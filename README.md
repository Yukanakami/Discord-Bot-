# Discord Time Tracking Bot

A Discord bot that allows users to track their work hours, breaks, and generate Excel reports of their time data.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Discord.py](https://img.shields.io/badge/discord.py-2.0%2B-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## Features

- ✅ Clock in/out functionality
- ⏰ Break tracking (start/end)
- 📊 Status checking
- 📝 Excel report generation
- 🔒 Role-based permissions for resetting data
- 👤 Ephemeral responses for privacy

## Commands

| Command | Description | Example |
|---------|-------------|---------|
| `!clock in` | Clock in for the day | `!clock in` |
| `!clock out` | Clock out for the day | `!clock out` |
| `!break start` | Start a break | `!break start` |
| `!break end` | End a break | `!break end` |
| `!status` | Check your current status | `!status` |
| `!report` | Generate an Excel report | `!report` |
| `!reset` | Reset all time data (admin only) | `!reset` |

## Installation

### Prerequisites

- Python 3.8 or higher
- A Discord bot token from the [Discord Developer Portal](https://discord.com/developers/applications)

### Steps

1. Clone or download this repository
2. Install the required dependencies:
   ```bash
   pip install discord.py openpyxl
