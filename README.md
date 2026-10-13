# Table Por downloads

This repository distributes Table Por installers and signed update manifests.

**No public release has been published yet.** Installers will appear on the [Releases page](https://github.com/sparkclan123/buggy-table-releases/releases) after signing and validation.

## Install

- macOS Apple Silicon: choose the `darwin-aarch64.dmg` installer.
- macOS Intel: choose the `darwin-x86_64.dmg` installer.
- Windows x64: choose the `windows-x86_64.exe` installer.

## Updates

Signed release builds show an update button at the bottom right when a newer version is available. Save pending database edits, then choose **Update & restart**. Downloads are verified before installation. Updates replace the existing app using a full package; they are not differential patches.

Automatic checks can be disabled in the update menu. Update requests contact GitHub and its CDN; they never contain database credentials, queries or results.

The `.app.tar.gz`, `.sig` and `latest.json` assets are used by the updater. First-time users should download the `.dmg` or `.exe` installer. Checksums are provided in `SHA256SUMS.txt`.

This repository does not contain signing credentials or application source.
