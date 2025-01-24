# PySpark Movie and Review Data Analysis

This project showcases PySpark-based analysis of movie and review datasets. The primary focus is on data processing, cleaning, and analytics. Below are the key features:

## Features
1. **CSV Data Loading:** Load and preprocess movie and review data with Spark.
2. **Data Cleaning and Transformation:** 
   - Remove special characters.
   - Standardize text formats.
   - Handle multi-line strings.
3. **Analytics:**
   - Calculate movie statistics like the most frequent city, average vote scores, etc.
   - Top-10 most frequent words in movie overviews.
   - Identify top-rated movies with at least 100 reviews.
4. **Join and Comparison:**
   - Match movies appearing in both datasets.
5. **Review Insights:**
   - Top users by review count.
   - Count reviews per movie.
6. **Visualization Ready:** Cleaned datasets are ready for visualization tools.

## Datasets
- TMDB Movies Dataset (Kaggle)
- IMDB Movie Reviews Dataset (IEEE Dataport)

## Tools Used
- PySpark
- AWS S3
- Pandas (for validation)
- Jupyter Notebook
