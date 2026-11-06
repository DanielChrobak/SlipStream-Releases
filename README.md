# SlipStream releases

SlipStream streams and controls a Windows desktop from a browser.

- [Download the latest Windows x64 installer](https://github.com/DanielChrobak/SlipStream-Releases/releases/latest)
- [Browse all versions and release notes](https://github.com/DanielChrobak/SlipStream-Releases/releases)
- [Visit the product website and try the browser demo](https://danielchrobak.github.io/SlipStream-Website/)

Open a release and choose its `SlipStream-<version>-windows-x64-setup.exe` asset. The adjacent `.sha256` asset contains the expected installer digest. In PowerShell, run `Get-FileHash -Algorithm SHA256` with the downloaded installer path and compare the hash to the first field in that file.

This repository hosts SlipStream's public distribution. Release tags point to this downloads repository. Each full release uses the `v<version>` tag and includes the versioned installer and its checksum. The website and Windows host check GitHub's latest full release.
