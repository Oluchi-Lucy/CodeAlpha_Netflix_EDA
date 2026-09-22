# CodeAlpha Netflix Data Analytics Project

This project was completed as part of the CodeAlpha Data Analytics Internship. It uses the Netflix Movies and TV Shows dataset from Kaggle to explore, visualize, and analyze patterns in Netflix's content library.

# Dataset
[Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows) by Shivam Bansal (Kaggle)
- 8,807 titles
- 12 columns: show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description

# Task 2: Exploratory Data Analysis (EDA)

Explored the dataset to understand its structure and find patterns.

*Key Findings:
- Netflix has more Movies (6,131) than TV Shows (2,676) — roughly a 70/30 split
- The United States (2,818 titles) and India (972 titles) are the top content-producing countries
- Content additions grew steadily, peaking in 2018, then declined (2021 data is incomplete)
- Dramas and International Movies are the most common genre combinations
- Rajiv Chilaka is the most prolific director (19 titles)
- Missing data: director (2,634 missing), country (831 missing), cast (825 missing)
- Average movie runtime is about 100 minutes

# Task 3: Data Visualization

Created 6 charts using Python (Matplotlib & Seaborn) to visualize the EDA findings:
1. Movies vs TV Shows (bar chart)
2. Top 10 Countries by content count (horizontal bar chart)
3. Content released by year (line chart)
4. Top 10 genre combinations (horizontal bar chart)
5. Distribution of movie durations (histogram)
6. Top 10 directors by number of titles (horizontal bar chart)

# Task 4: Sentiment Analysis

Used TextBlob (an NLP library) to analyze the tone of each show's description.

*Key Findings:
- Most descriptions (4,547) are Positive in tone
- 2,662 are Negative, and 1,598 are Neutral
- Movies and TV Shows have very similar sentiment patterns — content type doesn't significantly affect description tone

*Insight & Recommendation:
Since most Netflix descriptions are written with a positive tone — even for serious or dark shows — this suggests Netflix intentionally frames content to sound appealing. Content teams could continue this approach consistently across future titles to help maintain strong viewer engagement.

# Tools Used
- Python
- Pandas
- Matplotlib & Seaborn
- TextBlob

# Author
Oluch
