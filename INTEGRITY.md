# Integrity and Versioning

## What the checksum establishes

SHA-256 identifies the exact bytes of a published file. Matching hashes show that two copies are byte-for-byte identical. A checksum does not prove that every claim inside the file is correct; it protects the identity of the object being examined.

## Calculate SHA-256

### Windows PowerShell

```powershell
Get-FileHash -Algorithm SHA256 "Canonical-27-obstructions-of-deep-ethical-sense-making-processes-plus-12-fixes.md"
```

### Linux

```bash
sha256sum Canonical-27-obstructions-of-deep-ethical-sense-making-processes-plus-12-fixes.md
```

### macOS

```bash
shasum -a 256 Canonical-27-obstructions-of-deep-ethical-sense-making-processes-plus-12-fixes.md
```

Record the lowercase hexadecimal hash followed by two spaces and the repository-relative path in `MANIFEST.sha256`.

## Verify the manifest

From the repository root on Linux:

```bash
sha256sum --check MANIFEST.sha256
```

Comment lines beginning with `#` are ignored by common SHA-256 tools.

## Stable bytes

`.gitattributes` marks `CANONICAL/**` as `-text` so Git does not normalize line endings in canonical source objects.

No automated formatter, spelling checker, content generator, or cleanup script should run over `CANONICAL/**`.

## Immutable citation

For lasting citations, link to one of:

1. a specific commit URL;
2. a release tag;
3. a raw file URL pinned to a commit SHA.

A link to `main` identifies the current state and may change later.

## Version practice

Recommended release tag:

`canonical-YYYY-MM-DD-vN`

A corrected canonical file receives a new checksum. The reason for the correction should be visible in the commit or release notes. Do not force-push or erase earlier canonical history.
