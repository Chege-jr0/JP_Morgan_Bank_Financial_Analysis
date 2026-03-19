# JP MORGAN AND CHASE BANK FINANCIAL ANALYSIS
A full end to end data analysis project on JPMorgan and Chase Company covering (2022-2025). Built using Python, SQL, Excel and Power BI

# Project Objective
This project performs a deep dive financial analysis of JPMorgan Chase using real data pulled from Yahoo Finance. 

It covers data collection, cleaning, ratio calculation, SQL querying and visualization, with a final Power BI dashboard as capstone deliverable.

# Tech Stack
Python : Data Collection, cleaning and ratio calculations, visualisations.

SQLite : Structured storage, trend queries and YoY analysis.

Excel : Financial Modelling and Summary Tables.

Power BI : Interactive dashboard

# Getting Started 

1. Install Dependencies

   pip install requirements.txt

2. Run the Notebooks in order

   main.ipynb

   pythonplotting.ipynb

   sqlanalysis.ipynb

3. Live vs Sample Data
   
   find this line and set it accordingly
   USE_LIVE_DATA = True # Pulls from Yahoo Finance
   USE_LIVE_DATA = False # Uses bundled sample data


# Key Banking Ratios Explained
ROE => Ratio on Equity(>10%) => Profitability for Shareholders.

ROA => Ratio on Asset(>1%) => Efficiency of asset use.

NIM => NII/Earning Assets(2.5%) => Core Lending Profitability

Efficiency Ratio => Expense/ Revenue(>60%) => Cost Control(lower = better) 

Loan_to_Deposit => Loans/Deposit(60-80%) => Liquidity Balance.

# Key Findings

Total Revenue $127.7B(2022) - $181.8B(2025) => 42% change

Net Income $37.7B(2022) - $57B(2025) => 51% change

Diluted EPS $12.09(2022) - $20.02(2025) => 66% change

Basic EPS $12.10(2022) - $20.05(2025) => 65% change

Net Interest Income $66.7B(2022) - $96.5B(2025) => 45% change.

2022 was the baseline year - market volatility and an investment banking slowdown kept net income low despite solid fundamentals.

2023 was the inflection point - Fed rate hikes drove Net Interest Income up sharply, pushing net income +31.5 % YoY.

NII's share of revenue grew from 52% (2022) to 55% (2025) - lending became the dominant profit engine.

ROE consistenly above 10% benchmark - peaked above 19%, nearly double the industry average.

Efficiency ratio held below 60% throughout - a sign of disciplined cost management despite expenses growing from $76B to $10B.


# License

This project is for Educational and Portfolio Purposes only.

Financial data sourced from Yahoo Finance via the yfinance library.