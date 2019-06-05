# Yelp Reviewer Toughness Classification

## Project Description
The Yelp dataset is well known in the data science community and has been the subject of numerous machine learning projects due to its size, richness, and scope. However, the majority of the analysis that's been performed on this dataset has been focused on understanding the businesses rather than the users of Yelp. For the final project for USF's Intro to Machine Learning course, our team chose to instead focus on the users by training a classification model for reviewer toughness (hard, medium, or easy) based on a corpus of their reviews.

To accomplish this goal, we joined multiple tables and manipulated the data in order to create labels for each reviewer. We then prepared the review text data for modeling by performing NLP techniques such as tokenization, lemmatization, stop word removal, and TFIDF vectorization. We trained multiple machine learning models and found that multinomial logistic regression performed the best based on our chosen evaluation metrics of recall for the easy and hard classes. *Note that neural networks were outside the scope of this intro course and therefore were not able to be used.*

## Important Links

- [Final presentation slides](yelp_deck_v2.pdf)
- [Data preprocessing notebook](yelp_data_processing.ipynb)
- [Modeling notebook](hard_easy_reviewer_model-v2.ipynb)
- [More details on Yelp dataset](yelp_deck_v2.pdf)
