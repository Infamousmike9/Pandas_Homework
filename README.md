## Pandas Homework

Student: Michael De Paula

---
---
<p align="center">
 <ins><b>Portfolio Analysis</b><br><ins>
</p>


This repository is a portfolio analysis in which we are analyzing seven separate portfolios and comparing to the [S&P 500](https://www.google.com/finance/quote/.INX:INDEXSP). 

The analysis begins by first reading several csv files which contain stock data pulled from Google Finance via the (=GOOGLEFINANCE) sheets formula. 
Once the data is pulled in CSV file format it is cleaned of null values and indexed by Date. 
The cleaning and indexing will allow for us to concat the separate data into one data-frame for efficient manipulation using pandas via a Jupyter notebook via the file __whale_analysis_Mike.ipynb__.
The analysis begins with simple daily return calculations and eventually we move on to the following:

All calculations and plots are done using pandas data-frame manipulation.

- Daily Portfolio Returns plotting.
- Cumulative returns calculation and plotting.
- Risk Analysis:
    - Box Plot for Portfolio risk
    - Daily Standard Deviation
    - Volatility
    - Standard Deviation for one year (252 days)
- Rolling Statistics:
    - Rolling Standard Deviation for 21 day period
    - Correlation table
    - Compare Beta of one portfolio to S&P 500
    - Plot the beta and compare 
    - Exponentially Weighted Moving average calculated and plot
- Sharpe Ratios
    - Annualized Sharpe ratios
    - Visualization of Sharpe Ratios

After this initial analysis is complete, we will create a custom portfolio of three stocks, in my case I have selected __Freeport McMoRan__([FCX](https://www.google.com/finance/quote/FCX:NYSE)), __Microsoft__ ([MSFT](https://www.google.com/finance/quote/MSFT:NASDAQ)) and __Intel Corporation__ ([INTC](https://www.google.com/finance/quote/INTC:NASDAQ)). We will obtain data for each company via Google sheets using the GoogleFinance formula and save each stock on a separate CSV file. We will then follow the same steps for reading, cleaning and indexing the csv files to prepare for analysis.

Once each file is read, cleaned and indexed we will combine (concat) into a single data-frame using pandas. We will follow the exact analysis previously done above, however, there is a difference in which we will be calculating the weighted returns for each stock in the custom portfolio assuming an equal number of shares for each stock. 

Once the above analysis is completed we will combine our custom portfolio to the previously originally combined portfolios and compare risk, statistics, Sharpe Ratios and eventually plot our BETA for the custom portfolio compared to the S&P 500. 

All data used for the analysis is contained in a folder named Data within the repository.



