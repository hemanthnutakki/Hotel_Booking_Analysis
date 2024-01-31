## Hotel Booking Analysis

## Overview

This Python script analyzes hotel booking data using the pandas, matplotlib, and seaborn libraries. The script performs exploratory data analysis (EDA) and data cleaning on the provided dataset 'hotel_booking.csv'. It then visualizes various aspects of the data to gain insights into reservation trends, cancellation rates, and average daily rates.

## Dependencies

- Python (>=3.6)
- pandas
- matplotlib
- seaborn
- warnings

## Dataset

The dataset used for this analysis is 'hotel_booking.csv'. The script reads the dataset using pandas and performs data cleaning to handle missing values.

## Exploratory Data Analysis (EDA)

The script includes the following EDA steps:

- Loading the dataset and displaying basic information.
- Examining the dataset's structure, columns, and data types.
- Cleaning the data by handling missing values and removing unnecessary columns.
- Analyzing cancellation rates and visualizing results.

## Data Analysis and Visualization

The script generates various visualizations, including:

- Reservation status count (bar chart).
- Reservation status in different hotels (bar chart).
- Average Daily Rate (ADR) trends in City and Resort hotels (line chart).
- Reservation status per month (bar chart).
- ADR per month for canceled reservations (bar chart).
- Top 10 countries with the highest number of canceled reservations (pie chart).
- Market segment distribution (bar chart).
