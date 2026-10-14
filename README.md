# buggy-table downloads

Download [buggy-table 0.1.5 — Preview](https://github.com/sparkclan123/buggy-table-releases/releases/tag/v0.1.5).

Mac 0.1.5 fixes incomplete bundle signatures in 0.1.4. Windows remains on 0.1.4. This is a free test release. It has **no Apple Developer ID/notarization or Windows Authenticode certificate**, so the operating system may warn or block it. In-app updates are **disabled** in this preview. Install the next version manually.

## Download

- [Mac Apple Silicon (M series)](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.5/buggy-table_0.1.5_aarch64.dmg)
- [Mac Intel](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.5/buggy-table_0.1.5_x64.dmg)
- [Windows x64 (0.1.4)](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.4/buggy-table_0.1.4_x64-setup.exe)
- [SHA-256 checksums](https://github.com/sparkclan123/buggy-table-releases/releases/download/v0.1.5/SHA256SUMS.txt)

Mac: open the DMG and drag buggy-table into Applications, replacing the older app. Mac previews now have complete ad-hoc signatures, but are **not notarized or signed with Apple Developer ID**. After attempting to open the app, if macOS reports an unverified developer and you trust this download, use **System Settings → Privacy & Security → Open Anyway → Open** ([Apple instructions](https://support.apple.com/en-us/102445)). Do not disable Gatekeeper. If it still reports “damaged”, stop and check the SHA-256 checksum; report your macOS version and chip. Replacing the app keeps saved connection settings; do not remove its Application Support folder. Windows: open the EXE installer. Node.js and Rust are not required for users. If your device policy blocks unsigned applications, contact your administrator.

## Available features

PostgreSQL browsing and permitted manual cell edits, read-only MySQL/Redis access, table tabs, filters, sorting, resizable columns, SQL editor, saved local connections with optional OS password storage, PostgreSQL schema dropdown, and a compact Light/Dark/System icon beside the app version. AI chat is not enabled in this preview. This is not a production-certified release.

## Future signed releases

After signing services are configured, signed builds will support an update button at the bottom right. Updates verify signatures and replace the full package; they are not differential patches. Preview users will need to install the first signed version manually.

This repository contains distribution files, not application source or signing credentials. The automatically generated Source code archives contain this distribution repository only.
