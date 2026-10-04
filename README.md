# Hi, I'm Chun Hei Man 👋

I build hands-on Python projects in **quantitative research, financial-data
automation and workflow engineering**. My current portfolio focuses on turning
market data and repetitive information-processing tasks into reproducible,
auditable systems.

## Featured Projects

### 1. [Futu Quant Research & Paper-Trading System](https://github.com/titusmanch/futu-quant-portfolio)

A reproducible signal-to-order workflow for US-equity research and Futu paper
trading. It separates strategy, backtesting, risk control, broker execution and
audit logging, and deliberately rejects real-money trading environments.

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

### 2. [Quantitative Market Intelligence Report](https://github.com/titusmanch/market-intelligence-pipeline-info)

An auditable pipeline that combines financial-news evidence with deterministic
technical indicators and produces structured daily market-intelligence reports
in HTML, JSON, CSV and SQLite formats.

**Highlights**

- Modular financial-data ingestion, cleaning and provenance tracking
- Deterministic SMA, RSI, MACD, ATR and Bollinger Band calculations
- Controlled ticker validation and strict Pydantic output schemas
- Optional LLM interpretation with validation and deterministic fallback
- Reproducible offline samples, automated tests and secure configuration

**Technologies:** Python, Pydantic, RSS/Atom, SQLite, HTML, pytest, GitHub Actions,
OpenRouter-compatible APIs

---

### 3. [Daily Job Intelligence Automation](https://github.com/titusmanch/job-crawler-info)

A scheduled Python pipeline that combines JobsDB email alerts with school-IT
vacancies from Ming Pao JUMP, filters and deduplicates results, and delivers a
structured daily WhatsApp report.

**Highlights**

- Gmail API integration using OAuth 2.0
- Multi-source extraction, parsing, filtering and deduplication
- Scheduled execution with GitHub Actions
- Secure GitHub Secrets management for external integrations
- Automatic Gmail labelling and inbox filing after successful processing

**Technologies:** Python, Gmail API, OAuth 2.0, GitHub Actions, BeautifulSoup,
Selenium, REST APIs

## Technical Toolkit

- **Quantitative research:** backtesting, benchmark comparison, performance and risk metrics
- **Programming and data:** Python, pandas, NumPy, Pydantic, JSON, CSV and SQLite
- **Automation:** GitHub Actions, scheduled pipelines, API integration and audit logging
- **Testing and controls:** pytest, deterministic workflows, validation and risk gates

## Current Focus

- Quantitative analysis and systematic strategy research
- Financial-data pipelines and market intelligence
- Reliable automation with transparent assumptions and reproducible outputs

