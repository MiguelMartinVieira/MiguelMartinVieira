<div align="center">

# Miguel Martín Vieira

### **Mathematical Engineering & Artificial Intelligence (ICAI)**
*Mathematical Optimization • AI Systems in Production • Quantitative & Financial Engineering*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Miguel%20Mart%C3%ADn%20Vieira-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/miguel-mart%C3%ADn-vieira-77b35b28b)
[![Portfolio](https://img.shields.io/badge/Website-itacacademia.com-10B981?style=for-the-badge&logo=firefox-browser&logoColor=white)](https://itacacademia.com)
[![Email](https://img.shields.io/badge/Email-miguel.martin.vieira%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:miguel.martin.vieira@gmail.com)
[![Location](https://img.shields.io/badge/Location-Madrid%2C%20Spain-6B7280?style=for-the-badge&logo=google-maps&logoColor=white)](https://maps.google.com/?q=Madrid)

<br/>

> *"Bridging rigorous continuous & discrete mathematics with robust, containerized production systems and real-world operational scale."*

</div>

---

## 🧭 Executive Summary

Undergraduate in **Mathematical Engineering and Artificial Intelligence** at **Comillas-ICAI**, combining high-level analytical modeling (convex/non-convex optimization, dynamic programming, game theory, stochastic processes) with production-grade software architecture.

- 🚀 **Founder & Systems Engineer at Academia Ítaca**: Scaled an education marketplace approaching **€40k in revenue** with **100% autonomous operations** and zero administrative overhead, powered by model-cascade LLM agents, bitset combinatorial optimization, and automated accounting workflows.
- 🏭 **Industrial Optimization at El Encinar de Humienta (€300M turnover)**: Promoted by the CEO to lead an industrial IoT & RFID telemetry initiative tracking 500+ cattle heads daily across industrial cooling chambers and rail transport lines.
- 💰 **Financial Operations Leadership**: Managed **€234k in cash and POS settlements** at FSTA XLIII (18 social initiatives funded), engineering redundant double-entry controls that cut historical accounting discrepancies to exactly **€0.00**.
- 🏆 **Track Record**: 2nd Place at **Campus 42 Madrid Hackathon** (Fundación Telefónica / Movistar) and **Kumon Mathematics Completer** at age 15 (<1% completion rate: multivariable calculus, differential equations, and linear algebra).

---

## 🛠️ Technical Stack & Tooling

```
┌──────────────────────────────┬──────────────────────────────┬──────────────────────────────┐
│  APPLIED MATH & AI           │  SYSTEMS & DATA ARCHITECTURE │  SOFTWARE & DEVOPS           │
├──────────────────────────────┼──────────────────────────────┼──────────────────────────────┤
│ • Mathematical Optimization  │ • Python (Pandas, NumPy)     │ • Docker & Docker Compose    │
│   (LP, MILP, NLP, Bitsets)   │ • Apache Parquet Storage     │ • Caddy Reverse Proxy (HTTPS)│
│ • Machine Learning & PyTorch │ • PostgreSQL / SQLite        │ • CI/CD & GitHub Actions     │
│ • LLM Multi-Agent Cascades   │ • Streamlit & Plotly Dash    │ • Testing (pytest, coverage) │
│ • Multimodal Computer Vision │ • Asyncio / Microservices    │ • Ruff, Black, pre-commit    │
│ • NVIDIA DGX H200 Clusters   │ • Financial Double-Entry     │ • Linux / POSIX Shell        │
└──────────────────────────────┴──────────────────────────────┴──────────────────────────────┘
```

---

## 🌟 Featured Engineering Projects

### 1. [Itaca Autonomous Platform — Multi-Agent Operations & Microservices Engine](https://github.com/MiguelMartinVieira/itaca-autonomous-platform)
> **Stack**: `Python 3.12` • `Node.js microservices` • `Google Gemini 1.5 Flash` • `Asyncio` • `Google Sheets API` • `Circuit Breakers`

The complete autonomous backend and agent orchestration engine powering **Academia Ítaca** (€40k revenue, 100% automated operations).
- **Multi-Agent Orchestration**: NLP agent cascade analyzing unstructured multi-turn student messages to autonomously detect session cancellations, extract ISO timestamps, and execute calendar/database transactions.
- **Resilient Distributed Architecture**: Node.js WhatsApp session bridge communicating over authenticated HTTP endpoints with Python `asyncio` consumers; includes exponential backoff, circuit breaker policies, and rate-limited Google Cloud Sheets persistence.
- **Zero-Touch Business**: Automated billing notifications, teacher payout splits, and multi-session scheduling with zero administrative staff.

---

### 2. [Bokatas — Nationwide Intelligent OCR & Invoice Reconciliation Pipeline](https://github.com/MiguelMartinVieira/bokatas-ocr-accounting-pipeline)
> **Stack**: `Python 3.12` • `Google Gemini Vision API` • `Pydantic v2` • `Pandas` • `OpenPyXL` • `Google Drive API`

An automated accounting ingestion pipeline built for **Asociación Bokatas (NGO)** across Madrid, Valencia, and Zaragoza.
- **Multimodal OCR**: Ingests hundreds of heterogeneous, wrinkled receipts, thermal paper prints, and iOS HEIC files via Gemini Vision models.
- **Automated Bookkeeping**: Classifies itemized lines into the NGO's **9 official budgetary categories** with 0% human transcription error via strict Pydantic schemas.
- **Operational Impact**: Eliminates **200+ hours of manual administrative labor annually** and outputs audit-proof multi-sheet Excel workbooks and immutable general ledgers.

---

### 3. [Dynamic Programming Bitset Engine — Combinatorial Subset Sum](https://github.com/MiguelMartinVieira/bitset-subset-sum-balancer)
> **Stack**: `Python 3.12` • `Bitwise DP Parallelism` • `Discrete Optimization` • `Algorithms` • `pytest`

A high-performance algorithmic solver for the **NP-complete Subset Sum problem** accelerated via **bitwise 64-bit parallel shifts**.
- **The Problem**: Dynamically partition daily client transactions across multiple bank accounts to satisfy strict statutory monthly transaction limits (Bizum banking caps).
- **The Solution**: Implemented a bitset-accelerated dynamic programming approach reducing state-space search latency by orders of magnitude ($\mathcal{O}(n \cdot W / 64)$), executing in sub-milliseconds.

---

### 4. [Oki-Nami — Quantitative Wealth Analytics & Double-Entry Accounting](https://github.com/MiguelMartinVieira/oki-nami)
> **Stack**: `Python 3.12` • `Streamlit` • `Plotly` • `Docker Compose` • `Caddy (Auto TLS)` • `Apache Parquet` • `Gemini Vision` • `pytest`

An end-to-end containerized personal finance and quantitative asset allocation engine.
- **Mathematical Modeling**: Real-time portfolio valuation indexing against Spanish **INE CPI inflation** data to calculate real vs. nominal purchasing power and drawdown trajectories.
- **Double-Entry Engine**: Strict accounting invariants ($\Delta\text{Assets} = \Delta\text{Liabilities} + \Delta\text{Equity}$) generating real-time balance sheets, income statements, and cash flow forecasts.
- **High-Performance Persistence**: Columnar storage in **Apache Parquet** for sub-millisecond analytical aggregations paired with Google Sheets cloud synchronization.
- **Containerized Stack**: Packaged via Docker Compose and fronted by Caddy for automated TLS certificates.

---

### 5. [Universal Exercise Generator — Autonomous AI Curriculum Engine](https://github.com/MiguelMartinVieira/universal-exercise-generator)
> **Stack**: `Python` • `LLM Orchestration` • `YAML Config Engines` • `Automated LaTeX / PDF Rendering`

An autonomous batch-generation factory producing publication-grade academic STEM problem sets.
- Driven by declarative YAML curriculum profiles spanning secondary to elite university entrance exams (ICADE, CEU).
- Includes structural validation, LaTeX syntax sanitization, and automated PDF compilation workflows.

---

## 📈 Engineering Activity & Highlights

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MiguelMartinVieira&show_icons=true&theme=tokyonight&hide_border=true&title_color=38bdf8&icon_color=38bdf8" height="150" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MiguelMartinVieira&layout=compact&theme=tokyonight&hide_border=true&title_color=38bdf8" height="150" alt="Top Languages" />
</div>

---

<div align="center">
  <sub>Designed & engineered with precision by Miguel Martín Vieira • Madrid, Spain</sub>
</div>
