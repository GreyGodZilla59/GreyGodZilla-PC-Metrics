# Grey Godzilla PC Metrics

Portable all-in-one Windows PC monitor — single `.exe`, no installer, no account.

![Grey Godzilla](greygodzilla_logo.png)

## Download

Download from [GitHub Releases](https://github.com/GreyGodZilla59/GreyGodZilla-PC-Metrics/releases/latest).

**v1.0.2** — FPS accuracy and refresh-rate fix (streaming PresentMon + 50ms UI updates).

**SHA256:** `BED62CD0F4E79710E4817130B92E1CD99D55CF348EBEC957D9D0B473201F2240`

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
- **Real-time FPS** + frame-time stats (PresentMon bundled)

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

Open a [GitHub Issue](https://github.com/GreyGodZilla59/GreyGodZilla-PC-Metrics/issues) with:
- GPU model + motherboard
- Whether fan control appeared
- Screenshots if overlay/UI looks wrong

## License

MIT — see LICENSE