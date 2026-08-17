# OpenSnap

Keyboard-first window snapping for macOS.

OpenSnap arranges the focused window into halves, quarters, center, maximize,
and other useful layouts. It includes configurable global shortcuts, clear
destination overlays, SnapBack, multi-display movement, and optional action
sounds that can mute automatically while another app is using the microphone.

Visit [jonkwheeler.com/opensnap](https://www.jonkwheeler.com/opensnap) for the
product page, launch video, installation guide, privacy details, and support.

## Download

The first public download will appear on this repository's
[Releases](https://github.com/jonkwheeler/opensnap-releases/releases) page after
the macOS application has been signed and notarized. Do not install unofficial
copies from another repository or download host.

OpenSnap requires macOS 14 or later.

## Install

1. Download the latest signed and notarized `OpenSnap.dmg` from Releases.
2. Open the disk image and drag OpenSnap into Applications.
3. Launch OpenSnap and approve it under **System Settings → Privacy & Security → Accessibility**.

Accessibility permission lets OpenSnap read and change the focused window's
position and size. OpenSnap does not use it to inspect the contents of windows.

## Homebrew

Homebrew installation is planned after the first signed and notarized public
release. Until then, install OpenSnap from the official DMG.

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
