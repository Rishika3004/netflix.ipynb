#Netflix Data Analysis Project-
A comprehensive data analysis project exploring Netflix content using SQL and Python to uncover insights about movies, TV shows, genres, and viewing patterns.

#Project Overview-
This project analyzes Netflix's content catalog to answer key questions about:
Content distribution by type, genre, and country
Release trends over time
Rating patterns and content duration
Geographic content availability
Popular directors and cast members

#Tools Used-
Python: Data processing and visualization
SQL: Data querying and analysis
pandas: Data manipulation
matplotlib/seaborn: Data visualization
Jupyter Notebook: Interactive analysis

netflix-data-analysis/
│
├── data/
│   ├── raw/
│   │   └── netflix_titles.csv
│   └── processed/
│       └── netflix_cleaned.csv
│
├── sql/
│   ├── create_tables.sql
│   ├── data_cleaning.sql
│   └── analysis_queries.sql
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_cleaning.ipynb
│   └── 03_analysis_visualization.ipynb
│
├── src/
│   ├── data_loader.py
│   ├── data_cleaner.py
│   └── visualizer.py
│
├── results/
│   ├── figures/
│   └── reports/
│
├── requirements.txt
└── README.md

#Key Insights-
Based on the analysis, here are some sample insights:
Content Mix: Netflix catalog is approximately 6126 movies and  2664 TV shows
Geographic Focus: United States, India, and United Kingdom are top content producers
Genre Preferences: International Movies, Dramas, and Comedies dominate the platform
Growth Pattern: Significant content addition growth from 2015-2020
Rating Distribution: TV-MA and TV-14 content represents the largest segments

#Data Considerations

Dataset is from 2021 and may not reflect current Netflix catalog
Some entries may have missing or incomplete information
Content availability varies by geographic region
Data cleaning steps are documented in notebooks
