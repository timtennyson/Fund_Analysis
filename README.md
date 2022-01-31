# Fund_Analysis
Application to assess risk/reward over time of several fund vs the S&amp;P 500

Welcome. In this application, we are assessing the risks and rewards for several funds vs the s&p 500.

## Technologies
[Python3.7](https://www.python.org/)

[Jupyter Lab](https://jupyter.org/)

[Pandas](https://pandas.pydata.org)

[Pathlib](https://docs.python.org/3/library/pathlib.html) 

[Matplotline](https://matplotlib.org/)

## Installation guide
In order to run this application you'll need to install Python3.7 in conjunction with jupyter lab and the pandas and pathlib libraries linked above. 

## Usage

### 1)Collecting the data
This application is designed to be used with csv files.
Here we collect the data using pandas read_csv function.
We then ensure the data has been imported properly by calling the "head" function.

### 2)Analyze the Performance
Here, we plot the data showing the daily close (.pct_change) in a single dataframe, "daily_returns". The data is displayed in both line and box plots. Metrics include daily return, mean returns, and standard deviation for each portfolio and the S&P 500.

### 3) Analyze the risk
In this section we analyze and plot the risk/reward for each fun using standard deviation, average annual return, rolling 60 day returns, Sharpe Ratio, Variance. As can be seen, Berkshire Hathaway has the best risk/reward profile of the funds. The best performer for this time period was the S&P 500, but it is composed of riskier assets.

## Contributors

Tim Tennyson 
<ttennyson.xyz@gmail.com>

License: Open source, free distribution/reproduction