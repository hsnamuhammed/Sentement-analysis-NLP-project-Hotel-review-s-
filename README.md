# Hotel Reviews Data Analysis in Europe
This project involves analyzing and visualizing hotel reviews from various European hotels. The main objectives include data cleaning, feature engineering, and sentiment analysis to better understand the factors impacting hotel review sentiments. Here is an overview of the steps covered in the code:

## Data Cleaning and Preprocessing

Text reviews are preprocessed by converting to lowercase, removing punctuation, numbers, and stop words.
Lemmatization is applied to normalize words.
## Feature Engineering

New columns are added to capture information such as the number of characters and words in each review.
Sentiment analysis is performed on the reviews using the NLTK SentimentIntensityAnalyzer, adding features for positive, neutral, negative, and compound sentiment scores.
TF-IDF (Term Frequency-Inverse Document Frequency) vectors are generated for frequently occurring words in the reviews to capture relevant keywords.
## Model Training and Evaluation

The reviews are labeled based on sentiment polarity (positive or negative) and split into training and testing sets.
A Random Forest Classifier is trained on the feature-engineered dataset to classify reviews as positive or negative.
Model performance is evaluated using ROC-AUC to assess the classifier's ability to distinguish between positive and negative reviews
## Visualization

Distribution plots and ROC curves are generated to visualize sentiment distributions and evaluate model performance.
This project offers insights into customer sentiments for hotels across Europe, potentially informing service improvement strategies for hospitality businesses.
