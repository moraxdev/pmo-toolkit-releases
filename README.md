# PMO Toolkit — Releases

Download the latest **PMO_Toolkit.exe** from [Releases](../../releases/latest) (or from the `builds/` folder).
It is portable: no installation, just run it. Installed copies update themselves from this page.

Requirements: Windows 10/11, Microsoft Edge WebView2 Runtime, Microsoft Project and Microsoft Excel.

© 2026 Eng. Amr Karam. All rights reserved.

## Installer
`installers/` holds a normal Windows installer of the same version (listed as `installer` in
`latest.json`; Sahra Hub installs from it). It installs per user to
`%LOCALAPPDATA%\Programs\PMO Toolkit`. Make it with `python3 make_installer.py builds/<exe> <version>`
after updating `latest.json` (needs `makensis`).
