# Covid-19 Policy Analysis and Recommendation

**Project Overview:** 

This project explores data of COVID-19 growth rates, death rates, and policies across 10 different countries from January 2020 - March 2021. The countries analyzed include Canada, France, Germany, Italy, Japan, New Zealand, Russia, South Korea, Sweden, and the United Kingdom. The data is gathered from Azure SQL, Cosmos DB, and an on-premises data source within a Virtual Machine environment. The goal is to extract, clean, load and analyze this current data and create an enterprise Modern Data Pipeline solution that can be used for analysis and reporting by health and leadership officials. The project analyzes the global policies implemented by 10 representative countries to determine efficacy in keeping down Death and Cases growth rates of COVID-19, and recommends the three most effective policies at decreasing COVID rates.

**Steps Taken:**

1. Extracted data from Azure SQL, Cosmos DB, and an on-premises data source within a Virtual Machine environment to JSON and Parquet files.
2. Created relationships between the metrics data (cases, deaths, recoveries), and the other datasets (dates, countries, policies) using a star schema.
3. Merged all datasets by creating data pipelines to form a relational database warehouse in Azure Data Lake with fact tables (cases, deaths, recoveries, date, country), and dimension table (policies).
4. Loaded data into Azure Synapse Analytics and Microsoft Power BI to conduct analysis, create visualizations, and make policy recommendations.

**Architecture Overview**
![](assets/images/covidprojectarchitecture.png | width=300)

