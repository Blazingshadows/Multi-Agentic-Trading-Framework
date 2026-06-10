# AthenaTrade: Multi-Agent Hybrid AI Trading System

## Overview

AthenaTrade is a research-focused trading platform that combines:

- Quantitative trading infrastructure
- Machine Learning (LSTM-based forecasting)
- Reinforcement Learning (decision making)
- Multi-agent architecture
- Risk-aware execution
- Live paper trading deployment

The project is designed as an engineering-first system where infrastructure and evaluation are built before introducing intelligence and autonomy.

---

## Vision

Build a trading system that evolves through three layers:

### Layer 1: Infrastructure
Reliable data pipelines, backtesting, execution simulation, and evaluation.

### Layer 2: Intelligence
Machine learning and reinforcement learning models capable of generating and validating trading decisions.

### Layer 3: Agency
Specialized agents coordinating research, validation, risk management, and execution.

---

## Final Architecture

Market Data
↓
Researcher Layer (ML/LSTM Signals)
↓
Validator Layer (RL + Strategy Selection)
↓
Risk Manager
↓
Execution Agent
↓
Monitoring & Logging

---

## Core Components

### Researcher Agent
Responsible for:
- Market scanning
- Candidate selection
- Signal generation
- Forecasting

Potential models:
- LSTM
- GRU
- Transformers
- Ensemble models

### Validator Agent
Responsible for:
- Opportunity validation
- Strategy selection
- Confidence scoring

Potential models:
- PPO
- DQN
- Rule-based filters

### Risk Manager
Responsible for:
- Position sizing
- Exposure control
- Stop losses
- Drawdown limits

### Execution Agent
Responsible for:
- Exchange interaction
- Order placement
- API communication
- Audit logging

---

## Development Philosophy

Build in stages:

1. Infrastructure First
2. Baseline Strategies
3. ML Integration
4. RL Integration
5. Agentic Layer
6. Deployment
7. Research & Optimization

Complexity must always be justified by measurable improvements.

---

## Success Metrics

Performance:
- Sharpe Ratio
- Profit Factor
- Max Drawdown
- Win Rate

Engineering:
- Reliability
- Reproducibility
- Modularity
- Observability

---

## Technology Stack

### Data
- Pandas
- NumPy

### Machine Learning
- PyTorch

### Reinforcement Learning
- Stable-Baselines3
- Gymnasium

### Storage
- SQLite
- PostgreSQL

### Deployment
- Docker
- Ubuntu
- Cloud VM

### Monitoring
- Logging
- Telegram Alerts
- Dashboards

---

## Project Status

Current Phase:
Phase 1 — Infrastructure & Backtesting Foundation
