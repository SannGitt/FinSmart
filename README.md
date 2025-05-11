# FinSmart

**FinSmart** is a web-based financial analytics platform designed to provide users with comprehensive tools for stock prediction, sentiment analysis, and AI-powered investment advice. Built using **Streamlit**, the app leverages machine learning, natural language processing (NLP), and finance APIs to empower users with actionable insights for informed investment decisions.

## Features

### 1. **Stock Prediction**

- Users can input the name of a company and predict its future stock price based on historical data.
- Utilizes **LSTM** (Long Short-Term Memory) models for stock price forecasting.
- Includes technical indicators like **RSI**, **SMA**, and **Volatility**.

### 2. **Sentiment Analysis**

- Analyzes social media and news sentiment to gauge the public perception of a company’s stock.
- Helps users understand how the market feels about a company to inform investment strategies.

### 3. **My Advisor (AI-powered Investment Advice)**

- Provides personalized AI-driven investment advice based on the user’s financial goals.
- Leverages machine learning models trained on market data to recommend stocks and investment strategies.

---

## Installation

To run this project locally, follow these steps:

### Prerequisites

- Python 3.7+
- Streamlit
- Required Python Libraries: `requests`, `yfinance`, `pandas`, `numpy`, `scikit-learn`, `tensorflow`, `matplotlib`

### Steps

1. Clone this repository to your local machine:
   git clone https://github.com/SannGitt/FinSmart.git
   
   cd FinSmart
3. Install the required dependencies:
   pip install -r requirements.txt

   Set up your API keys for the relevant services. Replace the placeholders with actual API keys in the corresponding files:
   Alpha Vantage API Key
   Reddit API Key
   Other necessary keys for sentiment analysis and financial data fetching.

4. Run the Streamlit app:
   
   streamlit run main.py
   
   Open your browser and go to http://localhost:8501 to see the app in action!

## Usage

Once the app is running, you can:

- Input a company name for stock prediction.
- View the stock’s historical data and the predicted future prices.
- Get investment advice from the AI-powered advisor.
- Analyze market sentiment around a company by navigating to the Sentiment Analysis section.
