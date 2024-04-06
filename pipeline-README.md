# TMDB Movies Dataset (2023) Processing Pipeline

This pipeline demonstrates how to read and process movie data from the TMDB Movies Dataset (2023) available on Kaggle using Python and pandas.
Dataset Overview

The TMDB Movies Dataset (2023) contains information about movies, including details like titles, release dates, genres, production companies, and more. The dataset can be accessed from Kaggle at the following link:

https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies/data

This README outlines the steps to set up and run a Python script that reads this dataset, performs data cleaning and processing, and saves the processed data into a new CSV file.

## Requirements
1. Python 3.x
2. `pandas` library
3. `nltk` library (for text tokenization)
4. Kaggle API credentials (for downloading the dataset from Kaggle). The `.json` should have credentials for downloading the dataset, however, it is recommended to create your own Kaggle account and retreive your own API token.
5. Alterntively, you may download the dataset directly from the linke above.

## Setup
### Install Required Libraries:
Install `pandas`, `nltk` and `opendatasets` libraries using pip if you haven't already:

`pip install pandas`

`pip install nltk` 

`pip install opendatasets`

## Usage
### Run the Python Script:
Execute the `movie_project_datareader.ipynb` script to read, process, and save the movie data:

This script performs the following steps:
1. Download the TMBD Movies Dataset, given the API tokenin the .json file.
2. Reads the TMDB Movies Dataset (2023) (movies.csv).
3. Cleans and processes the data (assigning data types, filtering, tokenization).
4. Saves the processed data into a new CSV file (processed_movie_data.csv).
