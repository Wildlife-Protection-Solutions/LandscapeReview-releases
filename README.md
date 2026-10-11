# Landscape Review releases

This repository holds published releases of Landscape Review. It contains no source code and no project data.

**Installed copies check here once a day** while they are running. When a newer version is available, it is downloaded in the background and checked against the project's release signature. It is installed only when someone chooses **Install update** in **Settings & support**.

**Each release contains:**

| File | Purpose |
|---|---|
| `release.json` | Version, release notes and file checksums. |
| `release.json.sig` | Signature of `release.json`. Installations refuse a release without a valid signature. |
| `LandscapeReview-Update-<version>.lrupdate` | A small update containing only the changed files. |
| `LandscapeReview-Setup-<version>.exe` | The complete installer, for new installations. |

Releases marked *pre-release* are pilot versions. Only installations that choose **Receive pilot updates** take them.

Releases are published by the maintainers with the project's publish command. Please do not upload files here by hand.
