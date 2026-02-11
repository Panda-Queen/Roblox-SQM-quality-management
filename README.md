# Roblox SQM Quality Management (Final Project)

## Overview
This repository is my Software Quality Management (SQM) case study for the **Roblox platform** (player perspective).
It includes ISO 25010 quality goals, defects, risks, CMMI maturity justification, and a GitHub workflow (Issues + Project Board).

## System Scope (Player Perspective)
I focus on:
- Login and account access
- Joining games and multiplayer connection (disconnect/lag)
- Performance (loading time, FPS, ping)
- Chat and social features
- Safety tools (reporting, chat filtering, privacy settings)
- Payments/Robux from a player view

## Quality Model (ISO 25010) used
- Reliability
- Performance Efficiency
- Security
- Usability
- Maintainability

## Definitions
### Severity
- Critical: safety risk, money loss, or many users cannot use Roblox
- Major: big problem, many users affected, but system still partly usable
- Minor: small issue, workaround exists

### Priority
- High: fix ASAP
- Medium: fix after high items
- Low: fix later

## Workflow
Issues move in the board:
To Do → In Progress → Review/QA → Done

## Traceability Rule
Every Issue must include:
- Report section number
- Defect ID (D1–D10) or Risk ID (R1–R6)

Example:
Traceability: Report Section 4, Defect D4
