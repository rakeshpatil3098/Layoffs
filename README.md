# Analysis of Layoffs in 2023: Regional and Company-wise Trends

## Overview
This project focuses on analyzing layoffs that took place in 2023, with the goal of identifying trends based on factors such as company, industry, location, and other key metrics. By using Python for data analysis, the project examines the patterns of layoffs across various sectors, with a particular focus on the tech and transportation industries.

A dashboard was created to visually represent trends in layoffs, including location-wise, company-wise, and industry-wise analysis. The data used for this analysis is sourced from Kaggle and saved as `layoffs.csv` in the repository.

## Tools & Technologies
- **Python** (Pandas, Matplotlib, Seaborn)
- **Excel** (for preliminary data processing)
- **Kaggle** (for the original data source)

## Data
The dataset used for the analysis is available in this repository as `layoffs.csv`. It contains detailed information about various layoffs that occurred across companies, including:
- **Company**: The name of the company.
- **Location_HQ**: The headquarters location of the company.
- **Industry**: The industry sector the company operates in.
- **Percentage**: The percentage of workforce laid off.
- **Date**: The date of the announcement.
- **Source**: The source of the information (article or internal memo).
- **Funds_Raised**: The amount of funds raised by the company (if applicable).
- **Stage**: The company’s stage (e.g., Series C, Acquired).
- **Country**: The country where the company is located.
- **Laid_Off_Count**: The number of employees laid off.
- **List_of_Employees_Laid_Off**: This section provides additional details (if available).

You can find a sample of the data in the `layoff.csv` file:

## Methodology
1. **Data Collection**: The data was gathered from multiple sources, including news articles, press releases, and internal reports. The dataset was saved as `layoffs.csv`.
2. **Data Processing**: The data was cleaned and processed using **Python (Pandas)**. Missing or inconsistent values were handled, and relevant columns were extracted.
3. **Data Visualization**: Visualizations were created using **Matplotlib** and **Seaborn** to identify trends in layoffs by industry, region, and company.

## Key Results
- The **tech sector** saw a significant number of layoffs, with companies like **Uber**, **Anaplan**, and **Retool** contributing heavily to the trend.
- The **SF Bay Area** was the most impacted region, as it is home to several major tech companies.
- **Series C** and **Acquired** stage companies were more likely to experience layoffs due to restructuring or acquisition processes.
- Companies like **Uber** laid off a significant number of employees in specific departments (e.g., recruitment, operations).

## Visuals
The project features a dashboard of visualizations that highlight key trends in layoffs. 

## Conclusion
The analysis of layoffs in 2023 reveals a clear trend in the tech and transportation sectors, especially in the **SF Bay Area**. The results provide valuable insights into regional and company-wise layoffs, with special attention to factors such as industry, company stage, and workforce reductions.
