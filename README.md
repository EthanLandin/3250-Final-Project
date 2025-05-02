# 3250-Final-Project
### Final project for Data wrangling class

The 3 main folders in this repository are Data, Mid-Program Files, and Python Code
 - Data contains the initial data for the analysis, and 1 midround save after all scraping has been completed
 - Mid-Program files contains all csv saves throughout the python program
 - Python Code contains the .ipynb file with the actual project code in it

| File Name | Description |
| ------ | ------ |
| company_ipo.csv | [initial IPO data] from Kaggle.com |
| stock_overview_scraped.csv | Initial data with new scraped columns included |
| ipo_data_2019_2021_cleaned.csv | First data save, after scraping updated prices |
| merged_ipo_cleaned1.csv | save after cleaning first columns of data |
| merged_ipo_cleaned2.csv | Save after scraping yfinance data for market cap |
| Final_ipo_data_cleaned.csv | Save after converting numbers into millions |
| Project_Part_2_Data.csv | Save after finishing part 2 of the project (current last save) |
| Project_Landin.ipynb | Python code for the project |


[initial IPO data]: <https://www.kaggle.com/datasets/shivamb/company-ipos-2019-2021>


| Field Name                | Data Type | Description                                      |
|--------------------------|-----------|--------------------------------------------------|
| IPO Date                 | object    | The date the company went public                |
| Symbol                   | object    | The company's stock ticker symbol               |
| Company Name             | object    | Name of the company at IPO                      |
| Current                  | float64   | The current stock price (on December 2021)      |
| Return                   | float64   | Percent return since IPO                        |
| IPO Price (Float)        | float64   | Cleaned version of IPO price as a number        |
| Todays Price             | float64   | Live current stock price from StockAnalysis     |
| Current Return (%)       | float64   | Return calculated from Todays Price vs IPO Price|
| Industry                 | object    | Industry category from Yahoo Finance            |
| Market Cap in Millions   | float64   | Market capitalization of Company                |
| Net Income (ttm) in Millions | float64 | Net income over the trailing twelve months  |
| Revenue (ttm) in Millions   | float64 | Revenue over the trailing twelve months     |
