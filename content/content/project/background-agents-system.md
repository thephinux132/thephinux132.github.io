---
title: Background Agents System
date: 2026-04-01T08:00:00-07:00
type: project
tags: [bash, systemd, automation, monitoring]
status: active
summary: "Four persistent background agents auto-started via systemd on WSL2: night_watch (network/security, 5min), storage_watch (disk, 30min), docker_watch (containers, 5min), windows_space_watch (C: drive cleanup, 2h). Terminal banner shows green/red status on login."
reading_time: 2
---

- System of four persistent background agents managed by systemd on WSL2.
- **night_watch**: Monitors network and security status every 5 minutes.
- **storage_watch**: Checks disk health and usage every 30 minutes.
- **docker_watch**: Monitors container status every 5 minutes.
- **windows_space_watch**: Performs C: drive cleanup every 2 hours.
- Includes a terminal banner integration that displays real-time status (green/red) upon user login.

Next step: Continue development.
