# Google Play Store Data Analysis

## Overview
This project involves data cleaning and exploratory data analysis (EDA) of the Google Play Store dataset. The primary objective is to prepare the data for analysis and visualize key insights regarding app ratings, categories, and installations.

## Project Structure
- `Data Cleaning.ipynb`: Jupyter Notebook for data cleaning processes.
- `EDA.ipynb`: Jupyter Notebook for exploratory data analysis and visualizations.
- `googleplaystore_clean.csv`: Cleaned dataset ready for analysis.

## Data Cleaning
The data cleaning process includes:
- Loading the dataset using Pandas.
- Checking for and removing duplicate entries based on the 'App' column.
- Saving the cleaned dataset as `googleplaystore_clean.csv`.

## Exploratory Data Analysis (EDA)
The EDA process includes:
- Documenting feature information such as app name, category, rating, reviews, size, installs, type, price, content rating, genres, last updated date, current version, and minimum Android version.
- Analyzing and visualizing the top 5 apps in each of the top 5 genres based on the number of installs.
- Identifying the number of apps with ratings greater than 4.5 and visualizing the top 10 categories with such apps.

## Libraries Used
- `numpy`: For numerical operations.
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For data visualization.
- `seaborn`: For statistical data visualization.
- `warnings`: To manage warning messages in the output.

## Conclusion
This project demonstrates the ability to clean and analyze a real-world dataset, providing insights into app performance on the Google Play Store. The findings can be useful for developers and marketers to understand trends and improve app offerings.
