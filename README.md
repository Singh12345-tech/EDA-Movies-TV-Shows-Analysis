# EDA-Movies-TV-Shows_Analysis
## Project Summary
Exploratory Data Analysis on catalog of 9871 Movies & TV Shows to drive product decisions for streaming platform. Data has 15 columns - tital, type, release_year, runtime, genres, age_certification, imdb_score, etc.
## Problem Statement
The platform needs to design homepage & recommendation engine to maximize user engagement. Catalog has major data quality issues - 65.7% age_certification missing.
## Key Findings
-Modern library with release year 2014
-Most reliable fields (100% coverage): type, runtime, release_year, genres
-Data gaps: seasons only 13.7%, imdb_score missing 1021 rows
## Tech Stack
-Tool: Google Colab
-Language: Python
-Libraries: Pandas, NumPy, Matplotlip, Seaborn, Plotly
## Dataset
9871 rows X 15 columns | Project 2 - AlmaBetter
## Outcome
Identified reliable fields for recommendation system and critical data cleaning steps before model building.
