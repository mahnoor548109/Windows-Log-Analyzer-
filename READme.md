
# Mini SIEM – Windows & Linux Security Monitoring

A Windows security monitoring project that collects, centralizes, and visualizes Windows Security Event Logs using Grafana Alloy, Loki, and Grafana.

## Overview

The goal of this project is to build a centralized monitoring system for Windows & Linux security events. It collects logs from a Windows machine, sends them to Grafana Loki, and displays useful security insights through a Grafana dashboard.

The project will also include automated alerts through Discord or Email for selected security events.

## Tech Stack

- Windows 11
- PowerShell
- Grafana Alloy
- Ubuntu Server
- Grafana Loki
- Grafana
- Docker Compose

## Architecture

```text
Windows Event Logs
        |
   Grafana Alloy
        |
    Grafana Loki
        |
      Grafana
        |
   Security Alerts
        |
   Discord / Email
```

## Planned Features

- Windows Security Event Log collection
- Centralized log storage
- Interactive Grafana dashboard
- Failed and successful login monitoring
- Suspicious activity detection
- Linux log monitoring aur event correlation.
- Discord / Email notifications

## Project Status

Currently in Development 🚧

## Author

**Mahnoor Saleem**

Cybersecurity Enthusiast | BS Computer Science

[GitHub Profile](https://github.com/mahnoor548109)

