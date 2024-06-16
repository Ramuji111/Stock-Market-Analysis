# Stock Market Analysis

Stock Market Analysis is a Streamlit web application that allows users to visualize stock performance comparisons, real-time stock prices, and stock price predictions using yFinance and Prophet libraries.

## Features

- Stocks Performance Comparison: Compare the performance of different stocks over a selected date range with various chart types (Line, Area, Bar).
- Real-Time Stock Price: View and analyze real-time stock prices with Line and Candlestick charts.
- Stock Prediction: Predict future stock prices using the Prophet forecasting model and visualize the predictions.

## Installation

Clone the repository:
git clone https://github.com/Ramuji111/Stock-Market-Analysis

cd StockMarket

Install the required dependencies:
pip install -r requirements.txt

## Usage

Run the Streamlit app:
streamlit run app.py

Navigate the app:
- Use the sidebar to select different utilities: Stocks Performance Comparison, Real-Time Stock Price, Stock Prediction, and About.
- For performance comparison and predictions, select the start and end dates.
- Choose the desired stocks from the dropdown menus.
- View the results in various chart formats and analyze the data.

## File Structure

- app.py: Main application script.
- StockStreamTickersData.csv: CSV file containing stock tickers and company names.
- requirements.txt: List of required Python libraries.

## Libraries Used

- Streamlit
- pandas
- yfinance
- datetime
- plotly
- prophet
- streamlit_option_menu
