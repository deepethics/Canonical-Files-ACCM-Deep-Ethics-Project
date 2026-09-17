# Canonical Index

This is the authoritative register of canonical source files and canonical interaction records in this repository.

A path listed here as **Canonical** must also have a matching SHA-256 entry in [MANIFEST.sha256](MANIFEST.sha256). Repository presence alone does not establish canonical status.

A canonical interaction record authenticates the selected historical record as published by John. It does not automatically make every statement or A.I. response inside it a canonical claim of the **ACCM Deep Ethics Project**.

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
| CF-ACCM-QPTH-001 | Hypotheses and theories | [Markdown source](CANONICAL/questions-perspectives-theories-and-hypotheses/Hypotheses-and-theories.md) | [2026-09-17 / spelling corrections approved by John](https://github.com/deepethics/Canonical-Files-ACCM-Deep-Ethics-Project/commit/3b7c4401292af9ecac05957b0a3d930ab93448d9) | **Canonical** | `53f083405e45f98f35caf2640b4a6e073602e30545990950e3dfd2a58523d8b8` | [Deeper Introduction](https://deepethics.github.io/ACCM-Deep-Ethics-Project/DEEPER-INTRODUCTION/) |
| CF-ACCM-DS-001 | John Testing Arena Multiple A.I.s — Deep Session | [Canonical interaction record](CANONICAL/questions-perspectives-theories-and-hypotheses/John-Testing-Arena-Multiple-AIs-Deep-Session-2026-09-17-and-18.md) | [2026-09-17–18 / published under corrected filename](https://github.com/deepethics/Canonical-Files-ACCM-Deep-Ethics-Project/commit/a2c8a8b9dd969f9d335e4d17f2031bd13228b092) | **Canonical** | `ed38c219d888fe298818a2171050b996fa26af2178b676b7278ada005723f4fe` | [Deep Sessions Index](CANONICAL/questions-perspectives-theories-and-hypotheses/DEEP-SESSIONS-INDEX.md) · [Shared Desk](https://deepethics.github.io/ACCM-Deep-Ethics-Project/FORUM/0002-shared-desk/) |

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
