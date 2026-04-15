# Lydex

An audiophile-grade Android music player focused on **bit-perfect USB DAC playback**, transparent local/remote library management, and honest, low-overhead UX.

<p align="center">
  <img src="branding/lydex-logo-1024.png" width="180" alt="Lydex logo"/>
</p>

## Features

### Playback
- **Bit-perfect USB exclusive mode** — samples delivered to the DAC untouched, no system mixer, no resampling, no volume scaling.
- **Hardware volume routing** — volume keys route to the DAC's own attenuator when available.
- **Lydex Tone voicing presets** — Transparent / Precise / Stable / Warm, each tuning the USB feedback gate for a different tonal character while staying bit-perfect.
- **Low idle CPU** — typically ~15% during screen-off USB DAC playback.
- **Parametric EQ** (optional, non-bit-perfect).
- **Gapless playback** and stop-ramp for seamless track switching.

### Library
- Local folders via SAF (Android 11+ Scoped Storage compatible).
- Remote sources: **SMB**, **FTP**, **WebDAV** with incremental scan.
- **CUE sheet** support for single-file albums (FLAC / APE / WAV / DSF).
- **Auto-scan** with visible progress (listing / probing phases).
- Album-artwork extraction with dynamic Palette-driven detail pages.

### Integrations
- Last.fm scrobbling (user opt-in).
- In-app feedback and log collection to support.

### Formats
Lossless: FLAC, ALAC, APE, WavPack, WAV, AIFF, DSF.
Lossy: MP3, AAC, Ogg Vorbis, Opus.

## Project status

Current version: **0.1.1** (alpha). Active development. Feedback and logs welcome — see in-app **Settings → Support**.

## Support

- Email: [lydex.support@gmail.com](mailto:lydex.support@gmail.com)
- Issues: please include device model, Android version, and a log attached via **Send log** inside the app.

## Privacy

See [privacy.md](privacy.md). In short: no telemetry, no analytics, no ads, no accounts. All library and credential data stays on device.

## License

Lydex is closed-source application software. The app uses third-party open source components; their licenses are listed in-app under **Settings → About → Open source licenses**.

© 2026 Lydex. All rights reserved.
