<div align="center">

# Kaleksanan Barqi Aji Massani

**Software Architect · Quantitative Developer**

I build automated trading systems, quantitative analytics tools, and local-first desktop software.

[![GitHub](https://img.shields.io/badge/GitHub-KaleksananBarqi-181717?style=for-the-badge&logo=github)](https://github.com/KaleksananBarqi)
[![Rust](https://img.shields.io/badge/Rust-dea584?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Tauri](https://img.shields.io/badge/Tauri_v2-24C8D8?style=for-the-badge&logo=tauri&logoColor=white)](https://v2.tauri.app/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Binance](https://img.shields.io/badge/Binance_Futures-F0B90B?style=for-the-badge&logo=binance&logoColor=white)](https://binance.com)

</div>

---

## About

- Based in Indonesia
- Focus areas: algorithmic trading systems, quantitative analytics, local-first native desktop software, and data automation
- Currently developing **[trawangan](https://github.com/KaleksananBarqi/trawangan)** (a high-performance, zero-paywall crypto charting terminal) and **[nitirekso](https://github.com/KaleksananBarqi/nitirekso)** (an offline-first, multi-platform crypto trading journal)
- Dedicated to clean architecture, modular software design, and verifiable risk management

---

## Featured Projects

### Trading Systems & Analytics

| Project | Description |
|:--------|:------------|
| **[trawangan](https://github.com/KaleksananBarqi/trawangan)** ([Web](https://kaleksananbarqi.github.io/trawangan/)) | Professional desktop crypto charting terminal with zero paywalls. Native 60–120 FPS candlestick & orderflow rendering via WebGL2 engine, Pine Script v6 local execution in Web Worker, real-time multi-exchange WebSocket streaming (Binance, Bitunix, Hyperliquid, Coinbase), ultra-low memory footprint (~30–50 MB RAM), and 100% offline SQLite storage. Tauri v2, Rust, Svelte 5, LuxAlgo Vela, PineTS v6. |
| **[nitirekso](https://github.com/KaleksananBarqi/nitirekso)** ([Web](https://kaleksananbarqi.github.io/nitirekso/)) | Local-first, cross-platform crypto trading journal desktop app. Automated trade history sync via read-only APIs across 5 exchanges (Bybit, Binance, BingX, MEXC, Bitunix), execution quality grading (process vs. outcome), R-multiple distribution analytics, Alpha benchmarking against BTC Buy & Hold, AES-256 encrypted SQLite WAL storage, and social share card/video studio. Tauri v2, Rust, React 19, TailwindCSS v4, SQLite. |
| **[spot-prompt-cli](https://github.com/KaleksananBarqi/spot-prompt-cli)** | Quantitative Python CLI for systematic crypto spot DCA accumulation. Analyzes multi-timeframe technical metrics (RSI, ATR, VWAP, Bollinger Bands, POC 90d, Z-Score deviation) and generates a structured, clipboard-ready prompt for LLMs to determine dynamic limit order ladders vs. instant market buys. Python, Binance API, Rich, Pytest. |
| **[Crypto-BTC-Correlation-Beta-Filtering-System](https://github.com/KaleksananBarqi/Crypto-BTC-Correlation-Beta-Filtering-System)** | Quantitative multi-window rolling analysis pipeline classifying crypto assets by statistical correlation ($r$), beta ($\beta$), and $R^2$ relative to Bitcoin across multiple regimes (30d, 90d, 180d lookbacks). Features outlier handling (Winsorization, Huber robust regression), regime stability testing, and zero look-ahead bias validation. Python, Scipy, Statsmodels, CCXT. |
| **[Bot-Trading-Easy-Peasy-Full-AI](https://github.com/KaleksananBarqi/Bot-Trading-Easy-Peasy-Full-AI)** | Hybrid multi-AI crypto trading bot with a Triple AI Core (logic, vision, sentiment). AI sets entry, take-profit, and stop-loss with built-in validation. Python, Binance Futures. |
| **[Bot-Trading-Easy-Peasy-GUI](https://github.com/KaleksananBarqi/Bot-Trading-Easy-Peasy-GUI)** | Local FastAPI web dashboard for a Binance Futures bot: engine start/stop, live log streaming (SSE), position and PnL monitoring, config hot-reload, MongoDB trade journal. |
| **[Bot-Trading-Easy-Peasy](https://github.com/KaleksananBarqi/Bot-Trading-Easy-Peasy)** | Multi-strategy Binance Futures bot combining on-chain data, whale tracking, Fear & Greed, news sentiment, and technical analysis. `4 ★` |
| **[Bot-Trading-EMA-Cross-CCI](https://github.com/KaleksananBarqi/Bot-Trading-EMA-Cross-CCI)** | Focused Binance Futures bot using EMA 10/20 crossover with a CCI(20) momentum filter and a fixed 1:2 risk/reward. |

### Tools & Automation

| Project | Description |
|:--------|:------------|
| **[maos-nfc-rfid-android](https://github.com/KaleksananBarqi/maos-nfc-rfid-android)** | Native Android NFC app (Jetpack Compose, Kotlin, Room SQLite) for instant student RFID card reading and real-time 10-digit Little-Endian (`%010d`) decimal UID conversion matching USB hardware scanners for Pesantrenqu integration. Zero latency reader mode with auto-copy and persistent offline history. |
| **[smc-prompt-cli](https://github.com/KaleksananBarqi/smc-prompt-cli)** | Single-run Python CLI that pulls public Binance OHLC data, computes mechanical Smart Money Concepts facts (swings, structure, FVG), and renders a ready-to-paste LLM prompt. Zero paid APIs, clipboard-ready. |
| **[Ekspor-Komen-Tiktok](https://github.com/KaleksananBarqi/Ekspor-Komen-Tiktok)** | Chrome/Brave extension that exports TikTok comments and replies to CSV/Excel in one click, with auto-scroll and emoji-safe output. |
| **[Automasi-Analisis-Tren-Data-Santri](https://github.com/KaleksananBarqi/Automasi-Analisis-Tren-Data-Santri)** | Python tool that cleans and analyses student enrolment data from Excel and generates formatted reports (growth, top gainers/decliners, gender distribution). |
| **[BOT-RSS-Telegram](https://github.com/KaleksananBarqi/BOT-RSS-Telegram)** | RSS feed watcher that posts new articles to a Telegram chat. |
| **[Telegram-Bot-File-Sender](https://github.com/KaleksananBarqi/Telegram-Bot-File-Sender)** | Small utility for sending messages and files manually through a Telegram bot. |

---

## Tech Stack

| Category | Technologies |
|:--------:|:------------|
| **Languages** | ![Rust](https://img.shields.io/badge/Rust-dea584?style=flat-square&logo=rust&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) |
| **Desktop & Frameworks** | ![Tauri](https://img.shields.io/badge/Tauri_v2-24C8D8?style=flat-square&logo=tauri&logoColor=white) ![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=android&logoColor=white) ![Svelte](https://img.shields.io/badge/Svelte_5-FF3E00?style=flat-square&logo=svelte&logoColor=white) ![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi) ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) |
| **Charting & Graphics** | ![WebGL2](https://img.shields.io/badge/WebGL2-990000?style=flat-square&logo=webgl&logoColor=white) ![LuxAlgo](https://img.shields.io/badge/LuxAlgo_Vela-181717?style=flat-square) ![PineTS](https://img.shields.io/badge/PineTS_v6-2962FF?style=flat-square) |
| **Data & Storage** | ![SQLite](https://img.shields.io/badge/SQLite_WAL-07405E?style=flat-square&logo=sqlite&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=Streamlit&logoColor=white) |
| **AI & Automation** | ![OpenRouter](https://img.shields.io/badge/OpenRouter-000?style=flat-square) ![DeepSeek](https://img.shields.io/badge/DeepSeek-blueviolet?style=flat-square) ![Vision](https://img.shields.io/badge/Vision_Models-ff69b4?style=flat-square) |
| **Crypto & Exchanges** | ![Binance](https://img.shields.io/badge/Binance_API-F0B90B?style=flat-square&logo=binance&logoColor=white) ![Bybit](https://img.shields.io/badge/Bybit-F7A600?style=flat-square&logo=bybit&logoColor=black) ![CCXT](https://img.shields.io/badge/CCXT-informational?style=flat-square) |
| **Tools & CI/CD** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Telegram](https://img.shields.io/badge/Telegram_Bot-26A5E4?style=flat-square&logo=telegram&logoColor=white) |
| **Quantitative & Testing** | ![Scipy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white) ![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Backtesting](https://img.shields.io/badge/Backtesting-orange?style=flat-square) |

---

## GitHub Stats

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=KaleksananBarqi&theme=tokyonight" alt="GitHub Stats" height="170" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=KaleksananBarqi&theme=tokyonight" alt="Top Languages" height="170" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=KaleksananBarqi&theme=tokyonight&hide_border=true" alt="GitHub Streak" />

</div>

---

## Contact

Open to collaboration on trading systems, AI-assisted analysis, quantitative tooling, and data automation.
Reach out via [GitHub](https://github.com/KaleksananBarqi) or open an issue on any repository.

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=KaleksananBarqi&color=blueviolet&style=flat-square&label=Profile+Views)

</div>
