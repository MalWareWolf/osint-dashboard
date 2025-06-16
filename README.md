# 🔍 OSINT Intelligence Dashboard

This project is a custom-built Open-Source Intelligence (OSINT) dashboard that consolidates threat intelligence from multiple sources into a centralized and visual interface. Built with **Flask** and integrated with **Power BI**, this tool helps with early threat detection, profiling, and situational awareness.

---

## 🧠 Purpose

To assist cybersecurity professionals, blue teams, and researchers in collecting, organizing, and analyzing public data on IPs, domains, malware hashes, and threat actors from a single, user-friendly interface.

---

## 🧰 Stack & Technologies

- **Backend:** Python 3.x + Flask
- **Frontend:** HTML + Bootstrap (Flask templates)
- **Data Visualization:** Power BI Embedded + Pandas
- **APIs Used:**
  - Shodan
  - VirusTotal
  - AbuseIPDB
  - WhoisXML
  - BuiltWith
  - Custom Threat Feed JSON

---

## 🚨 Key Features

| Feature                         | Description                                      |
|--------------------------------|--------------------------------------------------|
| 🔍 Search Dashboard             | Lookup by IP, Domain, Email, or Hash             |
| 📊 Power BI Visuals            | Real-time visualization of feed trends           |
| 🧩 Modular API Integration     | Easily add/remove data sources via config files  |
| 📝 Report Generation           | Export PDF/CSV threat reports                    |
| 🔐 API Key Vault               | Secure API management via `.env` file            |

---

## 🧪 Example Use Cases

- Incident response enrichment
- Threat actor infrastructure mapping
- Campaign pattern tracking
- IP/domain risk scoring for firewall rules
- Automated OSINT collection

---

## 📸 Screenshots

> _(Stored in `/docs/`)_

![OSINT Dashboard Screenshot](docs/osint-ui-screenshot.png)

---

## 📁 Folder Structure

```bash
osint-dashboard/
├── app/
│   ├── templates/
│   ├── static/
│   ├── routes/
│   └── api_clients/
├── docs/
│   └── osint-ui-screenshot.png
├── .env.example
├── requirements.txt
├── app.py
└── README.md
