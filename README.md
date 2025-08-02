# WaveHunter.AI

🚨 A real-time anomaly detection system for identifying **stock manipulation (lái)** in the Vietnamese equity market.

## Features
- Detects abnormal trading patterns using ML (Isolation Forest, BiLSTM, etc.)
- Scrapes and analyzes news/social sentiment
- Telegram alerts with trading signals
- Interactive dashboard using Streamlit

## Folder Structure
```bash
wavehunter_ai/
├── data/               # Raw and processed financial data
├── models/             # AI models (anomaly detection, signal prediction)
├── notebooks/          # Exploratory notebooks
├── dashboard/          # Streamlit UI
├── bot/                # Telegram/Discord bot alerts
├── core/               # Core pipeline and utilities
