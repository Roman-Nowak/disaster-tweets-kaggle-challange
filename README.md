# Disaster tweets Kaggle classification challenge

Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).<br>

In this competition, we are challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t.<br>

The data is taken from the Natural Language Processing with Disaster Tweets competition on Kaggle<br>
https://www.kaggle.com/competitions/nlp-getting-started/overview

## Project structure outline
1. Problem description & project motivation
2. Verbal description of the data
3. Imports
4. Loading data
5. Exploratory data analysis
    * Data inspection
    * Counting unique values
    * Counting missing values
6. Data visualization
    * Target variable distribution
    * Tweet length distribution
7. Dealing with missing values
8. Data preparation
    * Cleaning the data
    * Vectorizing the data
    * Combining tf-idf and count vectorization
    * Tf-idf vectorizing joined columns
9. Training models
    * Models trained on combined tf-idf and count vectorized features
        * Logistic regression
        * Multinomial Naive Bayes
    * Models trained on tf-idf vectorized joined columns features
        * Logistic regression
        * Multinomial Naive Bayes
10. Model prediction comparison
11. Conclusion