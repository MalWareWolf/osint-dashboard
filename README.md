# 🕵️‍♂️ OSINT Intelligence Dashboard

**OSINT Intelligence Dashboard** is a modular, open-source platform for collecting, analyzing, and visualizing open-source intelligence (OSINT) data from multiple sources.  
It’s designed for **cybersecurity analysts, threat hunters, researchers, and OSINT investigators** who need to unify their intelligence workflow in a single place.

---

## ✨ Features
- **Data Collection** → Social media, threat feeds, domain/IP lookups, custom scrapers  
- **Enrichment Pipelines** → WHOIS, DNS, GeoIP, VirusTotal, and more  
- **Search & Indexing** → OpenSearch for lightning-fast queries  
- **Visualization & Analysis** → React/Tailwind dashboards + Power BI integration  
- **Alerting Engine** → Rule-based notifications on indicators of interest  
- **Exporting** → CSV, JSON, and Power BI templates  
- **Extensible Collectors** → Plug in your own data sources easily  

---

## 📂 Project Structure
apps/
api/ # FastAPI backend (REST + WebSocket)
web/ # React/Tailwind frontend
collectors/ # OSINT data collection jobs
workers/ # Async tasks & enrichment
config/ # Settings, env templates
infra/ # Docker Compose, database, OpenSearch configs
scripts/ # Development & maintenance scripts
powerbi/ # Power BI templates
docs/ # Architecture, API, and collector notes
