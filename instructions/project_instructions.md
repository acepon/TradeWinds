# Project Overview

**Objective**  
Develop a self-hosted trading intelligence platform for analyzing global stock markets (NASDAQ & China A-shares), backtesting custom strategies, and automating trade alerts. The system prioritizes scalability from personal use to institutional-grade analysis.

**Key Attributes**  
- 🧩 Modular architecture with clear domain boundaries  
- 📊 Real-time data visualization & historical benchmarking  
- 🔔 Multi-channel notification system (WeChat first)  
- 🚀 Local/cloud deployment flexibility  

# Core Functionalities  

## 1. Market Data integtation
- **Sources**  
  - NASDAQ-listed equities (real-time + historical)  
  - China A-shares (Shanghai/Shenzhen exchanges)  
- **Features**  
  - Batch/streaming ingestion modes  
  - Persistent storage for historical data to avoid unnecessary queries  

## 2. Stock Selection & Analysis
- **Features**
  - Enabel to setup custom stock selection pipeline
  - The analysis can be powered by ai or ai agent for in-depth analysis

## 3. Strategy Development Framework  
- **Backtesting Engine**
  - Historical simulation with custom timeframes
| Component          | Capabilities                                  |  
|--------------------|-----------------------------------------------|  
| Backtesting Engine | Historical simulation with custom timeframes |  
| Strategy Library   | Pre-built templates (RSI, MACD) + custom code |  
| Metrics Dashboard  | Sharpe ratio, max drawdown, win rate analysis |  

## 4. Signal Generation & Notification  
- **Workflow**  
  1. Continuous market condition monitoring  
  2. User-defined trigger thresholds  
  3. Alert delivery via WeChat (extensible to SMS/Email)  

## 5. User Interface  
- **Key Modules**  
  - Interactive charting with technical indicators  
  - Strategy configuration wizard  
  - Backtest performance dashboard  
  - Alert history & management console  

# Technical Foundation
  - use next.js and shacn for frontend development
  - use poetry for backend dependency management and fastapi for the API

**Architecture Principles**  
- 🛡️ API-first design with versioned endpoints  
- 🔄 Async processing for compute-heavy tasks  
- 📦 Scaleable and modular architecture to decouple different functionalities  
- 🔍 Local first principle for MVP to enable easy test and deploy locally

# Doc

# Important implementation notes
