# Unilever Talent Hunt Program 2025 - Knorr


This repository contains the analysis and insights generated for the **Unilever Talent Hunt Program 2025 (UTH 2025)**. The project was submitted by **Team Achanak United**, consisting of team members **Alwan**, **Moosa**, and **John**, led by the last. The project involves data collection, cleaning, analysis, and visualization to provide actionable recommendations for Knorr's marketing strategy.




---

## Project Overview

### Case Study Files
- **[Knorr Case.pdf](https://github.com/johnramal/knorr_uth/blob/master/case_study/Knorr%20Case.pdf)**: Contains the case description and the problems faced by Knorr.
- **[Social Media Challenge UTH 2025pdf.pdf](https://github.com/johnramal/knorr_uth/blob/master/case_study/Social%20Media%20Challenge%20UTH%202025pdf.pdf)**: Provides instructions for the social media challenge, which was a prerequisite for the final presentation.
- **[UTH Powerpoint Template 2025.pptx](https://github.com/johnramal/knorr_uth/blob/master/case_study/UTH%20Powerpoint%20Template%202025.pptx)**: A generic template for the final presentation, where recommendations were submitted in a 5-slide deck.

---

### Data Collection and Analysis

1. **Google Search Trends**  
   - File: **[google_trends.ipynb](https://github.com/johnramal/knorr_uth/blob/master/google/google_trends.ipynb)**  
   - Description: Analyzed the top three searched words related to noodles using the Pytrends API. The results are stored in `google_search_trends_monthly.csv`.

2. **Daraz Noodles Market Analysis**  
   - Files:  
     - **[daraz_eda_and_cleaning.ipynb](https://github.com/johnramal/knorr_uth/blob/master/daraz/daraz_eda_and_cleaning.ipynb)**: Data cleaning and transformation of Daraz noodles market data.  
     - **[analyse.ipynb](https://github.com/johnramal/knorr_uth/blob/master/daraz/analyse.ipynb)**: Analysis and aggregation of the cleaned data.  
   - Datasets:  
     - `daraz_noodles_market.csv`: Raw dataset scraped using Apify.  
     - `cleaned_daraz_noodles_market.csv`: Cleaned and transformed dataset.  

3. **Reddit Comments Analysis**  
   - Files:  
     - **[reddit_bot.ipynb](https://github.com/johnramal/knorr_uth/blob/master/reddit/reddit_bot.ipynb)**: Scraped comments from Reddit posts related to noodles in Pakistan over the last two years using the Reddit API.  
     - **[vader.ipynb](https://github.com/johnramal/knorr_uth/blob/master/reddit/vader.ipynb)**: Performed sentiment analysis on the comments using VADER to check polarity and identify the most frequent words.  
   - Datasets:  
     - `reddit_comments_20250130_003525.csv`: Raw Reddit comments dataset.  
     - `tableau_summary_stats.csv`: Summary statistics for Tableau visualizations.  

---

### Visualizations
- **Insights Cropped**:  
  - **[insights_cropped](https://github.com/johnramal/knorr_uth/tree/master/insights_cropped)**: Contains cropped visualizations for Daraz, Google Trends, and sentiment analysis.  
    - `daraz_cropped.png`: Visualization of Daraz insights.  
    - `google_cropped.png`: Visualization of Google trends insights.  
    - `sentiment_cropped.png`: Visualization of sentiment analysis insights.  

---

## How to Use This Repository

1. **Case Study**: Refer to the **[case_study](https://github.com/johnramal/knorr_uth/tree/master/case_study)** folder for the case description, instructions, and presentation template.
2. **Data Analysis**: Navigate to the respective folders (`google`, `daraz`, `reddit`) to explore the data collection, cleaning, and analysis notebooks.
3. **Visualizations**: Check the **[insights_cropped](https://github.com/johnramal/knorr_uth/tree/master/insights_cropped)** folder for cropped visualizations used in the final presentation.

---

## Tools and Technologies Used
- **Python**: For data scraping, cleaning, and analysis.
- **Pytrends API**: For Google search trends data.
- **Apify**: For scraping Daraz noodles market data.
- **Reddit API**: For scraping Reddit comments.
- **VADER**: For sentiment analysis.
- **Tableau**: For data visualization.

---


## License
This project is licensed under the MIT License.