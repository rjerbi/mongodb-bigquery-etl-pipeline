# MongoDB to BigQuery ETL Pipeline

## Overview
A Python-based ETL pipeline that extracts data from MongoDB, transforms and enriches it using Pandas, and loads new records into Google BigQuery while avoiding duplicates.

## Features
- Extract data from ESOS and ESIS MongoDB collections.
- Clean and normalize data.
- Convert and process date fields.
- Calculate lease duration and financial differences.
- Detect new records using MongoDB `_id`.
- Load transformed data into BigQuery.

## Technologies
- Python
- Pandas
- MongoDB / PyMongo
- Google BigQuery
- Google Cloud Authentication
- Python Dateutil

## Execution

```bash
pip install -r requirements.txt
python etl.py
