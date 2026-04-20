# Instagram Analytics - Exploratory Data Analysis (EDA)

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on an Instagram analytics dataset to uncover patterns in user engagement, content performance, and posting behavior.

The analysis focuses on identifying **key factors that influence post performance**, such as engagement rate, impressions, content type, and posting time.

---

## Objectives

* Understand dataset structure and features
* Perform data cleaning and preprocessing
* Analyze engagement metrics (likes, comments, shares, impressions)
* Identify trends in content performance
* Study the impact of posting time on impressions
* Categorize posts using performance buckets

---

## Dataset Information

* Dataset: `Instagram_Analytics.csv`
* Rows: ~30,000
* Columns: 23

### Key Features:

* `likes`, `comments`, `shares`, `saves`
* `impressions`, `reach`
* `engagement_rate`
* `post_hour`
* `content_category`, `media_type`, `account_type`
* `performance_bucket_label`

---

## Technologies Used

* Python 
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## EDA Steps

### 1. Data Loading & Inspection

* Loaded dataset using Pandas
* Checked shape, columns, and datatypes

### 2. Data Cleaning

* Removed missing values
* Dropped duplicate records

### 3. Univariate Analysis

* Distribution of numerical features using histograms
* Count plots for categorical variables

### 4. Bivariate Analysis

* Likes vs Comments
* Reach vs Engagement Rate

### 5. Feature Engineering

* Created `engagement_score`
* Classified posts based on time (Before/After 7 PM)

### 6. Outlier Detection

* IQR Method
* Z-score Method

### 7. Time-Based Analysis

* Studied engagement based on posting hour
* Found higher impressions after 7 PM

### 8. Performance Bucket Analysis

* Analyzed distribution of:

  * Low
  * Medium
  * High performance posts

* Compared:

  * Engagement rate
  * Impressions across buckets

---

## Key Insights

* Posts with higher reach tend to have higher engagement
* Posts after **7 PM** receive more impressions
* Content category significantly affects performance
* More hashtags do not always increase engagement
* High-performance posts show:

  * Higher engagement rates
  * More impressions

---

## Performance Bucket Explanation

Posts are categorized into:

* **Low Performance**
* **Medium Performance**
* **High Performance**

This classification is based on engagement metrics and helps simplify analysis.

---

## Sample Visualizations

* Bar charts for performance distribution
* Scatter plots for engagement relationships
* Time-based trend graphs

---

## Future Improvements

* Build ML model to predict post performance
* Optimize posting time recommendation system
* Perform sentiment analysis on captions
* Deploy dashboard using Streamlit

---

## How to Run

```bash
# Clone repository
git clone https://github.com/your-username/instagram-eda.git

# Navigate to project folder
cd instagram-eda

# Install dependencies
pip install -r requirements.txt

# Run the notebook/script
jupyter notebook
```

---

## Conclusion

This EDA project provides valuable insights into Instagram post performance and helps in understanding how different factors influence engagement and reach.

---

## Author

**Tejas Kumar H**

---
