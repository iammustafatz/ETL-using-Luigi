# ETL using Luigi

This repository contains an ETL (Extract, Transform, Load) pipeline implemented using Luigi, a Python package for building data pipelines. The pipeline extracts data from a CSV file hosted on a GitHub repository, performs some cleaning and transformation steps, and then loads the data into a SQLite database table.


## Usage

To run the pipeline, first clone the notebook in this repository to your local machine or Google colab and run the python notebook:

```http
  ETL_using_Luigi.ipynb
```

This will run the Luigi pipeline and execute the extract, transform, and load tasks.


## Pipeline Steps

1. Extract: The pipeline extracts data from a CSV file hosted on a GitHub repository.

2. Transform: The pipeline performs several data cleaning and transformation steps on the extracted data. These include converting data types, filling in missing values, and encoding categorical variables.

3. Load: The cleaned and transformed data is then loaded into a SQLite database table.


## Requirements

The following packages are required to run the ETL pipeline:

- Python 3.x
- Luigi
- Pandas
- NumPy
- SQLite3


## Conclusion

This ETL pipeline demonstrates how to use Luigi to create an automated data pipeline that extracts data from a remote CSV file, performs cleaning and transformation tasks, and loads the output into a local SQLite database. This approach can be easily adapted to work with other data sources and destinations, making it a useful tool for any data engineer or analyst.
