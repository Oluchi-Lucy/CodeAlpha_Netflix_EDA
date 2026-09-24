# CodeAlpha Task 2: Exploratory Data Analysis (Netflix Dataset)

This project was completed as part of the CodeAlpha Data Analytics Internship — Task 2: Exploratory Data Analysis (EDA).

# Objective
To explore a real-world dataset, understand its structure, identify data quality issues, and uncover meaningful patterns before any visualization or modeling work.

# Dataset
[Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows) by Shivam Bansal (Kaggle)
- 8,807 titles
- 12 columns: show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description

# Process
1. *Structure check* — Used df.info() and df.isnull().sum() to understand data types and missing values.
2. *Content mix analysis* — Compared the number of Movies vs TV Shows.
3. *Geographic analysis* — Identified top content-producing countries.
4. *Time trend analysis* — Examined how many titles were released each year.
5. *Genre analysis* — Found the most common genre combinations.
6. *Director analysis* — Identified the most prolific directors on the platform.
7. *Duration analysis* — Examined the distribution of movie runtimes.

# Key Findings
- Netflix has significantly more Movies (6,131) than TV Shows (2,676) — roughly a 70/30 split
- Missing data: director (2,634 missing), country (831 missing), cast (825 missing) — director is the biggest data quality gap
- The United States (2,818 titles) and India (972 titles) are the top content-producing countries
- Content additions grew steadily from 2012, peaking in 2018 (1,147 titles), then declined — 2021 data is incomplete since the dataset was collected mid-year
- Dramas and International Movies are the most common genre combination
- Rajiv Chilaka is the most prolific director (19 titles)
- Average movie runtime is about 100 minutes, with most falling between 87–114 minutes

# Tools Used
- Python
- Pandas

# Author
Oluchi
