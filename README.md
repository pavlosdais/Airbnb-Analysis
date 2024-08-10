# **Airbnb Data Analysis and Recommendation System**
This repository contains code for a project focused on mining Airbnb data from the years 2019 and 2023. The project is divided into two main parts: data exploration and query analysis, and sentiment analysis with machine learning models.

## **Data**
The dataset contains the following columns:
- id
- zipcode
- transit
- Bedrooms
- Beds
- Review_scores_rating
- Number_of_reviews
- Neighbourhood
- Name
- Latitude
- Longitude
- Last_review
- Instant_bookable
- Host_since
- Host_response_rate
- Host_identity_verified
- Host_has_profile_pic
- First_review
- Description
- City
- cancellation_policy
- Bed_type
- Bathrooms
- Accommodates
- Amenities
- Room_type
- Property_type
- price
- Availability_365
- Minimum_nights

## **[Part 1: Data Exploration and Recommendation System](https://github.com/pavlosdais/Airbnb-Analysis/blob/main/part1/analysis_recommendation_system.ipynb)**
In the first part of this project, we performed a series of queries on the Airbnb dataset to extract valuable insights and trends. The key tasks included:

1. **Query Analysis**:

Executed different queries to uncover various patterns and metrics, such as the most common room types, average prices by neighborhood, and the top neighborhoods by number of reviews.

2. **Recommendation System**:

Developed a recommendation system using Cosine Similarity to suggest similar properties to users based on specific criteria.

## **[Part 2: Sentiment Analysis on Airbnb Reviews](https://github.com/pavlosdais/Airbnb-Analysis/blob/main/part2/sentiment_analysis.ipynb)**
The second part of the project focused on analyzing the sentiment of Airbnb reviews using machine learning techniques. The steps involved:

1. **Annotation Process**:

Annotated the comments from Airbnb reviews based on sentiment (positive, negative, neutral) using a pretrained model: [bert-base-multilingual-uncased-sentiment](https://huggingface.co/nlptown/bert-base-multilingual-uncased-sentiment).

2. **Sentiment Analysis**:

Applied various machine learning algorithms to classify the sentiment of reviews:

- Support Vector Machine (SVM)
- Random Forest
- K-Nearest Neighbors (KNN)

The analysis was conducted using two different feature extraction methods:

- TF-IDF (Term Frequency-Inverse Document Frequency)
- Word Embeddings

## **Contributors**
- [Pavlos Ntais](https://github.com/pavlosdais)
- [Aristarchos Kaloutas](https://github.com/aristarhoskal)
