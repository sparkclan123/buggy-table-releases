# buggy-table downloads

Download [buggy-table 0.1.7 — Preview](https://github.com/sparkclan123/buggy-table-releases/releases/tag/v0.1.7) for Mac Apple Silicon, Mac Intel or Windows x64.

This release adds highlighted cell drafts and staged row deletions, timestamp pickers, local column ordering, 50/100/250/500-row pages, optional exact counts, collapsible controls and full-value display. It also reduces PostgreSQL metadata work and fixes MySQL connection diagnostics and Redis key browsing, with real snapshot charts for all three engines. See the release notes for details and validation.

**Preview: install manually.** Versions 0.1.4–0.1.7 have in-app updates disabled. Publishing a release cannot turn on the updater in an already-installed app. Finish or discard unsaved edits, close buggy-table, and replace the app using the installer below. Keep the existing app data folder to retain saved connection settings.

## Download

- [Mac Apple Silicon (M series)](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.7/buggy-table_0.1.7_aarch64.dmg)
- [Mac Intel](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.7/buggy-table_0.1.7_x64.dmg)
- [Windows x64](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.7/buggy-table_0.1.7_x64-setup.exe)
- [SHA-256 checksums](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.7/SHA256SUMS.txt)
- [Build provenance](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.7/BUILD_INFO.txt)

## Install and preview limits

Mac: open the DMG and drag buggy-table into Applications, replacing the older app. The apps have complete ad-hoc signatures, but **no Apple Developer ID or notarization**. macOS may still show “damaged” with only Move to Trash; Open Anyway is not guaranteed. If macOS offers Open Anyway and you trust this download, follow [Apple's instructions](https://support.apple.com/en-us/102445). Do not disable Gatekeeper. If the app reports “damaged”, check the SHA-256 checksum and report your macOS version and chip. A Developer ID signed and notarized release is required for normal Mac distribution.

Windows: run the EXE installer and use the existing installation location. The installer has **no Authenticode certificate** and may show an unknown-publisher or SmartScreen warning. Managed devices may block unsigned apps. Node.js and Rust are not required for users.

## Available features

PostgreSQL browsing and permitted manual cell edits/staged row deletions, read-only MySQL/Redis access, table tabs with Cmd/Ctrl+W, symbolic filters and timestamp pickers, sorting, resizable/reorderable columns, pagination and optional counts, SQL editor, database snapshot charts, saved local connections with optional OS password storage, PostgreSQL schema dropdown and refresh, and Light/Dark/System appearance. AI chat is not enabled in this preview. This is not a production-certified release.

## Future signed releases

After signing services are configured, signed builds will support an update button at the bottom right. Updates verify signatures and replace the full package; they are not differential patches. Preview users will need to install the first signed version manually.

This repository contains distribution files, not application source or signing credentials. The automatically generated Source code archives contain this distribution repository only.
