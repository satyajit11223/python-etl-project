# Insurance Data Preprocessing ETL Project

This project performs ETL (Extract, Transform, Load) and data preprocessing operations on insurance data using Python.

## Project Objective

The objective of this project is to clean, preprocess, and transform raw insurance data for machine learning and analytical purposes.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

## ETL & Data Preprocessing Steps

### Extract

* Loaded insurance dataset from CSV file

### Transform

* Handled missing values using `SimpleImputer`
* Removed duplicate records
* Processed categorical and numerical variables
* Applied feature binning using `KBinsDiscretizer`
* Prepared dataset for machine learning models

### Load

* Exported cleaned and transformed data for analysis

## Project Files

```text id="mjlwmj"
python-etl-project/
│
├── Data Preprocessing.ipynb
├── Data_Dictionary_Insurance.xlsx
├── Insurance.csv
├── requirements.txt
├── README.md
```

## File Description

* `Data Preprocessing.ipynb` → Jupyter notebook containing ETL and preprocessing steps
* `Data_Dictionary_Insurance.xlsx` → Description of dataset variables and columns
* `Insurance.csv` → Raw insurance dataset
* `requirements.txt` → Required Python libraries
* `README.md` → Project documentation

## How to Run the Project

Install dependencies:

```bash id="ldwrkr"
pip install -r requirements.txt
```

Open Jupyter Notebook:

```bash id="m8j0lm"
jupyter notebook
```

Run:

```text id="fjlwmg"
Data Preprocessing.ipynb
```

## Skills Demonstrated

* ETL Pipeline Development
* Data Cleaning
* Data Preprocessing
* Feature Engineering
* Machine Learning Data Preparation
* Python Programming
* Pandas & Scikit-learn
