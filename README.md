# Ihago Nunes

### Software · AI · Data

Information Systems student at [ESPM](https://www.espm.br), building software and data-driven systems from **raw data to working products**.

I like the part where a vague problem becomes something you can actually run, measure, and improve.

[LinkedIn](https://www.linkedin.com/in/ihagonunes) · [GitHub](https://github.com/ihagonunes)

---

### Currently exploring

`AI Engineering` `Machine Learning` `Data Science` `Backend` `Data Systems`

Productionizing models, building reliable software around them, and exploring how AI can be applied to real operational problems.

---

## Selected work

### 01 — Predicting ride prices

**ML · Time Series · LightGBM · Optuna**

A forecasting pipeline for **UberX, Comfort and Black**, built around ~2.5 GB of raw data.

The interesting part wasn't just training the model. The pipeline handles chunked ingestion, profiling, feature engineering and strict temporal validation, keeping every ride in the same fold and preventing future information from leaking into training.

| Category     |  RMSE |  MAPE |   R² |
| ------------ | ----: | ----: | ---: |
| UberX        | 11.43 | 17.6% | 0.81 |
| Uber Black   | 10.34 | 12.1% | 0.93 |
| Uber Comfort |  7.42 |  8.7% | 0.96 |

`Python` `pandas` `scikit-learn` `LightGBM` `Optuna` `SHAP`

→ [Repository](https://github.com/ihagonunes/ml-price-prediction)

---

### 02 — Forecasting pharmaceutical inventory

**Forecasting · Optimization · Operations**

A hackathon project connecting demand forecasting with an actual replenishment decision.

Instead of stopping at a prediction, the project estimates censored demand, accounts for campaign effects, segments products using ABC classification and simulates a tuned **(s, S)** replenishment policy.

**Simulated vs. historical operation**

`99.85%` → service level
`R$143.71` → capital tied in stock / SKU / day
`113` → orders simulated

The repository also includes a chaos-oriented test suite for demand shocks, extreme lead times and unusual SKU histories.

`Python` `Forecasting` `Optimization` `pytest`

→ [Repository](https://github.com/ihagonunes/demand-forecasting-inventory-optimization) · [Presentation](https://www.canva.com/design/DAHKgqxWLmY/CVNnVVRHbfio3tMMeRxciA/edit)

---

### 03 — Building a learning platform

**Java · Spring Boot · Angular · PostgreSQL**

A full-stack EAD platform built around courses, subscriptions and gamification.

The backend is a layered **Spring Boot 3.3.5 / Java 17** application with Spring Security, JWT, OpenAPI and PostgreSQL. The frontend is an Angular 19 SPA.

It includes course progression, subscription plans, premium upgrades, coins and rewards.

`Java` `Spring Boot` `JWT` `Angular` `PostgreSQL` `Docker`

→ [Repository](https://github.com/ihagonunes/projeto-spring-edu-platform)

---

### 04 — TimeFlow

**Product · Next.js · Supabase · Analytics**

A different approach to productivity:

> **manage energy, not just time.**

TimeFlow lets users classify activities according to their effect on energy and explore the resulting timeline and analytics.

The project uses a two-dimensional energy model and a spec-driven workflow where acceptance criteria become executable Vitest tests.

`Next.js` `React` `TypeScript` `Tailwind` `Supabase` `Vitest`

→ [Repository](https://github.com/ihagonunes/timeflow)

---

### 05 — From sensors to decisions

**IoT · Backend · Data · Reporting**

An environmental monitoring platform connecting the entire pipeline:

```text
IoT Sensors
  ↓
Sensor data
  ↓
Python ingestion
  ↓
MySQL
  ↓
Node / Express
  ↓
Dashboards + Alerts
  ↓
PDF / Excel reports
```

The system monitors CO₂, VOCs, temperature, humidity and noise, then turns the data into dashboards, SLA-oriented alerts, occupancy views and compliance reports.

`IoT Sensor` `Python` `MySQL` `Node.js` `Express`

→ [Repository](https://github.com/ihagonunes/inter-3sem-2026-manalistas-panauaras)

---

### 06 — NFC-e → Excel

**A small product solving a very Brazilian problem.**

Paste a Brazilian electronic receipt URL.

Get a spreadsheet.

NFC-e Suite parses the public Sefaz page and generates workbooks for bill splitting, reimbursement workflows and price comparison across multiple markets.

No account. No upload. Just a link → useful output.

`Python` `Streamlit` `BeautifulSoup` `Excel`

→ [Repository](https://github.com/ihagonunes/mvp-nota) · [Live demo](https://nfc-esuite.streamlit.app/)

---

## How I build

I tend to care about the parts between the lines of code.

**Data should survive contact with reality.**

Temporal validation when time matters.
Invariant checks when systems have rules.
Chaos tests when edge cases are expensive.
Versioned reports when results need to be reproduced.

**Requirements should become something executable.**

Acceptance criteria → tests.
Architecture decisions → documented.
Specs → implementation constraints.

**A model isn't the product.**

A useful system usually looks more like:

```text
        messy problem
              ↓
        data / inputs
              ↓
       pipeline + logic
              ↓
       model / decision
              ↓
        software layer
              ↓
       useful outcome
```

That's the kind of engineering I enjoy.

---

## Stack

<p align="center">

<img src="https://skillicons.dev/icons?i=python,java,js,ts,c,cs,r,postgres,mysql,docker,git,github,spring,nodejs,nextjs,angular" />

</p>

**Data & ML**

`pandas` `NumPy` `scikit-learn` `LightGBM` `XGBoost` `Optuna` `SHAP` `time-series forecasting`

**Backend**

`Spring Boot` `Node.js` `Express` `Next.js` `REST APIs` `JWT` `PostgreSQL` `MySQL`

**Quality**

`pytest` `Vitest` `JUnit 5` `ArchUnit` `Testcontainers` `ESLint`

---

## What I'm working toward

I'm currently going deeper into three areas:

**AI Engineering**
Taking models beyond notebooks: inference, serialization, monitoring, performance and production systems.

**AI governance**
Building a multi-tenant SaaS for governing AI usage, with Spring Boot, PostgreSQL, Flyway, JWT/RBAC, ArchUnit and Testcontainers.

**AI-assisted engineering**
Exploring spec-driven workflows where AI can accelerate development without making the engineering process unverifiable.

---

## Education

**B.Sc. Information Systems**
ESPM · São Paulo, Brazil · 2025–2028

Coursework includes software engineering, algorithms, databases, statistics, data structures, OOP, backend development and machine learning.

---

<p align="center">

**Build useful things. Understand why they work. Keep improving them.**

<br>

<a href="https://www.linkedin.com/in/ihagonunes">LinkedIn</a>
  ·   <a href="https://github.com/ihagonunes">GitHub</a>

<br><br>

<sub>Living the present, building the future.</sub>

</p>
