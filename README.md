# buggy-table downloads

Download [buggy-table 0.1.9 — Preview](https://github.com/sparkclan123/buggy-table-releases/releases/tag/v0.1.9) for Mac Apple Silicon or Mac Intel. Windows 0.1.9 is pending.

This release adds alternating rows in Data and Row details, draggable table tabs with a lifted preview and saved ordering, a thin tab scrollbar, compact schema refresh, and light-blue table icons. Browsing starts at 100 rows per page, with 50/100/250/500 choices. The Updates button opens this GitHub downloads page in your browser. Previous PostgreSQL connection reuse and deliberate row selection/editing remain included.

**Preview: install manually.** Versions 0.1.4–0.1.9 have in-app updates disabled. Publishing a release cannot turn on the updater in an already-installed app. Finish or discard unsaved edits, close buggy-table, and replace the app using the installer below. Keep the existing app data folder to retain saved connection settings.

Windows 0.1.9 and the full CI checks are waiting for GitHub Actions during [a service incident](https://www.githubstatus.com/incidents/8tzbpcnl75jp). The Mac installers were built and verified locally. Follow the [installer workflow](https://github.com/sparkclan123/buggy-table/actions/runs/39284299677); Windows users can use 0.1.8 in the meantime.

## Download

- [Mac Apple Silicon (M series)](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.9/buggy-table_0.1.9_aarch64.dmg)
- [Mac Intel](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.9/buggy-table_0.1.9_x64.dmg)
- [Windows x64 (previous 0.1.8; 0.1.9 pending)](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.8/buggy-table_0.1.8_x64-setup.exe)
- [SHA-256 checksums](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.9/SHA256SUMS.txt)
- [Build provenance](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.9/BUILD_INFO.txt)

## Install and preview limits

Mac: open the DMG and drag buggy-table into Applications, replacing the older app. The apps have complete ad-hoc signatures, but **no Apple Developer ID or notarization**. macOS may still show “damaged” with only Move to Trash; Open Anyway is not guaranteed. If macOS offers Open Anyway and you trust this download, follow [Apple's instructions](https://support.apple.com/en-us/102445). Do not disable Gatekeeper. If the app reports “damaged”, check the SHA-256 checksum and report your macOS version and chip. A Developer ID signed and notarized release is required for normal Mac distribution.

Windows: run the EXE installer and use the existing installation location. The installer has **no Authenticode certificate** and may show an unknown-publisher or SmartScreen warning. Managed devices may block unsigned apps. Node.js and Rust are not required for users.

## Available features

PostgreSQL browsing and permitted manual cell edits/staged row deletions, read-only MySQL/Redis access, table tabs with Cmd/Ctrl+W, symbolic filters and timestamp pickers, sorting, resizable/reorderable columns, read-only row details with formatted JSON, pagination and optional counts, SQL editor, database snapshot charts, saved local connections with optional OS password storage, PostgreSQL schema dropdown and refresh, and Light/Dark/System appearance. AI chat is not enabled in this preview. This is not a production-certified release.

## Future signed releases

After signing services are configured, signed builds will support automatic checks and installation through Update options at the bottom right. Updates verify signatures and replace the full package; they are not differential patches. Preview users will need to install the first signed version manually.

This repository contains distribution files, not application source or signing credentials. The automatically generated Source code archives contain this distribution repository only.
