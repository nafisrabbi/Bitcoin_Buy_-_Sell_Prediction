# Bitcoin Buy and Sell Prediction

This project aims to predict buy and sell signals for Bitcoin based on historical price data, technical indicators, and sentiment analysis.

## Project Structure

- **Data**: Contains datasets used for analysis.
- **Notebooks**: Jupyter notebooks with data analysis and model development.
- **Result**: Outputs and results from the analysis.

## Methodology

1. **Data Collection**: Historical Bitcoin price data is collected along with sentiment data from social media and news sources.
2. **Feature Engineering**: Technical indicators such as moving averages, RSI, MACD, and Bollinger Bands are calculated, along with sentiment scores from textual data.
3. **Model Development**: Machine learning models are developed to predict buy and sell signals based on these features.
4. **Evaluation**: Model performance is evaluated using accuracy, precision, recall, and F1-score to determine its predictive capabilities.

## Technical Indicators

- **Moving Averages (SMA, EMA)**: Simple Moving Average (SMA) and Exponential Moving Average (EMA) are used to smooth price data and identify trends over a specified period.
- **Relative Strength Index (RSI)**: An oscillator that measures the speed and change of price movements, used to identify overbought or oversold conditions.
- **Bollinger Bands**: Composed of a moving average and two bands that measure volatility, helping to identify whether prices are high or low.
- **MACD (Moving Average Convergence Divergence)**: A momentum oscillator that shows the relationship between two moving averages of the price, helping to detect changes in the strength, direction, momentum, and duration of a trend.

## Sentiment Analysis

Sentiment analysis is performed on social media posts, news articles, and other textual data related to Bitcoin. The sentiment (positive, negative, or neutral) is extracted using Natural Language Processing (NLP) techniques and incorporated into the predictive model.

