# Covid-19 Micro Analysis Project 

## Introduction

The "Covid-19 Micro Analysis" project provides a focused analysis of a small dataset containing information about the Covid-19 pandemic. This dataset has been curated for the purpose of understanding and learning. For a more comprehensive analysis, it is recommended to use the original dataset, which contains approximately 19,000 rows of data. The data used in this micro-analysis is up to April 29, 2020, and has been sourced from Kaggle in CSV format. The primary tool for this analysis is the Pandas dataframe, a powerful library for data manipulation and analysis in Python.

## Data Loading and Overview

The project begins by loading the dataset using the Pandas library, revealing its structure and initial records. The dataset includes columns such as Date, State, Region, Confirmed cases, Deaths, and Recovered cases. Exploratory data analysis techniques are employed to understand the nature of the data, including the count of non-null values and the presence of missing values in each column.

## Null Values and Heatmap
![image](https://github.com/no37no37/covid19_micro_analysis/assets/132648428/8f8750f9-f391-4440-9359-fb8cff6af2ac)

A detailed examination of null values is conducted, revealing that the "State" column has a significant number of missing values (181). A heatmap visualization is employed to provide a clear representation of the distribution of null values in the dataset.

## Analysis of Cases by Region

The project aims to analyze the number of Confirmed, Deaths, and Recovered cases in each region. Using the "groupby" function, the sum of Confirmed and Recovered cases is calculated for each region. The results are then displayed, showcasing the regions with the highest number of cases.

## Data Filtering

To refine the dataset, records where the number of Confirmed cases is less than 10 are removed. This step helps focus the analysis on regions with more significant impact. The dataset is updated accordingly, and the resulting records are displayed.

## Region-wise Analysis

The analysis extends to determining the region with the maximum and minimum number of Confirmed and Deaths cases. The "groupby" function is utilized to aggregate and summarize the data, providing insights into the most and least affected regions.

## Country-specific Insights

Specific insights related to India are extracted, showcasing the number of Confirmed, Deaths, and Recovered cases reported till April 29, 2020.

## Data Sorting

The dataset is sorted based on the number of Confirmed and Recovered cases in ascending and descending order, respectively. This step aids in identifying regions with the least and most impact.

In summary, the "Covid-19 Micro Analysis" project provides a detailed exploration of the available dataset, offering insights into regional impacts, data cleaning, and specific country-wise statistics. The use of Pandas facilitates efficient data manipulation, enabling a meaningful analysis of the Covid-19 data.
