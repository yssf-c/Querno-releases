# Querno downloads

Querno is a local LaTeX editor with a live PDF preview, native Mac controls, and built-in project history.

**Website:** https://querno.vercel.app

## Install on Mac

Requires **macOS 13.5 or later on Apple Silicon**.

1. [Download Querno 1.0.0](https://github.com/yssf-c/Querno-releases/releases/download/v1.0.0/Querno-1.0.0-macOS-arm64.zip).
2. Open the ZIP archive and drag **Querno.app** into Applications.
3. Open Querno from Applications or Spotlight.

The app includes its runtime and typesetter; Node, Homebrew, and a separate TeX installation are not required. The first build of a document needs internet access to fetch its TeX packages. Projects stay on your Mac in `~/.querno/`.

This release is ad-hoc signed and is not yet Developer ID signed or notarized. macOS may require permission under **System Settings → Privacy & Security** before the first launch.

## Verify the download

Download the [SHA-256 checksum](https://github.com/yssf-c/Querno-releases/releases/download/v1.0.0/Querno-1.0.0-macOS-arm64.zip.sha256) beside the ZIP, then run:

```sh
shasum -a 256 -c Querno-1.0.0-macOS-arm64.zip.sha256
```

This repository distributes release archives. Third-party notices and licenses are included in the app bundle.
