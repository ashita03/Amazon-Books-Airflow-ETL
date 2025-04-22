# 📚 Amazon Books Airflow ETL
This project demonstrates an ETL (Extract, Transform, Load) pipeline built using **Apache Airflow** to collect books data from the Amazon website and store it in a **PostgreSQL database** for further analysis or reporting.

## Project Overview

1. Extract: Scrape book information from Amazon's website.
2. Transform: Clean and normalize the raw data (e.g., handle missing fields, standardize formats).
3. Load: Insert the transformed data into a PostgreSQL database.

## Tech Stack

* Apache Airflow – Workflow orchestration
* Python – Scripting and data processing
* BeautifulSoup / Requests – Web scraping
* PostgreSQL – Data storage
* Docker – Containerization

## Features

* Automated data pipeline with scheduling via Airflow DAGs
* Robust error handling and logging
* Modular and scalable code structure
* Easily configurable to extract different book categories or pages

### Check out [official Airflow Documentation](https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html) to learn more

