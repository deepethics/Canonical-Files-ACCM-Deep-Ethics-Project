# Canonical Index

This is the authoritative register of canonical source files in this repository.

A path listed here as **Canonical** must also have a matching SHA-256 entry in [MANIFEST.sha256](MANIFEST.sha256). Repository presence alone does not establish canonical status.

## Status vocabulary

| Status | Meaning |
|---|---|
| **Pending** | Reserved or announced, but the exact source has not yet been manually published and registered by John |
| **Canonical** | Manually published or approved by John, indexed here, and checksum-registered |
| **Superseded** | Former canonical version retained for provenance after a later version |
| **Withdrawn** | Retained for history but no longer presented by John as canonical |
| **Derived** | Summary, interpretation, comparison, or other noncanonical work |

## Register

| ID | Title | Path | Version/date | Status | SHA-256 | Related working reference |
|---|---|---|---|---|---|---|
| CF-ACCM-27+12-001 | Canonical 27 obstructions of deep ethical sense-making processes plus 12 fixes | [Markdown source](CANONICAL/27-plus-12/Canonical-27-obstructions-of-deep-ethical-sense-making-processes-plus-12-fixes.md) | [2026-09-17 / initial canonical publication](https://github.com/deepethics/Canonical-Files-ACCM-Deep-Ethics-Project/commit/5bd8508eaf402ca30c9241e6384fa54f9158119d) | **Canonical** | `4342a68afc418a64c36fe659f9221236c5eca3696434714336e3d340e6471d3c` | [27+12 working architecture](https://deepethics.github.io/ACCM-Deep-Ethics-Project/CORE/27-PLUS-12/) |

## Registration checklist

When John manually publishes a canonical file:

- [ ] Confirm the filename and exact path.
- [ ] Confirm that no tool reformatted or rewrote the content.
- [ ] Calculate SHA-256 from the published bytes.
- [ ] Replace **Pending** with **Canonical** in this index.
- [ ] Add the matching entry to `MANIFEST.sha256`.
- [ ] Record the immutable commit link.
- [ ] Optionally create a release tag for easier long-term citation.
- [ ] Add or verify links from the related working and testing repositories.
