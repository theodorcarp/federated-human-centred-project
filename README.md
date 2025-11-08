# The Federated, Human-Centred Project: Engineering Trust Across Societies (v1.0)

**Author:** Theodor-Nicolae Carp | **Year:** 2025 | **Assisted by:** OpenAI GPT-5

## Overview
[Keep your existing intro from before, e.g., trust erosion, four layers...]

**Mission**: "Ethical interoperability as standard for democratic systems." – T.N. Carp, 2025

## Layers & Outputs
| Layer | Key Artefact | Description |
|-------|--------------|-------------|
| **Theoretical/Infrastructural** | [01_Doctoral_Synthesis.md](01_Doctoral_Synthesis.md) | Full synthesis (from upload); Cyber Entente foundation. |
| **Governance** | [04_Federated_Trust_Protocol_v1.0.md](04_Federated_Trust_Protocol_v1.0.md) | API specs + compliance pack (Model Card, DPIA, MOU). |
| **Applied Civic** | [Morning Star Core](https://github.com/YOUR_USERNAME/morning-star-core) | Backend: FastAPI + Federated Trust APIs (`app/main.py`). |
| **Applied Civic** | [Morning Star Frontend](https://github.com/YOUR_USERNAME/morning-star-frontend) | React UI: Video feed, tuner, FTS dashboard (`package.json`, `src/App.js`). |
| **Applied Civic** | [Morning Star Infra](https://github.com/YOUR_USERNAME/morning-star-infra) | DevOps: Docker Compose, HTTPS, Grafana (`docker-compose.prod.yml`). |
| **Socio-Philosophical** | [06_New_Marshall_Plan_Summary.md](06_New_Marshall_Plan_Summary.md) | Humane governance extensions. |

## Quick Start (Full Stack)
1. Clone umbrella: `git clone --recurse-submodules https://github.com/YOUR_USERNAME/federated-human-centred-project.git` (once local Git ready).
2. Deploy infra: In `morning-star-infra` → `docker compose -f docker-compose.prod.yml up -d`.
3. Backend: `http://localhost:8001/docs` (test `/trust/score`).
4. Frontend: In `morning-star-frontend` → `npm start` → `localhost:3000` (polls FTS).
5. Metrics: Grafana `localhost:3000` (import `grafana_dashboard_federated_trust.json`).

## Hardening Status
Follow [10_Hardening_Plan.md](10_Hardening_Plan.md) for NIST/ISO upgrades (Phase 1: mTLS in infra).

License: MIT. Cite: [CITATION.cff](CITATION.cff). Questions? @CarpTheodor on X.
