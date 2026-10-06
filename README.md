# Hi, I'm Chun Hei Man 👋

I build Python-based projects in **systematic trading, quantitative research and financial-data engineering**. My current portfolio focuses on reproducible backtesting, risk management, market-data pipelines and automated research workflows.

## Featured Projects

### 1. [Futu Quant Research & Paper-Trading System](https://github.com/titusmanch/futu-quant-portfolio)

A reproducible systematic-trading research and paper-trading workflow for US equities. It separates strategy research, backtesting, risk control, broker execution and audit logging, while deliberately restricting broker execution to the Futu `SIMULATE` environment.

**Highlights**

- Bias-aware backtesting with next-bar execution
- Configurable commission and adverse slippage
- CAGR, Sharpe, Calmar, maximum drawdown and benchmark comparison
- Position, buying-power, daily-loss, market-hours and kill-switch risk gates
- Restart-safe duplicate-order prevention and SQLite audit trail
- Futu OpenD integration restricted to `SIMULATE`

**Technologies:** Python, pandas, NumPy, matplotlib, SQLite, pytest, Futu OpenAPI

> Included demo results are illustrative and are not investment-performance claims.

---

### 2. [Financial Market Intelligence & Quantitative Signal Pipeline](https://github.com/titusmanch/market-intelligence-pipeline-info)

An auditable Python pipeline that combines financial-news evidence with deterministic technical indicators and produces structured daily market-intelligence reports in HTML, JSON, CSV and SQLite formats.

**Highlights**

- Modular financial-data ingestion, cleaning and provenance tracking
- Deterministic SMA, RSI, MACD, ATR and Bollinger Band calculations
- Controlled ticker validation and strict Pydantic output schemas
- Optional LLM interpretation with validation and deterministic fallback
- Reproducible offline samples, automated tests and secure configuration

**Technologies:** Python, Pydantic, RSS/Atom, SQLite, HTML, pytest, GitHub Actions, OpenRouter-compatible APIs

---

### 3. [Daily Job Intelligence Automation](https://github.com/titusmanch/job-crawler-info)

A scheduled Python pipeline that combines JobsDB email alerts with school-IT vacancies from Ming Pao JUMP, filters and deduplicates results, and delivers a structured daily WhatsApp report.

**Highlights**

- Gmail API integration using OAuth 2.0
- Multi-source extraction, parsing, filtering and deduplication
- Scheduled execution with GitHub Actions
- Secure GitHub Secrets management for external integrations
- Automatic Gmail labelling and inbox filing after successful processing

**Technologies:** Python, Gmail API, OAuth 2.0, GitHub Actions, BeautifulSoup, Selenium, REST APIs

## Technical Toolkit

- **Systematic trading & quantitative research:** backtesting, benchmark comparison, performance metrics, risk management and strategy evaluation
- **Programming & data:** Python, pandas, NumPy, Pydantic, JSON, CSV and SQLite
- **Financial data & APIs:** Futu OpenAPI, market-price data, RSS/Atom feeds and REST APIs
- **Automation:** GitHub Actions, scheduled pipelines, API integration and audit logging
- **Testing & controls:** pytest, deterministic workflows, validation and risk gates

## Current Focus

- Systematic trading and quantitative strategy research
- Reproducible backtesting and risk management
- Financial-data pipelines and market intelligence
- Reliable automation with transparent assumptions and reproducible outputs
