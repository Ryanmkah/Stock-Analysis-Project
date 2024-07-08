# Stock Analysis Project

## Overview

This project performs stock analysis on three prominent stocks: Tencent (TCEHY), Baidu (BIDU), and Alibaba (BABA). The analysis involves calculating moving averages and generating buy/sell signals based on the stock prices.

## Author

**Ryan Kahrimanian**  
Bachelor of Science in Finance with a concentration in FinTech  
Fordham University, Gabelli School of Business  
[LinkedIn](https://www.linkedin.com/in/ryankah96/)

## Project Description

This project uses Python to analyze stock data for Tencent, Baidu, and Alibaba. The main features of the project include:
- Reading stock data from CSV files
- Calculating 4-day and 2-day moving averages
- Generating buy/sell signals based on the moving averages
- Plotting stock prices and moving averages

## Project Files

- `TCEHY.csv`, `BIDU.csv`, `BABA.csv`: CSV files containing stock price data for Tencent, Baidu, and Alibaba.
- `TCEHY_UPDATED.csv`, `BIDU_UPDATED.csv`, `BABA_UPDATED.csv`: CSV files that will be generated to store the buy/sell signals.

## Requirements

- Python 3.x
- pandas
- matplotlib

## Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/ryankahrimanian/stock-analysis.git
   ```
2. **Navigate to the Project Directory:**
   ```sh
   cd stock-analysis
   ```
3. **Install the Required Packages:**
   ```sh
   pip install pandas matplotlib
   ```

## Usage

1. **Run the Script:**
   ```sh
   python stock_analysis.py
   ```
2. **View the Results:**
   - The script will generate updated CSV files with buy/sell signals.
   - It will also display plots of stock prices and moving averages.

## Code Structure

- **Imports and File Paths:**
  The necessary libraries are imported, and the file paths for the CSV files are defined using relative paths for portability.

- **Plotting Function:**
  A function `plot` is defined to visualize stock prices and moving averages.

- **Processing Function:**
  The `process_stocks` function reads the stock data, calculates moving averages, generates buy/sell signals, and writes the results to new CSV files. It also calls the `plot` function to visualize the data.

## Future Enhancements

- Add error handling for missing or incorrect data.
- Include additional stock analysis metrics.
- Enhance the visualization with more interactive plots.

## Contact

For any questions or suggestions, feel free to reach out to me:

- **LinkedIn:** [Ryan Kahrimanian](https://www.linkedin.com/in/ryankah96/)
