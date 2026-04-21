<div align="center">

# Hi, I'm Guido 👋

**Python Developer & Technical Analyst — building real-world backend services, automation tools and full-stack apps.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=flat-square)](https://www.linkedin.com/in/guido-delponte-7a26033a4/)
![Location](https://img.shields.io/badge/Buenos_Aires-Argentina-lightgrey?style=flat-square)
![Focus](https://img.shields.io/badge/Python_·_FastAPI_·_Django-306998?logo=python&logoColor=white&style=flat-square)
![Status](https://img.shields.io/badge/Open_to-Opportunities-brightgreen?style=flat-square)

<a href="https://github.com/GDelpo"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=GDelpo&layout=compact&theme=tokyonight&hide_border=true&langs_count=10&card_width=480" alt="Top languages" /></a>

</div>

---

### 🧑‍💻 About me

Python Developer & Technical Analyst with 3+ years designing and shipping **end-to-end solutions** — from automation scripts and internal tools to scalable APIs, microservice suites and full-stack apps. I care about code that is readable, well-structured, and solves a real problem.

- 🏢 **Currently:** Python Developer & Systems Analyst at [Example Corp](https://example.com/) (Dec. 2020 – present). Led **ExampleOnline** rollout, designed the FastAPI microservice suite, modernized legacy PHP stacks, and built the internal documentation portal.
- 🧰 **On the side:** independent software developer & tech consultant since 2018 — e-commerce, CMSs, data processing, custom integrations.
- 🎓 **Background:** Systems Analyst (ORT Argentina), AI Certification (ITBA), ongoing Software Development (ISTEA).

### 🛠️ Tech I use day-to-day

<p align="left">
  <img alt="Python"     src="https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=for-the-badge">
  <img alt="FastAPI"    src="https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white&style=for-the-badge">
  <img alt="Django"     src="https://img.shields.io/badge/-Django-092E20?logo=django&logoColor=white&style=for-the-badge">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white&style=for-the-badge">
  <img alt="Redis"      src="https://img.shields.io/badge/-Redis-DC382D?logo=redis&logoColor=white&style=for-the-badge">
  <img alt="Docker"     src="https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white&style=for-the-badge">
  <img alt="Traefik"    src="https://img.shields.io/badge/-Traefik-24A1C1?logo=traefikproxy&logoColor=white&style=for-the-badge">
  <img alt="React"      src="https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black&style=for-the-badge">
  <img alt="Astro"      src="https://img.shields.io/badge/-Astro-BC52EE?logo=astro&logoColor=white&style=for-the-badge">
  <img alt="Tailwind"   src="https://img.shields.io/badge/-Tailwind-38BDF8?logo=tailwindcss&logoColor=white&style=for-the-badge">
  <img alt="Laravel"    src="https://img.shields.io/badge/-Laravel-FF2D20?logo=laravel&logoColor=white&style=for-the-badge">
  <img alt="Spring"     src="https://img.shields.io/badge/-Spring_Boot-6DB33F?logo=spring&logoColor=white&style=for-the-badge">
  <img alt="GCP"        src="https://img.shields.io/badge/-Google_Cloud-4285F4?logo=googlecloud&logoColor=white&style=for-the-badge">
  <img alt="Grafana"    src="https://img.shields.io/badge/-Grafana-F46800?logo=grafana&logoColor=white&style=for-the-badge">
  <img alt="Docusaurus" src="https://img.shields.io/badge/-Docusaurus-3ECC5F?logo=docusaurus&logoColor=white&style=for-the-badge">
  <img alt="Git"        src="https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white&style=for-the-badge">
</p>

---

## 📚 Projects

Everything is **MIT-licensed** and shares the same shape: `README` + `LICENSE` + `.env.example` + `Dockerfile` where it fits. All born from real production needs, then generalized.

> 📌 The six repos pinned above give the quickest tour of the work. The rest — grouped by area — below.

### 🧩 FastAPI microservices suite

> An interoperable set of services built around a shared pattern: app factory, `/health`, `/api/v1`, JWT via the identity hub, Gunicorn multi-stage images, admin dashboards. Use them together — or pick one.

| Repo | What it is |
|------|------------|
| 🪪 **[fastapi-identity-service](https://github.com/GDelpo/fastapi-identity-service)** | The hub — LDAP authentication + JWT issuance + admin dashboard. |
| ✉️ **[fastapi-email-service](https://github.com/GDelpo/fastapi-email-service)** | Transactional email with ARQ workers, Redis queue, pluggable providers. |
| ☁️ **[fastapi-gcs-manager](https://github.com/GDelpo/fastapi-gcs-manager)** | Google Cloud Storage file manager with upload / list / dashboard. |
| 📁 **[fastapi-google-drive-api](https://github.com/GDelpo/fastapi-google-drive-api)** | Google Drive operations exposed as a clean REST service. |
| 🎫 **[fastapi-helpdesk-tickets](https://github.com/GDelpo/fastapi-helpdesk-tickets)** | Full helpdesk — admin dashboard, employee portal, emails, SLA reminders. Ready to fork. |

### 🇦🇷 AFIP / ARCA integration ecosystem

> Four coordinated pieces to talk to Argentina's tax authority. Extensible by design — add new services by editing a YAML catalog.

| Repo | Role |
|------|------|
| 📦 **[afip-services](https://github.com/GDelpo/afip-services)** | Installable Python package — WSAA auth + SOAP clients, YAML catalog + handler registry. |
| 🔌 **[afip-services-api](https://github.com/GDelpo/afip-services-api)** | FastAPI REST wrapper with JWT + rate limiting + dashboard, consuming the package above. |
| 🧪 **[afip-services-applied](https://github.com/GDelpo/afip-services-applied)** | Reference consumer — JWT refresh, chunking, example workflows. |
| 📒 **[afip-iva-checker](https://github.com/GDelpo/afip-iva-checker)** | Audit IVA ledger files against AFIP records. CLI + Tkinter GUI. |

### 📄 Python utilities & tools

| Repo | What it does |
|------|--------------|
| 📝 **[docx-to-markdown](https://github.com/GDelpo/docx-to-markdown)** | Convert `.docx` to Markdown (images preserved) — FastAPI + HTMX webapp + CLI. |
| 📑 **[pdf-batch-renamer](https://github.com/GDelpo/pdf-batch-renamer)** | Tkinter wizard — rename PDFs in bulk from an Excel source. Includes a splitter. |
| 📋 **[copy-files](https://github.com/GDelpo/copy-files)** | Copy files listed in a `.txt` — GUI + scriptable backend. Zero dependencies. |
| 🗂️ **[directory-inventory-reporter](https://github.com/GDelpo/directory-inventory-reporter)** | Export an Excel inventory of a Windows directory, grouped by file owner (NTFS ACL). |
| 🔐 **[python-ldap-connector](https://github.com/GDelpo/python-ldap-connector)** | Reusable LDAP service — authenticate users, retrieve attributes. |
| 🔥 **[palo-alto-stats-collector](https://github.com/GDelpo/palo-alto-stats-collector)** | Collect firewall stats via Palo Alto XML API, export to Excel. |
| 🎓 **[moodle-usuarios-masivos](https://github.com/GDelpo/moodle-usuarios-masivos)** | Moodle-ready CSV for bulk user import, with validation + error reporting. |

### 🏗️ Full-stack apps & templates

| Repo | What it is |
|------|------------|
| 🏛️ **[django-ssn](https://github.com/GDelpo/django-ssn)** | Django 5 app for filings with Argentina's insurance regulator — scheduler, alerts, reports. |
| 📘 **[docusaurus-docs-template](https://github.com/GDelpo/docusaurus-docs-template)** | Docusaurus 3 scaffold with MDX components (Alert, Card, Steps, Tabs), optional CMS + auth sidecar. |

### 🔭 Infrastructure

| Repo | What it is |
|------|------------|
| 📊 **[observability-stack](https://github.com/GDelpo/observability-stack)** | Loki + Promtail + Grafana preconfigured for microservice log aggregation. |

### 🪄 Side projects

| Repo | What it is |
|------|------------|
| 💼 **[cv-online](https://github.com/GDelpo/cv-online)** | My interactive CV — React + Vite + Tailwind. |
| 🌳 **[link_tree](https://github.com/GDelpo/link_tree)** | Link-in-bio SPA with Instagram integration, deployed on Vercel. |

---

<div align="center">

### 📬 Get in touch

Based in **CABA, Argentina** · Open to **Technical Analyst / Python Developer** roles.

[![Email](https://img.shields.io/badge/guido__delponte@hotmail.com-D14836?logo=maildotru&logoColor=white&style=for-the-badge)](mailto:guido_delponte@hotmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=for-the-badge)](https://www.linkedin.com/in/guido-delponte-7a26033a4/)

<br>

<sub>If one of the projects above is useful to you, starring it makes my day. ⭐</sub>

<br><br>

<img src="https://komarev.com/ghpvc/?username=GDelpo&style=flat-square&color=0A66C2" alt="profile views" />

</div>
