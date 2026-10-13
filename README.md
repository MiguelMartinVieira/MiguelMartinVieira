# Miguel Martín Vieira

**Mathematical Engineering & AI — Comillas ICAI (Madrid)**

[LinkedIn](https://linkedin.com/in/miguel-mart%C3%ADn-vieira-77b35b28b) · [miguel.martin.vieira@gmail.com](mailto:miguel.martin.vieira@gmail.com) · [itacacademia.com](https://itacacademia.com)

---

## About

I'm finishing my degree in Mathematical Engineering and AI at ICAI. Most of my work sits at the intersection of applied math (optimization, dynamic programming, stochastic models) and building software that actually runs in production — not just notebooks.

A few things I've built and shipped:

- **[Academia Ítaca](https://itacacademia.com)** — Founded and run a tutoring marketplace (~€40k revenue) with zero admin staff. The whole operation (scheduling, billing, cancellations, teacher payouts) runs on a stack of Python services, LLM agents, and a Node.js messaging bridge. [See the platform repo →](https://github.com/MiguelMartinVieira/itaca-autonomous-platform)

- **Industrial IoT at El Encinar de Humienta** (€300M turnover meat processing) — The CEO pulled me in to lead an RFID telemetry project tracking 500+ cattle heads through cooling chambers and rail transport.

- **Financial ops for FSTA XLIII** — Managed €234k in cash and card settlements for a student festival funding 18 social projects. Built double-entry reconciliation controls that closed the books at exactly €0.00 discrepancy.

- 2nd place at **Campus 42 Madrid Hackathon** (Telefónica/Movistar). Completed Kumon Mathematics at 15 (multivariable calculus, ODEs, linear algebra — <1% completion rate).

---

## Tech I use regularly

**Math & AI:** optimization (LP, MILP, bitsets), PyTorch, LLM orchestration (Gemini model cascades), multimodal vision pipelines

**Systems:** Python (pandas, numpy, asyncio), Node.js microservices, PostgreSQL, SQLite, Apache Parquet, Streamlit

**Infra:** Docker Compose, Caddy (reverse proxy + auto-TLS), Linux, pytest, ruff, pre-commit

---

## Projects

### [itaca-autonomous-platform](https://github.com/MiguelMartinVieira/itaca-autonomous-platform)
The backend that runs Academia Ítaca end-to-end. Python async orchestrator + Node.js WhatsApp daemon + Gemini Flash NLP agent that reads parent messages ("Mateo can't make it today, he has a fever") and auto-cancels sessions. Circuit breakers, rate-limited Sheets client, cron-scheduled jobs on a VPS.

### [bokatas-ocr-accounting-pipeline](https://github.com/MiguelMartinVieira/bokatas-ocr-accounting-pipeline)
OCR pipeline for an NGO (Asociación Bokatas) that feeds the homeless in Madrid, Valencia, and Zaragoza. Takes photos of crumpled supermarket receipts, runs them through Gemini Vision, validates with Pydantic schemas, and classifies every line item into 9 budget categories. Saves volunteers ~200 hours/year of manual data entry.

### [bitset-subset-sum-balancer](https://github.com/MiguelMartinVieira/bitset-subset-sum-balancer)
Solver for the Subset Sum problem using bitset-parallel dynamic programming. Built it because I needed to split Bizum transactions across multiple bank accounts without exceeding monthly caps. Runs in $O(n \cdot W / 64)$ — sub-millisecond for real workloads. Full test suite with pytest.

### [oki-nami](https://github.com/MiguelMartinVieira/oki-nami)
Personal finance dashboard and double-entry accounting engine. Tracks real vs. nominal returns adjusted by Spanish CPI inflation data. Parquet for fast aggregations, Streamlit frontend, Docker Compose + Caddy for deployment.

### [universal-exercise-generator](https://github.com/MiguelMartinVieira/universal-exercise-generator)
Batch generator for STEM problem sets. Define a curriculum profile in YAML, point it at an LLM, and it produces validated LaTeX exercises with step-by-step solutions. Used at Ítaca to generate hundreds of worksheets from secondary school to university entrance level.

---

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MiguelMartinVieira&show_icons=true&theme=default&hide_border=true" height="150" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MiguelMartinVieira&layout=compact&theme=default&hide_border=true" height="150" alt="Top Languages" />
</div>
