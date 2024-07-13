# Stock Analysis Project

## Overview

This project performs stock analysis on three prominent stocks: Tencent (TCEHY), Baidu (BIDU), and Alibaba (BABA). The analysis involves calculating moving averages and generating buy/sell signals based on the stock prices.

## Author

**Ryan Kahrimanian**  
Bachelor of Science in Finance with a concentration in FinTech  
Fordham University, Gabelli School of Business  
[LinkedIn](https://www.linkedin.com/in/ryankah96/)

```markdown
# Stock Data Analysis Project

## Overview
This project fetches stock data for specified tickers from Yahoo Finance, calculates a 2-day moving average, and visualizes the stock prices along with their volume. The script allows users to input multiple stock tickers and generates plots for each.

## Features
- Fetches historical stock data from Yahoo Finance.
- Calculates and plots the 2-day moving average.
- Plots stock prices and volume on a dual-axis chart.
- Handles multiple stock tickers input by the user.

## Requirements
- Python 3.x
- `pandas` library
- `matplotlib` library
- `yfinance` library
- `numpy` library
- `os` library (comes with Python standard library)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. Navigate to the project directory:
   ```sh
   cd your-repo-name
   ```
3. Install the required libraries:
   ```sh
   pip install pandas matplotlib yfinance numpy
   ```

## Usage
1. Run the script:
   ```sh
   python your_script_name.py
   ```
2. Input the stock tickers when prompted, separated by commas (e.g., `AAPL, MSFT, TSLA`).

## Code Explanation
### Imports
- `pandas` for data manipulation and analysis.
- `matplotlib.pyplot` for plotting graphs.
- `yfinance` for fetching stock data.
- `numpy` for handling arrays.
- `os` for handling file paths.

### Functions
- `yf_data(tickers)`: Fetches data for the provided stock tickers, calculates the 2-day moving average, and calls the `plot` function.
- `plot(date, price, volume, ma, stock_name)`: Plots the stock prices, 2-day moving average, and volume on a dual-axis chart.

### Main Script
- Prompts the user to input stock tickers.
- Processes each ticker to fetch data and generate plots.

## Example
```sh
What stock would you like to analyze? Please input the stock's ticker symbol. Please separate tickers with a ','.
AAPL, MSFT, TSLA
```

## Output
The script will generate and display plots for each stock ticker showing the stock prices, 2-day moving average, and volume.

```

Feel free to customize the `git clone` command and paths according to your repository and script names.
## Contact

For any questions or suggestions, feel free to reach out to me:

- **LinkedIn:** [Ryan Kahrimanian](https://www.linkedin.com/in/ryankah96/)
