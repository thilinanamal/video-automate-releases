# Video Automate for Mac — downloads

This repository only hosts release files for the Video Automate macOS app.
It contains no application source code.

Each release has:

- **Video-Automate-<version>.dmg** — the app. Open it, drag Video Automate into
  Applications, and follow *How to open Video Automate* inside the disk image.
- **engine-…vacp** and **media-tools-…vacp** — processing components the app
  downloads and verifies on first launch. You do not need to download these
  yourself.
- **third-party-sources-…tar.gz** — optional corresponding source code and build
  records for the open-source components the app uses, as their licences require.

The app is signed by its developer but not notarized by Apple, so macOS asks you
to approve it once in **System Settings → Privacy & Security → Open Anyway**.
See Apple's guide: https://support.apple.com/en-us/102445

Requirements: a Mac with Apple silicon and the macOS version listed on the release.
