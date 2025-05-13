# COVID-19 Global Data Tracker

## Project Overview

The COVID-19 Global Data Tracker is a data analysis project designed to explore, clean, and visualize COVID-19 data using Python. It aims to provide insights into the global impact of the pandemic, focusing on selected countries.

## Dataset

The project uses the **OWID COVID-19 Data** dataset, which contains COVID-19 data from countries worldwide. The data is stored in a CSV file named **`owid-covid-data.csv`**.

## Key Features

1. **Data Loading and Exploration:**

   * Loads the dataset using pandas and checks for missing values and data types.
   * Handles file loading errors with exception handling.

2. **Data Cleaning:**

   * Filters the dataset to include the most populated countries per continent: India, United States, Nigeria, Brazil, Germany, and Australia.
   * Converts date columns to datetime format.
   * Fills missing values with zero.

3. **Exploratory Data Analysis (EDA):**

   * Analyzes and visualizes key metrics using line plots, bar charts, and interactive plots with Matplotlib, Seaborn, and Plotly.
   * Visualizes trends over time for total cases, total deaths, new cases, death rates, vaccination trends, and monthly average vaccinations.

## Analysis Highlights

* The United States exhibited the highest growth in COVID-19 cases, while Nigeria reported the lowest.
* COVID-19 death trends closely follow the case trends, with Brazil showing a higher death rate compared to total cases.
* Vaccination analysis reveals significant differences between countries, with the United States leading in total vaccinations.

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Plotly

## Usage

1. Clone the repository and navigate to the project directory.
2. Ensure you have Python and the required libraries installed.
3. Run the Python scripts to load, clean, analyze, and visualize the data.
4. View the generated plots and infer insights.

## Results

The project produces various plots showcasing the COVID-19 trends over time for each selected country, focusing on:

* Total cases
* Total deaths
* New cases
* Death rate
* Total vaccinations
* Monthly average vaccinations


## Contact

For questions or suggestions, feel free to reach out.
