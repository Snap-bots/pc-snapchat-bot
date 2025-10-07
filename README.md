# pc snapchat bot

## Short overview
pc snapchat bot is a desktop automation toolkit that automates Snapchat tasks from a PC. It solves repetitive account tasks (posting, messaging, story upload, friend actions) and provides a simple CLI + optional GUI for running automation reliably.

<p align="center"> 
  <a href="https://github.com/yourusername/pc-snapchat-bot">
    <img src="https://img.shields.io/badge/Try%20It%20Free-1E90FF?style=for-the-badge&logo=fire&logoColor=white" alt="Try it Free" width="30%">
  </a> 
</p>

<p align="center">
  <a href="https://discord.gg/vBu9huKBvy">
    <img src="https://img.shields.io/badge/Join-Discord-5865F2?logo=discord" alt="Join Discord">
  </a>
  <a href="https://t.me/devpilot1">
    <img src="https://img.shields.io/badge/Contact-Telegram-2CA5E0?logo=telegram" alt="Contact on Telegram">
  </a>
</p>

---

## Introduction
pc snapchat bot is a lightweight, modular project that lets teams and power users automate Snapchat flows from a Windows/Linux PC. Built for QA, growth testing, and repetitive content tasks, it combines device drivers (ADB), browser automation, and optional Appium for connected devices.

### 3 Key Benefits
- **Time-saving** — automates repetitive Snapchat tasks so your team focuses on strategy.  
- **Scalable** — runs multiple parallel jobs (local or Dockerized) and supports device farms.  
- **Safer** — includes randomization, delay profiles, and proxy support to reduce detection risk.

## Features
- CLI runner for scripted Snapchat flows (login, post story, send snap, add friend).  
- Optional GUI dashboard for non-developers.  
- Device & emulator support (ADB + Appium hooks).  
- Human-like action randomization and schedule/warm-up profiles.  
- Proxy and SMS/2FA integration hooks (pluggable).  
- Dockerized worker for headless/background execution.  
- Logging, retry logic, and basic metrics export (JSON).

<p align="center">
  <img src="pc-snapchat-bot.png" alt="snapchat-bot hero image" width="100%">
</p>

## Use Cases
- Bulk content publishing and story scheduling for marketing tests.  
- QA automation for Snapchat features (regression flows).  
- Growth experiments: follow/add/unfriend workflows with warm-up.  
- Demo / POC for device-farm based automation.

## Contact
<p align="center">
  <a href="https://discord.gg/vBu9huKBvy">
    <img src="https://img.shields.io/badge/Join-Discord-5865F2?logo=discord" alt="Join Discord">
  </a>
  <a href="https://t.me/devpilot1">
    <img src="https://img.shields.io/badge/Contact-Telegram-2CA5E0?logo=telegram" alt="Contact on Telegram">
  </a>
</p>

---

## Installation Instructions

### Pre-requisites
- Python 3.10+ (recommended) **or** Node.js 18+ (optional GUI).  
- ADB (for Android device control) if using real devices.  
- Docker (optional, for worker).  
- (Optional) Appium server for advanced device control.  
- Git client.

### Clone repo
```bash
git clone https://github.com/yourusername/pc-snapchat-bot.git
cd "pc-snapchat-bot"

