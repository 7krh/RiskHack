# RiskCheat

RiskCheat — a research & educational scaffold for experimenting with a local/test copy of **Risk: Global Domination**.  
> ⚠️ **Important — For ethical use only.**  
> Use RiskCheat only in controlled environments (your own accounts, private servers, or with explicit permission). Do **not** use this project to cheat in online games, circumvent anti-cheat mechanisms, infringe terms of service, or harm other users. The authors are not responsible for misuse.

---

## Table of contents

- [Overview](#overview)  
- [Features](#features)  
- [Quick notes & safety](#quick-notes--safety)  
- [Parameters (starter CLI)](#parameters-starter-cli)  
- [Planned / safe features](#planned--safe-features)  
- [Installation (example)](#installation-example)  
- [Project layout (suggested)](#project-layout-suggested)  
- [Contributing](#contributing)  
- [License](#license)

---

## Overview

This repository is an initial scaffold intended for offline research, education, and experimentation with exported or local copies of game state for **Risk: Global Domination**. It provides starter modules, CLI ideas, and documentation placeholders so you can iterate safely and responsibly.

**Important:** This project does **not** include or condone tools that bypass protections or give unfair advantages on live servers. All functionality should be implemented and used in offline/test environments only.

---

## Features

- **Unlock All (simulation, offline only)**  
  - Unlock premium features (cosmetics, maps, etc.) in local/test state files — **does not** grant server-side currency or entitlements.  
  - Note: *Does not grant unlimited coins or server-side currency.*

- **Modify Troops**  
  - Change troop attributes in exported or local state files for testing and simulation.

- **Change Card Types**  
  - Alter card metadata in offline state files for replay and analysis.

---

## Quick notes & safety

- This repository does **NOT** provide or promote methods to bypass anti-cheat or gain unfair advantage in online matches.  
- Always test on private/local copies of the game or explicitly permitted test environments.  
- Keep secrets out of the repo (API keys, account credentials, server IPs).  
- Any code that touches live clients, memory, or network traffic must:
  - clearly require explicit permission,
  - implement an offline-only enforcement mode,
  - include a documented risk checklist.

---

## Parameters (starter CLI)

These flags are **placeholders** for a future CLI. They should be validated and implemented with offline-only checks.

