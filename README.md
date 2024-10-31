# Stock Portfolio Manager

## Project Overview
The **Stock Portfolio Manager** is a PyQt5-based application for monitoring real-time stock prices in your portfolio. It fetches live data from the Alpha Vantage API, displaying each stock's current price and percentage change.

## Setup Instructions

### Clone the Repository
Clone the repository and navigate into the project directory:
git clone https://github.com/Dadudekc/stock_portfolio_manager.git  
cd stock_portfolio_manager  

### Install Dependencies
Install the required dependencies:
pip install -r requirements.txt  

### Configure Environment Variables
Create a `.env` file in the project root and add your Alpha Vantage API key:
ALPHA_VANTAGE_API_KEY=your_api_key_here  

### Run the Application
Launch the Stock Portfolio Manager application:
python stock_portfolio_manager.py  

### Run Tests
Execute the test suite to ensure everything functions as expected:
python test_stock_portfolio_manager.py  

## Potential Improvements

1. **Detailed Stock Information Panel**: Add a sidebar or pop-up panel for selected stocks, displaying daily highs, lows, historical data, or company profiles.
2. **Graphical Data Visualization**: Integrate basic trend charts for stock performance using libraries like `matplotlib`.
3. **Price Alerts and Notifications**: Allow users to set price alerts for stocks, with notifications when a stock reaches the set price.
4. **Portfolio Tracking with Total Value Calculation**: Add fields for share quantities, calculate individual and total portfolio value, and update in real-time.
5. **Historical Data Integration**: Integrate historical data for each stock, displaying past trends for analysis.
6. **Authentication and User Profiles**: Add login features for saving watchlists, preferences, and alert settings.
7. **Expanded Watchlist and Sorting Features**: Enable customized sorting of watchlists (by price, daily change, etc.).
8. **Multiple Data Sources**: Integrate fallback data sources like Yahoo Finance or IEX Cloud for reliability.
9. **Offline Mode with Cached Data**: Cache last successful fetch, allowing data display even offline.
10. **Automated Daily Reports**: Send daily summaries of stock performance and portfolio updates via PDF or email.
11. **News Feed Integration for Each Stock**: Display relevant news articles for each stock via a news API.
12. **Sentiment Analysis on News Headlines**: Apply sentiment analysis on stock-related headlines, showing a sentiment score.

## Contributing
If you’d like to contribute, please open an issue or submit a pull request with your enhancements or bug fixes.

## License
This project is licensed under the MIT License.
