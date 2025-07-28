# CIS-509-Analytics-Unstructured-Data-Yelp-Data-Analysis

# Yelp Data Analysis Project

## Overview
This project analyzes Yelp restaurant reviews to identify key factors contributing to positive and negative ratings, explore relationships between reviews, tipping behavior, and overall ratings, and compare trends across Florida (FL) and Pennsylvania (PA). The focus is on restaurants serving American, Chinese, and Italian cuisine.

**Data Sources**
Yelp Dataset: https://business.yelp.com/data/resources/open-dataset/

We created filtered CSV files after processing the original JSON files to include only our required data:

- Filtered for restaurants in FL and PA serving American, Chinese, and Italian cuisine

- Resulting filtered CSV files:

  - F_filtered_business.csv

  - F_filtered_review.csv

  - F_filtered_user.csv

  - F_filtered_tip.csv

These filtered CSV files were used for all subsequent analyses in our project.

## Key Findings

**Sentiment Analysis:**

1-Star Reviews: Focus on complaints about food, service, delays, and overall experience

5-Star Reviews: Highlight praise for food quality, great experiences, and excellent service

**Topic Modeling:**

Common themes across cuisines: Food quality, service issues

American Cuisine: Wings, brunch, happy hour specials

Chinese Cuisine: Authentic dishes, dim sum, service complaints

Italian Cuisine: Pizza, pasta, wine pairings, gluten-free options

**Regional Preferences:**

Florida: Higher preference for Italian and seafood, outdoor dining, brunch

Pennsylvania: Higher preference for wings and pancakes, concerns about parking and tipping

**Factors Influencing Ratings:**

Positive: Food quality, ambiance, specific dishes, dining experience

Neutral: Administrative procedures (reservations, payment methods)

Negative: Poor service, refund problems, waiting times, overall negative experiences

**Key Statistics**

Total Reviews: 845,306

Unique Words: 297,193

Unique Customers: 351,921

Businesses: 8,642

Reviews for PA: 566,833

Reviews for FL: 398,808

American Cuisine Reviews: 676,072

Chinese Cuisine Reviews: 100,164

Italian Cuisine Reviews: 189,405

**Analysis Techniques**

- Exploratory Data Analysis (EDA)

- Sentiment Analysis

- Topic Modeling

- Word Cloud Visualization

- Bigram and Trigram Analysis


## Project Navigation
The project is organized into multiple Python files:

***CIS-509-Yelp-Data-Analysis-Project-Part-1.ipynb:***

- Initial data loading and preprocessing

- Exploratory Data Analysis (EDA)

- Bigram and Trigram analysis

- Word Cloud visualizations

***CIS-509-Yelp-Data-Analysis-Project-Part-2.ipynb:***

- Topic Modeling using BERTopic

- Sentiment Classification

- Regional and Cuisine Comparison


## Recommendations

- Focus on improving food quality across all cuisines

- Enhance service training to address common complaints

- Tailor offerings to regional preferences (e.g., outdoor seating in Florida)

- Improve operational efficiency in areas like reservations and payment processing

- Address specific cuisine-related opportunities:

  - American: Emphasize brunch and happy hour specials

  - Italian: Expand gluten-free options

  - Chinese: Improve service quality

## Tools and Technologies Used

- Python

- Pandas

- NLTK

- Matplotlib

- Seaborn

- BERTopic

## Future Work

- Incorporate more advanced natural language processing techniques

- Analyze temporal trends in reviews and ratings

- Investigate the impact of external factors (e.g., economic conditions, seasonal variations) on restaurant ratings
