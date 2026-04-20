<h1 align="center">Hi, I'm Guido 👋</h1>
<p align="center">
  <a href="https://www.linkedin.com/in/guido-delponte-7a26033a4/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white"></a>
  <img alt="Location" src="https://img.shields.io/badge/Buenos%20Aires-Argentina-lightgrey">
  <img alt="Focus" src="https://img.shields.io/badge/focus-Python%20%7C%20FastAPI%20%7C%20Django-306998?logo=python&logoColor=white">
</p>

Python Developer & Technical Analyst. I build end-to-end solutions — from internal automation and backend services to full microservice suites with dashboards, background workers and observability. Most of what you see here started as real production work.

**Currently:** Python Developer & Systems Analyst at Example Corp (Dec. 2020 – present). Led the implementation of ExampleOnline, modernized legacy PHP stacks, designed a FastAPI microservices architecture from scratch, and structured the internal documentation site with Docusaurus. I also do independent consulting (Dec. 2018 – present): e-commerce, CMSs, data processing, system migrations.

## What I work with

- **Python** — FastAPI, Django, Flask, SQLAlchemy/SQLModel, Alembic, ARQ, Pydantic.
- **JavaScript** — React, Astro, HTMX, Tailwind, Vite.
- **Backends** — PostgreSQL, MySQL, Redis, SQL Server, Google Cloud Storage.
- **Infra** — Docker multi-stage builds, Traefik, Gunicorn, Loki + Promtail + Grafana.
- **Also** — PHP/Laravel, Java/Spring Boot, Docusaurus/MkDocs, Git, Jira, Postman.
- Systems Analyst (ORT Argentina), ongoing Software Development (ISTEA), AI certification (ITBA).

## Projects by area

Everything here is MIT-licensed and carries a consistent signature — README + LICENSE + `.env.example` + Dockerfile where it makes sense.

### 🧩 FastAPI microservices suite

An interoperable set of services following the same pattern (app factory, `/health`, `/api/v1`, JWT via identity, Gunicorn multi-stage, admin dashboard). They can be used independently or wired together.

| Repo | What it does |
|------|--------------|
| [**fastapi-identity-service**](https://github.com/GDelpo/fastapi-identity-service) | Identity + LDAP authentication, JWT issuance, admin dashboard. The hub of the suite. |
| [**fastapi-email-service**](https://github.com/GDelpo/fastapi-email-service) | Transactional email with ARQ workers + Redis, template engine, pluggable providers. |
| [**fastapi-gcs-manager**](https://github.com/GDelpo/fastapi-gcs-manager) | Google Cloud Storage file manager with upload / download / list + admin UI. |
| [**fastapi-google-drive-api**](https://github.com/GDelpo/fastapi-google-drive-api) | Google Drive operations exposed as a REST service. |
| [**fastapi-helpdesk-tickets**](https://github.com/GDelpo/fastapi-helpdesk-tickets) | Full helpdesk — admin dashboard + employee portal + emails + SLA reminders. Scaffold-ready. |

### 🇦🇷 AFIP / ARCA integration ecosystem

Four coordinated pieces for interacting with Argentina's tax authority (AFIP).

| Repo | Role |
|------|------|
| [**afip-services**](https://github.com/GDelpo/afip-services) | Installable Python package — WSAA authentication + SOAP clients for padrón/inscripción. |
| [**afip-services-api**](https://github.com/GDelpo/afip-services-api) | FastAPI REST wrapper over `afip-services` with JWT, rate limiting and dashboard. |
| [**afip-services-applied**](https://github.com/GDelpo/afip-services-applied) | Reference consumer that calls `afip-services-api` with chunking + JWT refresh. |
| [**afip-iva-checker**](https://github.com/GDelpo/afip-iva-checker) | Standalone app to audit IVA ledger files against AFIP records. CLI + Tkinter GUI. |

### 📄 Python utilities & tools

| Repo | What it does |
|------|--------------|
| [**docx-to-markdown**](https://github.com/GDelpo/docx-to-markdown) | Convert `.docx` to Markdown preserving images. Webapp (FastAPI + HTMX) + CLI. |
| [**pdf-batch-renamer**](https://github.com/GDelpo/pdf-batch-renamer) | Tkinter wizard to rename PDFs in bulk using Excel data. Includes a PDF splitter. |
| [**copy-files**](https://github.com/GDelpo/copy-files) | Copy files listed in a `.txt` with GUI + scriptable backend. Zero dependencies. |
| [**directory-inventory-reporter**](https://github.com/GDelpo/directory-inventory-reporter) | Scan a Windows directory and export an Excel report grouped by file owner (NTFS ACL). |
| [**python-ldap-connector**](https://github.com/GDelpo/python-ldap-connector) | Reusable LDAP user service class — authenticate users and retrieve attributes. |
| [**palo-alto-stats-collector**](https://github.com/GDelpo/palo-alto-stats-collector) | Collect stats from Palo Alto Networks firewalls via XML API, export to Excel. |
| [**moodle-usuarios-masivos**](https://github.com/GDelpo/moodle-usuarios-masivos) | Generate Moodle-ready CSV for bulk user import, with validation + error reporting. |

### 🏗️ Full-stack apps & templates

| Repo | What it does |
|------|--------------|
| [**django-ssn**](https://github.com/GDelpo/django-ssn) | Django 5 app for filing operations with Argentina's insurance regulator (SSN). Includes scheduler + alert system. |
| [**docusaurus-docs-template**](https://github.com/GDelpo/docusaurus-docs-template) | Docusaurus 3 scaffold with reusable MDX components (Alert, Card, Steps, Tabs), optional CMS + auth sidecar, and dark/light theme. |

### 🔭 Infrastructure

| Repo | What it does |
|------|--------------|
| [**observability-stack**](https://github.com/GDelpo/observability-stack) | Loki + Promtail + Grafana preconfigured for microservice log aggregation. |

### 🪄 Side projects

| Repo | What it does |
|------|--------------|
| [**cv-online**](https://github.com/GDelpo/cv-online) | My interactive CV in React + Vite + Tailwind. |
| [**link_tree**](https://github.com/GDelpo/link_tree) | Link-in-bio SPA with Instagram integration, deployed on Vercel. |

---

<sub>📬 Reach me at guido_delponte@hotmail.com · based in CABA, Argentina · open to technical analyst / Python developer roles in challenging environments.</sub>
