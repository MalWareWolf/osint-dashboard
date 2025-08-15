# 🕵️‍♂️ OSINT Intelligence Dashboard

This repository contains a simple **OSINT dashboard for Windows** built with
Python and the Tkinter GUI toolkit.  The application allows analysts to
quickly perform common open‑source intelligence lookups from a single
interface.

## ✨ Features
- WHOIS lookup for domains and IP addresses
- DNS resolution
- GeoIP lookup using the `ip-api.com` service
- Scrollable output window and clear button

## 🚀 Getting Started (Windows)
1. Install [Python 3](https://www.python.org/downloads/windows/)
2. Install dependencies:
   ```powershell
   pip install -r requirements.txt
   ```
3. Run the dashboard:
   ```powershell
   python osint_dashboard.py
   ```

## 📦 Project Structure
```text
osint_dashboard.py  # Tkinter application
requirements.txt    # Required Python packages
```

The application is intentionally minimal so you can extend it with
additional OSINT integrations or adapt it for your workflow.
