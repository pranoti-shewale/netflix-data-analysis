# Netflix Data Analysis using Python

## Project Overview

This project explores the Netflix Titles dataset using Python to analyze content distribution, genre trends, release patterns, and platform growth over time.

The analysis focuses on cleaning the dataset, handling missing values, performing feature engineering, and generating meaningful business insights through visualizations.

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Data Cleaning & Preparation

The following preprocessing steps were performed:

- Handled missing values in director, cast, country, and rating columns.
- Removed rows with missing duration values.
- Converted `date_added` column to datetime format.
- Created a separate copy of the dataset for genre and cast analysis.
- Split and exploded genre (`listed_in`) column for detailed genre distribution.
- Split and exploded cast column to identify top actors.
- Extracted month from `date_added` for monthly trend analysis.
- Extracted numeric duration for movie runtime analysis.

---

## Analysis Performed

1. Distribution of Movies vs TV Shows
2. Top 10 Countries by Content Count
3. Genre Distribution Analysis (after splitting and exploding genres)
4. Top 10 Directors by Number of Titles
5. Top 10 Actors (after splitting and exploding cast data)
6. Monthly Content Addition Trend
7. Movie Duration Distribution (Runtime Analysis)
8. Rating Distribution Analysis
9. Content Release Trend Over the Years 

---

## Key Insights

- Movies dominate the Netflix content library compared to TV Shows.
- The United States contributes the highest number of titles.
- Drama and International genres are highly represented.
- Most movies have a runtime between 90 and 120 minutes.
- Content additions increased significantly after 2015, indicating rapid platform expansion.

---

## Repository Structure

```
Netflix-Data-Analysis/
│
├── netflix_data_analysis.ipynb
├── netflix_titles.csv
└── README.md
```

---

## Author

Pranoti Shewale  
Aspiring Data Analyst  
Skills: Python | SQL | Power BI
