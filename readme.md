# Social Media Impacts of COVID-19 Pandemic

## Affiliation
* **San Jose State University** - Applied Data Science program
* **Database Systems for Analytics** (DATA 225)

**Contributors:**<br>
Catherine Cho, Dahlia Ma, Neha Singh, Mingshuo Yu, Yiyi Zhang 
<br><br>
This **README** file provides the scope/context of the project, as well on how to navigate and use this resository.

## Motivation and goals of our project
Since the COVID-19 pandemic, there has been an insurmountable increase in internet usage with an increase in quarantine regulations and transition to work-from-home settings. There has been mentions of change in social media posting trends and behavior, but there are very few accessible clean data for direct analysis. Hence, the goal of this project is to **create a database that contains COVID-19 related statistics data along with social media keywords and posts, so researchers can spend more time on direct analysis and less time on data wrangling**.

## Prerequisites
* Register and create an account with **Google Cloud Platform (GCP)**
* Register and create an account with **MongoDB (Atlas)** to create cloud cluster to store non-structured text data from API calls
* Install **MySQL and/or MySQL Workbench** to store structured data
* Create a developers account with Twitter
* Create a developers account with NY Times
* Install Python 3.x

## How to navigate this repository
| Directory | File Name | Description |
| :-------- | :-------- | :---------- |
| data_loading_ipynb_files | mongodb_setup.ipynb | contains Python code that connects to MongoDB cloud cluster database (using a JSON file as example)  |
| data_loading_ipynb_files | nytimes_covid19_data.ipynb | contains Python code that loads NY Times COVID-19 stats data |
| data_loading_ipynb_files | nytimes_covid_social.ipynb | contains Python code to call NY Times API and loads data from call |
| data_loading_ipynb_files  | twitter_data.ipynb | contains Python code used to load CSV Twitter data  |
| nytimes_api_py_files | create_tables.py | Python file that runs data definition (DDL) queries in MySQL |
| nytimes_api_py_files | etl.py | Python file that performs ETL |
| nytimes_api_py_files | sql_queries.py | Python file that contains data manipulation (DML) SQL queries  |
| nytimes_api_py_files | etl_python_run_procedure.png | a screenshot showing how to execute the python files in command line |
| twitter_api_py_files | twitterStream.py | Python file that connects to Twitter using API (not used in project) |
| gcp_raw_data_tables | raw_tables_all_Create.sql | SQL file that contains DDL statements to insert raw data into GCP |
| gcp_raw_data_tables |  |  |
| gcp_final_normalied_data_tables |  |  |
| gcp_final_normalied_data_tables |  |  |
| gcp_final_normalied_data_tables |  |  |