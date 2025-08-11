# 🕵️‍♂️ OSINT Intelligence Dashboard

**OSINT Intelligence Dashboard** is a modular, open-source platform for collecting, analyzing, and visualizing open-source intelligence (OSINT) data from multiple sources.  
It’s designed for **cybersecurity analysts, threat hunters, researchers, and OSINT investigators** who need to unify their intelligence workflow in a single place.

## ✨ Features
- **Data Collection** from social media, threat feeds, domain/IP lookups, and custom scrapers
- **Enrichment Pipelines** for WHOIS, DNS, GeoIP, VirusTotal, and more
- **Search & Indexing** with OpenSearch for lightning-fast queries
- **Visualization & Analysis** via React-based dashboards and Power BI integration
- **Alerting Engine** for rule-based notifications on indicators of interest
- **Exporting** to CSV, JSON, and Power BI templates
- **Extensible Collectors** for adding your own data sources

---

## 📂 Project Structure
```text
apps/
  api/         # FastAPI backend (REST + WebSocket)
  web/         # React/Tailwind frontend
  collectors/  # OSINT data collection jobs
  workers/     # Async tasks & enrichment
config/        # Settings, env templates
infra/         # Docker Compose, database, OpenSearch configs
scripts/       # Development & maintenance scripts
powerbi/       # Power BI templates
docs/          # Architecture, API, and collector notes
