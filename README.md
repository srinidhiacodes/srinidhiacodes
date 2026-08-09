<div align="center">

# Hi, I'm Srinidhi 👋

### QA Engineer — turning testing rigor into shipped confidence, from the UI down to the ML models underneath

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2E86AB&center=true&vCenter=true&width=600&lines=QA+Engineer+%7C+B2B+FinTech+SaaS;Playwright+%7C+API+%2B+UI+Automation;AI%2FLLM+%26+OCR+Model+Validation;Curious+by+default%2C+rigorous+by+habit)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/srinidhi-a-/)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:srinidhiaraja05@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/srinidhiacodes)

</div>

---

## About Me

I test a B2B FinTech SaaS product used by enterprise customers — the kind where a wrong number in a payment reconciliation isn't a cosmetic bug, it's someone's books being wrong. That context shaped how I test: I don't stop at "it failed," I want to know exactly which stage of the pipeline it failed at.

My title went from Data Analyst to QA Engineer, but the analytical habits came with me — SQL-first debugging, tracing a bad output back through logs and queues instead of guessing. I'm curious by default, which is usually why I end up owning things nobody assigned me: the ERP stress-test framework below started as me poking at a slow manual process during a perf-testing task, not as a ticket.

Lately that curiosity has pointed at AI features — validating what an LLM/OCR model actually got right by computing the correct answer myself first, not by eyeballing whether the output looks plausible.

---

## Impact at a Glance

| | |
|---|---|
| 🐛 **300+ defects found** | many of them buried in RabbitMQ/Celery queues and background jobs, not visible from the UI |
| ⚡ **~1 day → <40 min** | rebuilt how test data gets set up for stress testing, wiring internal APIs straight into a third-party ERP |
| 🤖 **~90% less manual analysis** | on an AI/LLM testing framework covering prediction, recommendation, OCR-extraction, rule-engine & LLM workflows |
| 🔄 **~2 days → <1 min** | an ETL pipeline I built from scratch (Spring Boot + RabbitMQ) to replace a manual analysis workflow |
| 📊 **Anomaly detection + Slack alerts** | plus a self-serve API and auto-emailed CSV reports so Customer Success didn't have to ask me for numbers |
| 📈 **~2,000 data points/customer/day** | funnel & cohort analysis across a multi-stage ML pipeline, pinned down to the exact stage that broke |

---

## What I Work On

- **Test automation** — Playwright (UI + API modules), Postman/Swagger-driven API testing
- **Distributed systems testing** — async workflows through RabbitMQ/Celery, race conditions, eventual-consistency bugs
- **AI/LLM & OCR validation** — prompt evaluation, grading output against independently computed expected results instead of string-matching
- **Data-informed QA** — SQL-first debugging, tracing failures to the exact stage of a multi-tier pipeline

---

## 🧰 Tech Stack

**Languages & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

**Automation & Testing**

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

**Backend & Messaging**

![REST APIs](https://img.shields.io/badge/REST%20APIs-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Monitoring & Collaboration**

![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Agile](https://img.shields.io/badge/Agile%2FScrum-1E90FF?style=for-the-badge&logo=scrumalliance&logoColor=white)

---

## 🤖 AI-Augmented QA

QA doesn't stop at the application anymore — it extends to the models running inside it. I use AI both as something I test and as something I test *with*: prompt engineering & evaluation, OCR/LLM model validation, synthetic test data generation, agentic workflows — day to day with OpenAI, Gemini, Claude, Cursor, and GitHub Copilot.

| Capability | What it looks like in practice |
|---|---|
| **LLM/OCR output validation** | Compute the correct answer independently first, then grade the model's output against it — not exact-string-match |
| **Prompt-driven test case generation** | Feed an LLM (Claude Code) the PRD, my own notes, and team context; it drafts test cases from the actual codebase, asks when something's ambiguous, I review every one before trusting it |
| **Multi-tier pipeline debugging** | Trace a wrong prediction back to the exact stage — extraction, rule engine, or model — that actually caused it |
| **AI-assisted engineering** | Claude Code / GitHub Copilot are part of my daily workflow, not a replacement for reviewing my own output |

---

## 💼 Experience

**QA Engineer** · Nov 2025 – Jul 2026
Own QA end to end for a B2B FinTech SaaS product — UI, APIs, backend services, ML workflows, and the distributed/async systems underneath. Built the ERP stress-test data framework and the AI/LLM testing framework featured below, extended regression automation into Playwright API tests, and carry release quality — QA sign-off, defect lifecycle, regression coordination — through every ship.

**Founding Data Analyst** *(Product AI Analytics & Quality Engineering)* · Jun 2024 – Oct 2025
Started as the first data analyst on a product-analytics-meets-QA function, and ended up doing both. Built an ETL pipeline from scratch, an anomaly-detection + Slack-alerting system for customer health, and ran the A/B testing that compared in-house models against rule engines and third-party OCR — while already testing and validating releases before that became my official title.

---

## 🚀 Featured Projects

### 🤖 [AI/LLM Testing Framework](https://github.com/srinidhiacodes/ai-testing-portfolio)
A from-scratch, IP-clean recreation of a real validation pattern: independently computing the correct answer to a prediction problem, then grading a system's output against it — including crediting a *different but still-valid* answer instead of false-flagging it as a bug.

`Python` `pytest` `Test Data Generation` `Independent Ground-Truth Validation`

### 🎭 [Playwright + TypeScript Automation Framework](https://github.com/srinidhiacodes/playwright-portfolio)
POM-structured UI automation and an API testing module, both exercising the same real target application end-to-end.

`Playwright` `TypeScript` `POM` `API Testing`

### 🐍 Python API Automation (pytest + requests)
Standalone backend/API test suite against a public REST API — Python-specific coverage independent of the TypeScript framework.

`Python` `pytest` `requests` — *in progress*

---

## 🏢 Production Contributions

The projects above are personal, IP-clean rebuilds for this portfolio — the real versions live inside my company's proprietary codebase, so no repo link here, just what shipped:

- **Playwright automation framework** — expanded regression coverage by adding an API testing module alongside the existing UI test suite, across the production application stack
- **ERP stress-test data framework** — internal APIs wired into a third-party ERP, cut test-data prep from ~1 day to under 40 minutes
- **AI/LLM testing framework** — generates test data/cases across Product-defined prompt combinations, validates outputs across prediction, recommendation, OCR-extraction, rule-engine & LLM workflows, ~90% less manual analysis effort

---

<div align="center">

### Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/srinidhi-a-/)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:srinidhiaraja05@gmail.com)

*Open to QA/SDET roles — automation architecture, AI/ML testing, and everything in between.*

</div>
