# WaveHunter.AI

WaveHunter.AI is a real-time anomaly detection framework for identifying **stock manipulation (lái)** in the Vietnamese equity market. The project combines market data analysis, news and sentiment scraping, and machine learning models to surface abnormal trading patterns and deliver actionable alerts.

## Features

- Detects abnormal trading patterns using ML algorithms like Isolation Forest and BiLSTM
- Scrapes and analyzes news and social sentiment
- Sends Telegram/Discord alerts with trading signals
- Interactive dashboard built with Streamlit

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/wavehunter-ai.git
   cd wavehunter-ai
   ```

2. **Create a virtual environment and install dependencies**

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   ```

## Usage

Run the core pipeline or launch the dashboard:

```bash
# Run anomaly detection on the default dataset
python core/main.py

# Start the Streamlit dashboard
streamlit run dashboard/app.py
```

## Directory Structure

```bash
wavehunter_ai/
├── bot/                # Telegram/Discord bot alerts
├── core/               # Core pipeline and utilities
├── dashboard/          # Streamlit UI
├── data/               # Raw and processed financial data
├── models/             # Machine learning models and training code
├── notebooks/          # Exploratory analysis notebooks
```

## Contributing

Contributions are welcome!

1. Fork the repository and create your branch: `git checkout -b feature/my-feature`
2. Make your changes and ensure all tests pass: `pytest`
3. Commit your changes and open a pull request with a clear description

Please follow the existing code style and include tests when adding new features.

## License

Distributed under the MIT License. See `LICENSE` for more information.

