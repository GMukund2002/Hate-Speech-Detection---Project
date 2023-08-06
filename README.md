# Hate Speech Detection - Project
 "Hate Speech Detection project aims to build a machine learning model to identify hateful language in social media tweets, promoting a safer and more inclusive online community."

# Introduction
Hate Speech Detection is a project aimed at developing a machine learning model that can accurately detect hate speech in social media tweets. Hate speech refers to language that expresses hatred, discrimination, or prejudice against a particular group or individual based on their race, ethnicity, religion, gender, sexual orientation, or other personal characteristics. The objective of this project is to build a classifier that can automatically distinguish between tweets containing hate speech and those that do not, in order to create a safer and more inclusive online community.

# Dataset
The project utilizes the Kaggle Twitter Sentiment Analysis dataset provided by Analytics Vidhya. The dataset contains over 31,000 tweets that have been labeled as either "hateful" or "non-hateful". The dataset has been preprocessed to remove URLs, user mentions, and other irrelevant information. It includes a binary label indicating whether the tweet is hateful (1) or non-hateful (0).

# Technologies Used
Python
Jupyter Notebook
Transformers library
Google API Python Client
Pandas, NumPy, Matplotlib, Seaborn
NLTK (Natural Language Toolkit)
WordCloud, PIL (Python Imaging Library)

# Project Structure
The project is structured as follows:

Data Preparation:
Importing necessary libraries
Loading the dataset from CSV files
Checking for any NULL values in the dataset
Data visualization to understand the distribution of labels
Data Pre-processing and Cleaning:

Text cleaning by removing HTML tags, emojis, punctuation, and special characters
Tokenization and stemming using NLTK library
Removing stop words and rare words
Lemmatization to convert words to their base form
Exploratory Data Analysis:

Data visualization to understand the distribution of tweets' lengths
Word cloud generation for hateful and non-hateful tweets
RoBERTa Model:

Importing RoBERTa model and tokenizer from Transformers library
Encoding the input text to IDs and attention masks
Creating the RoBERTa model architecture with dense layers
Training and evaluating the RoBERTa model
Visualizing the model accuracy and loss
Tokenization & Vectorization:

Splitting the data into train and test sets
Tokenizing and cleaning the text data using word tokenizer
Vectorizing the text data using TF-IDF (Term Frequency-Inverse Document Frequency)
Oversampling using SMOTE:

Addressing the imbalanced dataset problem using SMOTE
Training various classifiers (Logistic Regression, Naive Bayes, Random Forest, SVM) with SMOTE
Conclusion:

Analyzing the performance of different classifiers
Selecting the best model for hate speech detection

# Author
This project is developed by G Mukund. Feel free to contact me at mukund.1@iitj.ac.in for any questions or feedback.

# License
This project is licensed under the MIT License.