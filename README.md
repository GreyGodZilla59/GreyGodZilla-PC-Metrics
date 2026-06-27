# Grey Godzilla PC Metrics

Portable all-in-one Windows PC monitor — single `.exe`, no installer, no account.

![Grey Godzilla](greygodzilla_logo.png)

## Download

Download from [GitHub Releases](https://github.com/GreyGodZilla59/GreyGodZilla-PC-Metrics/releases/tag/v1.0.0).

Or grab `GreyGodZilla PC Metrics.exe` from this release folder.

**SHA256:** `E4E6C4703F974EBAD8B28D18C0E2B9F283A6F5C458D6B6372B983CA63DCC0C42`

## Quick start

1. Download and unzip anywhere (Desktop, `C:\Tools`, etc.)
2. Run `GreyGodZilla PC Metrics.exe`
3. Right-click the tray icon for overlay, benchmark, fans, and more

Windows SmartScreen may warn on first run — normal for unsigned indie apps.

## Features

### Live monitoring
- CPU, GPU, RAM, VRAM, temps, power, disk I/O, network
- Custom in-game overlay (drag fields, resize, themes)
- Mini strip + fullscreen dashboard
- FPS + frame-time stats (PresentMon bundled)

### Cooling & profiles
- Fan curves + presets (LibreHardwareMonitor bundled)
- Per-game profiles (overlay + fan behavior per title)
- Night / battery schedule automation

### Tools & diagnostics
- **Standalone benchmark** with **Score Book** (Good / Fair / Poor ratings)
- SMART storage health
- Throttling + power-efficiency insights
- Ping / latency monitor
- WHEA hardware error scan
- HTML health report
- Screenshot with stats
- Game session compare

### Quality of life
- 7 theme presets
- Streamer mode
- System tray quick actions
- Config saved to `%APPDATA%\GreyGodzilla\`

## Command line

```bat
"GreyGodZilla PC Metrics.exe" --benchmark --quick
"GreyGodZilla PC Metrics.exe" --benchmark
"GreyGodZilla PC Metrics.exe" --self-test
```

## Requirements

- Windows 10/11 (64-bit)
- NVIDIA GPU recommended for fullest GPU stats (`nvidia-smi`)
- Fan control depends on hardware support via LibreHardwareMonitor

## Known limits

- Windows only, portable exe (~52 MB)
- Benchmark scores are Grey Godzilla–specific — not comparable to 3DMark or Cinebench
- GPU stress in benchmark is light; Score Book focuses on CPU, RAM, disk, and thermals

## Data locations

| Path | Contents |
|------|----------|
| `%APPDATA%\GreyGodzilla\grey_godzilla_config.json` | Settings |
| `%APPDATA%\GreyGodzilla\data\` | History, benchmarks, reports |

## Feedback

Open a [GitHub Issue](https://github.com/PLACEHOLDER/GreyGodZilla-PC-Metrics/issues) with:
- GPU model + motherboard
- Whether fan control appeared
- Screenshots if overlay/UI looks wrong

## License

MIT — see LICENSE