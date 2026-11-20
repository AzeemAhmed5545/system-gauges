<p align="center"><img src="docs/azivo-oval.png" width="320" alt="azivo"></p>

# System Gauges

Modern analog desktop gauges for Windows: a small always-on-top instrument cluster that shows your PC's vital signs live.

## Download

**[Download the latest installer from Releases](../../releases/latest)** (`SystemGauges-Setup.exe`, about 140 KB).

Requires Windows 10 or 11. Nothing else to install.

> The installer isn't digitally signed yet, so Windows SmartScreen may show *"Windows protected your PC"*. Click **More info → Run anyway**.

## Gauges

| Gauge | Shows |
|---|---|
| **CPU** | Load %, busiest app |
| **MEMORY** | % used, GB used, cleanup status (blinks red at its limit) |
| **CLOCK** | Current GHz, % of base clock, power-plan mode |
| **TEMP** | °C from the system's thermal sensor |
| **FAN** | Fan RPM (Dell laptops) |
| **NET** | Live download/upload Mbps, built-in speed test |

Arcs are cyan/green when normal, amber when high and red when critical.

## Features

- **Always on screen:** stays on top and recovers after display changes, sleep and Explorer restarts.
- **Self-healing:** restarts itself if it crashes or stops responding.
- **Starts with Windows**, light on resources (about 0.25 MB on disk).
- **Hidden auto-cleanup** of old temp files every few minutes, and memory trimming when RAM runs high.
- **Auto power plan:** switches to High performance under heavy load and back to Balanced when idle.
- **Speed test:** double-click the NET gauge.
- **Layouts and sizes:** Row, Column or Grid; Mini, Small or Large. Right-click the gauges for all options.

## Uninstall

**Settings → Apps → System Gauges → Uninstall.**

## License

Copyright © 2026 azivo. All rights reserved. See [LICENSE](LICENSE).
The source code is not public.
