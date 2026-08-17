# OpenSnap

Keyboard-first window snapping for macOS.

OpenSnap arranges the focused window into halves, quarters, center, maximize,
and other useful layouts. It includes configurable global shortcuts, clear
destination overlays, SnapBack, multi-display movement, and optional action
sounds that can mute automatically while another app is using the microphone.

Visit [jonkwheeler.com/opensnap](https://www.jonkwheeler.com/opensnap) for the
product page, launch video, installation guide, privacy details, and support.

## Launch media

- [Launch video (`opensnap-launch.mp4`)](https://github.com/jonkwheeler/opensnap-releases/releases/download/media-v1/opensnap-launch.mp4)
- [Video poster (`opensnap-launch-poster.jpg`)](https://github.com/jonkwheeler/opensnap-releases/releases/download/media-v1/opensnap-launch-poster.jpg)

## Download

Download the latest `OpenSnap.dmg` from this repository's
[Releases](https://github.com/jonkwheeler/opensnap-releases/releases/latest)
page. Each release also includes a SHA-256 checksum. Do not install unofficial
copies from another repository or download host.

OpenSnap requires macOS 14 or later.

## Install

1. Download the latest `OpenSnap.dmg` from Releases.
2. Open the disk image and drag OpenSnap into Applications.
3. Try to open OpenSnap from Applications, then dismiss the developer warning.
4. Open **System Settings → Privacy & Security**, scroll to Security, click
   **Open Anyway**, and confirm.
5. Launch OpenSnap and grant it Accessibility permission when prompted.

OpenSnap is distributed free of charge and is not Apple-notarized, so macOS
requires that one-time approval. You should never need to disable Gatekeeper
globally or run a Terminal command that removes quarantine protection.

Accessibility permission lets OpenSnap read and change the focused window's
position and size. OpenSnap does not use it to inspect the contents of windows.

To verify a download, place the DMG and checksum file together in Downloads,
then run:

```sh
cd ~/Downloads
shasum -a 256 -c OpenSnap-1.0.0.dmg.sha256
```

## Homebrew

OpenSnap does not currently provide a Homebrew Cask. The DMG is the primary
installation path because a Terminal installer would only hide the same
Gatekeeper approval behind a command.

## Privacy

OpenSnap has no accounts, subscriptions, or analytics. During normal use it
does not send network traffic. Microphone-aware sound muting observes device
activity only; OpenSnap does not record, listen to, or inspect audio.

## About this repository

This repository is the public distribution channel for official OpenSnap
releases and rendered launch media. It does not contain the OpenSnap source
code, internal planning documents, video source project, prompts, audio stems,
or production notes.

## License

Official OpenSnap application binaries are free for personal and internal
business use. See [LICENSE](LICENSE) for the complete terms.
