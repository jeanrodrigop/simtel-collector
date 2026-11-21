# SimTel Ranking: Collector

Installers for the SimTel Ranking collector, the open global leaderboard for racing simulator lap times. The collector runs on your PC, reads game telemetry, and submits valid laps to the leaderboard.

This repository contains only published releases. They are generated automatically.

## Download

Open [last version](../../releases/latest) and download:

| System | File |
|---|---|
| Windows | `SimtelCollector-win-Setup.exe` |
| Linux | `SimtelCollector-linux.AppImage` (then, `chmod +x` and open) |
| Docker | `docker pull ghcr.io/jeanrodrigop/simtel-collector:latest` |

The collector updates itself automatically: it checks for new versions on startup, downloads them in the background, and installs them when you close the application.

Versions marked as **pre-release** (`u*`) are for testing and submit laps to the test environment, not to the official leaderboard.
