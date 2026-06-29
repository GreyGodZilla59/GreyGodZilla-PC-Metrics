# Changelog

## v1.0.3 — 2026-06-28

- **Grey GodZilla** branding standardized across window title, tray, and settings
- **Version badge** shown in the header next to the title (`v1.0.3`)
- Window title now includes version: `Grey GodZilla PC Metrics v1.0.3`
- Config path uses `%APPDATA%\GreyGodZilla\` (reads legacy `GreyGodzilla` if present)

## v1.0.2 — 2026-06-27

- **FPS accuracy fix** — PresentMon now streams continuously instead of 1-second batch captures
- **Faster FPS refresh** — dashboard, overlay, and mini strip update ~20×/sec (50ms) instead of every 2 seconds
- **Lower FPS lag** — uses latest frame data with a tiny 3-frame weighted average instead of a 24-sample rolling average

## v1.0.1 — 2026-06-26

- Rebuilt without UPX compression to reduce antivirus false positives
- New SHA256 — re-scan on VirusTotal recommended

## v1.0.0 — 2026-06-26

Initial public release.