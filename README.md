# ETL-CSV-Data-Pipeline

This project demonstrates a basic ETL (Extract, Transform, Load) pipeline that processes stock market data. The pipeline extracts data from a CSV file, transforms it by calculating key metrics, and loads the processed data into an SQLite database.

Project Overview

1. Extract: The stock data is extracted from a CSV file containing columns such as Date, Stock, Open, High, Low, Close, and Volume.
   
2. Transform:
   
   * Missing values are checked (if any).
   
   * The data is sorted by Date and Stock.
   
   * A new column, Price Change, is added, which calculates the difference between the Close and Open prices.

   
3. Load: The transformed data is inserted into a local SQLite database for further analysis and storage.

   
Technologies Used


  * Python: For scripting the ETL process.
    
  * Pandas: For data extraction and transformation.
    
  * SQLite: For storing the processed data.

  * Jupyter Notebook: For code execution and testing.

Files

  * random_stock_data.csv: The sample CSV file containing stock data.
  * ETL_Stock_Data_Pipeline.ipynb: The Jupyter Notebook containing the ETL pipeline code.
  * stock_data.db: The SQLite database where the processed data is stored.
