# Portfolio_Tracker
A beginner-friendly Python tool to track and analyze an investment portfolio. Includes current market value tracking, return calculations, and comparison against the S&amp;P 500 benchmark. 
Built using pandas, yfinance, and simple visualization libraries. Sample holdings file included.

## Features
- Load portfolio from a CSV file
- Fetch current prices using Yahoo Finance
- Calculate unrealized gains and portfolio weights
- Benchmark vs. S&P 500 (cumulative returns)
- Simple pie and line charts for visualization

## Sample Use Case
The notebook includes example data in `holdings.csv`, so you can run it without setting up anything complex.

## How to Run
1. Clone the repo or download the `.ipynb` file.
2. Install required libraries:
    ```bash
    pip install pandas yfinance matplotlib plotly
    ```
3. Open `portfolio_tracker.ipynb` in Jupyter or VS Code.
4. Upload your own CSV file or use the sample to test.

## File Format
Here's what the `holdings.csv` file should look like:

```csv
Ticker,Shares,Purchase Date,Purchase Price
AAPL,10,2022-01-15,150
MSFT,5,2022-02-10,280
GOOGL,8,2022-03-05,2500
TSLA,3,2022-04-12,700
AMZN,2,2022-05-01,3300
