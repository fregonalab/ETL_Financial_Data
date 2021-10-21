# Data Ingestion & Processing of Financial Reports - 10-K 

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)

## Description
The use of data for prediction of stocks has grown in the last 5 years. Both robots and analysts have started to make predictions, and estimates based on financial data, which are regulated and can be found in SEC EDGAR website. In this project, we focused on acquiring financial data from an open-source API called SimFin. The main documents extracted from the API are the income statement, balance sheet, and cash flow of Apple and Google. The methodology choosen for data ingestion & processing was the extract, trasnform, and load (ETL) process. The final document is a .csv file containing all three documents and ready to be download to a relational database.
	
## Technologies
Project is created with:
* Conda - Jupiter Notebook: 2.1.0
* Python: 3.7.3
  * Libraries: requests, pandas, os, numpy, datetime, glob
* Unix: OS version 18.7.0
* Git and Github
