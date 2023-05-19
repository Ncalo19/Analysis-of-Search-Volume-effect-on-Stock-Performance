# Exploring Search Relevance as an Indicator for Corporate Quarterly Financial Reports 
Authors: Jason Coffman (jascoffm@) and Nicolas Calo (ncalo@)

24 May 2021

## Description of Data Files
`sp500_companies.json`: JSON of companies listed in the S&P 500 Index

`google_trend_sp500.csv`: CSV document of Google Trend data retrieved via the pytrends package. Data for all 504 stock symbols present in the S&P 500 Index are aggregated into this dataset

`merged_dataset.csv`: The end result of merging the _google_trend_sp500.csv_ file with the [Kaggle datasets](https://www.kaggle.com/tsaustin/us-historical-stock-prices-with-earnings-data). An explanation of formatting and abbreviations can be found in the project report

## Description of Code Documents
`GoogleTrendBuilder.ipynb`: Jupyter notebook used to call and aggregate Google Trends data via the pytrends library

`InitialMerge.ipynb`: Jupyter notebook with initial formatting and merging of the Google Trends and Earnings Kaggle datasets. Additionally, preliminary analysis performed within this notebook.

`EarningsEDA.ipynb`: Jupyter notebook with additional formatting and merging to ultimately generate the _merged_dataset.csv_ file. Additional exploratory data analysis (EDA) was carried out within this notebook as well.

`PredictiveModeling.ipynb`: Jupyter notebook with more extensive efforts in generating a predictive model and additional EDA/data visualizations. 
