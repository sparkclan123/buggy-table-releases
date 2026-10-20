# buggy-table downloads

Download [buggy-table 0.1.10 — Preview](https://github.com/sparkclan123/buggy-table-releases/releases/tag/v0.1.10) for Mac Apple Silicon, Mac Intel or Windows x64.

This release adds undo/redo for unsaved table edits, copying selected rows into new PostgreSQL drafts with Cmd/Ctrl+C and Cmd/Ctrl+V, expanded editors for long cell values, Cmd/Ctrl+Enter SQL execution, and mouse-wheel scrolling for overflowing tabs. MySQL adds an explicit encrypted/unverified TLS compatibility option; verified TLS remains the default. Previous table styling, row details, draggable tabs, 100-row pagination and PostgreSQL connection reuse remain included.

**Preview: install manually.** Versions 0.1.4–0.1.10 have in-app updates disabled. The Updates button opens this downloads page. Publishing a release cannot turn on the updater in an already-installed app. Finish or discard unsaved edits, close buggy-table, and replace the app using the installer below. Keep the existing app data folder to retain saved connection settings.

## Download

- [Mac Apple Silicon (M series)](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.10/buggy-table_0.1.10_aarch64.dmg)
- [Mac Intel](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.10/buggy-table_0.1.10_x64.dmg)
- [Windows x64](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.10/buggy-table_0.1.10_x64-setup.exe)
- [SHA-256 checksums](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.10/SHA256SUMS.txt)
- [Build provenance](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.10/BUILD_INFO.txt)

## Install and preview limits

Mac: open the DMG and drag buggy-table into Applications, replacing the older app. The apps have complete ad-hoc signatures, but **no Apple Developer ID or notarization**. macOS may still show “damaged” with only Move to Trash; Open Anyway is not guaranteed. If macOS offers Open Anyway and you trust this download, follow [Apple's instructions](https://support.apple.com/en-us/102445). Do not disable Gatekeeper. If the app reports “damaged”, check the SHA-256 checksum and report your macOS version and chip. A Developer ID signed and notarized release is required for normal Mac distribution.

Windows: run the EXE installer and use the existing installation location. The installer has **no Authenticode certificate** and may show an unknown-publisher or SmartScreen warning. Managed devices may block unsigned apps. Node.js and Rust are not required for users.

## Available features

PostgreSQL browsing and permitted manual INSERT/UPDATE/DELETE, read-only MySQL/Redis access, table tabs with Cmd/Ctrl+W, symbolic filters and timestamp pickers, sorting, resizable/reorderable columns, read-only row details with formatted JSON, pagination and optional counts, SQL editor, database snapshot charts, saved local connections with optional OS password storage, PostgreSQL schema dropdown and refresh, and Light/Dark/System appearance. Copied rows stay unsaved until Save; generated keys are omitted, and required manual keys must be filled. AI chat is not enabled in this preview. This is not a production-certified release.

## Future signed releases

After signing services are configured, signed builds will support automatic checks and installation through Update options at the bottom right. Updates verify signatures and replace the full package; they are not differential patches. Preview users will need to install the first signed version manually.

This repository contains distribution files, not application source or signing credentials. The automatically generated Source code archives contain this distribution repository only.
