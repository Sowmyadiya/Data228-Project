# Data228-Project
The housing market in the United States is one of the quickest developing areas and most secure spots to contribute for many people.. The real estate market has encountered critical repetitive instability in the course of the last a quarter century because of major underlying changes and financial vacillations. These days, we can see a great deal of instability in the real estate market. It may very well be because of the COVID-19 pandemic, telecommuting, rising pay in few industries, lack of inventory, high timber costs, and record-low home loan rates. Housing prices have touched an all-time high in most US cities while the affordability issue is worsening and increasing job losses. The sudden growth of house prices looks like a bubble because in the past we have seen some housing market crashes like in the 1980s and 2008. The latest housing bubble was observed in 2008. Housing prices touched the peak in 2016 and started falling from early 2007 and reached a record low in 2012. Our main objective in this project is to analyze the changes in trends during the period of five years from 2016 to 2021. Through our analysis, we will find the market's steadiness and observe the overall average growth of the US housing market from 2016 to 2021.

Steps:

1) The data for the analysis is gathered from multiple sources
2) The data files are cleaned and merged based on common columns
3) The cleaned data is loaded to Amazon S3 Bucket in CSV format
4) The structure of the table is created using AWS Glue Crawler
5) Data is then converted into tables using the AWS Glue job, which tranfers the data from S3 to Redshift 
6) Data is explored using the Data Mining techniques in AWS Sagemaker
7) The trends are visualized using Tableau.
