# Amazon-Reviews-Summarization

This project aims to generate a summary of Amazon product reviews using machine learning techniques. The dataset used for this project consists of reviews of fine foods from Amazon, spanning a period of more than 10 years and including all ~500,000 reviews up to October 2012. The reviews include product and user information, ratings, and a plain text review, and also include reviews from all other Amazon categories.

# Extractive vs. Abstractive Summarization
This project uses both extractive and abstractive summarization techniques. Extractive summarization involves selecting a subset of sentences from the original text to create a summary, while abstractive summarization involves generating new sentences that convey the same meaning as the original text.

# Models
This project tests three different models of increasing complexity - Simple LSTM, Stacked LSTM, Attention with Stacked LSTM. These models use deep learning techniques to analyze the reviews and generate a summary. The models are trained on a subset of the dataset and evaluated using the remaining data.

# Dataset
The dataset used for this project includes 568,454 reviews, 256,059 users, and 74,258 products. The data spans a period of more than 10 years, from Oct 1999 to Oct 2012. The dataset includes the following columns: Id, ProductId, UserId, ProfileName, HelpfulnessNumerator, HelpfulnessDenominator, Score, Time, Summary, Text.

# How to Run
Clone this repository to your local machine.
Navigate to the project directory in your terminal.
Run pip install -r requirements.txt to install the required packages.
Run the Jupyter notebook Amazon_Reviews_Summarization.ipynb to train and evaluate the models.
Future Work
Experiment with other deep learning techniques for summarization
Incorporate user and product information into the models
Test the models on other datasets to evaluate their generalizability
