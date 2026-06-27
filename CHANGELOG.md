# Changelog

## v1.0.2 — 2026-06-27

- **FPS accuracy fix** — PresentMon now streams continuously instead of 1-second batch captures
- **Faster FPS refresh** — dashboard, overlay, and mini strip update ~20×/sec (50ms) instead of every 2 seconds
- **Lower FPS lag** — uses latest frame data with a tiny 3-frame weighted average instead of a 24-sample rolling average

## v1.0.1 — 2026-06-26

- Rebuilt without UPX compression to reduce antivirus false positives
- New SHA256 — re-scan on VirusTotal recommended

## v1.0.0 — 2026-06-26

Initial public release.

### Highlights
- Portable single-exe Windows PC monitor
- Live dashboard, tray, customizable overlay
- Fan curves + per-game profiles
- Standalone benchmark with Score Book ratings
- SMART storage, ping monitor, WHEA scan
- Mini strip, fullscreen dashboard, streamer mode
- HTML health report + screenshot with stats
- CLI: `--benchmark`, `--self-test`