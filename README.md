# Product Recommendation System

## Project Overview
This project aims to develop a product recommendation system using Amazon product data. The system is designed to provide personalized product suggestions to users based on their browsing and purchasing history, enhancing user experience and potentially increasing sales.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Sentiment Analysis](#sentiment-analysis)
- [Content-Based Filtering](#content-based-filtering)
- [Hybrid Recommendation Approach](#hybrid-recommendation-approach)
- [Results](#results)
- [Key Findings and Insights](#key-findings-and-insights)
- [Examples of Recommendations](#examples-of-recommendations)
- [Challenges and Learnings](#challenges-and-learnings)
- [Future Work](#future-work)
- [Conclusions](#conclusions)

## Technologies Used
- Python
- Pandas, NumPy - for data manipulation
- Matplotlib, Seaborn - for data visualization
- NLTK, TextBlob - for text processing and sentiment analysis
- Scikit-learn - for implementing machine learning models and similarity measurements

## Data Preprocessing
- Data cleaning: Removed missing values and extracted necessary features.
- Feature transformation: Converted prices and ratings from strings to numerical values to facilitate analysis.

## Exploratory Data Analysis
- **Price vs Rating**: Analyzed how prices (both actual and discounted) correlate with product ratings.
- **Top Categories**: Identified the top product categories based on the available data to target popular segments.

## Sentiment Analysis
- Performed sentiment analysis on user reviews.
- Classified sentiments into Positive, Neutral, and Negative categories.
- Visualized the distribution of these sentiments to understand consumer emotions towards products.

## Content-Based Filtering
- Implemented a TF-IDF Vectorizer to transform text data into a format suitable for similarity comparison.
- Calculated cosine similarity scores among products to identify similarities.

## Hybrid Recommendation Approach
- Combined content-based and collaborative filtering techniques to enhance recommendation accuracy.
- Content-based recommendations were derived from textual similarity, while collaborative filtering considered user ratings.

## Results
- The hybrid model provided a balanced approach, taking into account both product content and user interaction.
- Demonstrated the ability to recommend similar and relevant products based on a sample product input.

## Key Findings and Insights
- Significant correlation between discounted prices and customer ratings, suggesting price sensitivity among consumers.
- Positive reviews overwhelmingly dominate, indicating general customer satisfaction.

## Data Visualizations



## Examples of Recommendations


## Challenges and Learnings
One challenge was dealing with sparse data, which we mitigated by applying smoothing techniques in our collaborative filtering model.

## Future Work
We plan to explore deep learning techniques to further enhance the personalization aspect of our recommendations.

## Conclusions
The developed product recommendation system showcases the effective use of both content-based and collaborative filtering methods to recommend products. This system can be integrated into e-commerce platforms to enhance user experience by providing personalized recommendations.



