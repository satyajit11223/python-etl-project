# python-etl-project
ETL pipeline using Python and Pandas
# Insurance ETL Project

This project performs ETL (Extract, Transform, Load) operations on insurance data using Python and Pandas.

## Project Objective

The goal of this project is to clean, preprocess, and transform raw insurance data for analysis and reporting.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

## ETL Process

### Extract

* Loaded insurance dataset from CSV file

### Transform

* Handled missing values using `SimpleImputer`
* Cleaned duplicate records
* Processed categorical and numerical variables
* Prepared data for analysis

### Load

* Exported cleaned dataset for further analysis

## Files Included

* `etl.py` → Main ETL script
* `insurance_data.csv` → Input dataset
* `requirements.txt` → Required Python libraries

## How to Run

Install dependencies:

```bash id="ru6lpo"
pip install -r requirements.txt
```

Run the ETL pipeline:

```bash id="b3m9dz"
python etl.py
```

## Skills Demonstrated

* Data Cleaning
* ETL Pipeline Development
* Data Preprocessing
* Python Programming
* Pandas & NumPy
