# love-sandwiches

[A small project that interacts with Google Sheets to manage sandwich-related data.]

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [How to Use](#how-to-use)
- [What I Learned](#what-i-learned)

---

## Overview
love-sandwiches is a small Python utility that demonstrates reading from and writing to Google Sheets (via `gspread` and Google OAuth) to manage simple sandwich-related data. It's intended as a compact example of authenticating with Google APIs and performing lightweight spreadsheet operations.

## Features
- Authenticate with Google Sheets using OAuth
- Read and write rows from a Google Sheet using `gspread`
- Simple command-line runner (`run.py`) to exercise the functionality

## Technologies Used
- **Languages:** Python
- **Libraries:** gspread, google-auth, requests
- **Other:** Google Sheets API

## How to Use

### Local Setup
```bash
git clone <repo-url>
cd love-sandwiches
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### Run
```bash
python run.py
```

## What I Learned
- Working with Google OAuth flows in a CLI context
- Using `gspread` to interact with Google Sheets programmatically
- Packaging a minimal Python utility with a clear entrypoint

---
**Bootcamp Project** | May 2026
