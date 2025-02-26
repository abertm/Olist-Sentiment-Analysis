
# Olist-Sentiment-Analysis

## Project Overview

This project aims to perform sentiment analysis on customer reviews from the Brazilian E-Commerce Public Dataset by Olist. Using Exploratory Data Analysis (EDA) and Machine Learning (ML). We analyze customer feedback to understand sentiment trends and improve customer experience.


## Structure

│-- data/                   # Raw and processed datasets
│-- notebooks/              # VSC notebooks for analysis
│-- src/                    # Scripts for data preprocessing & modeling
│   │-- preprocess.py       # Data cleaning and processing
│   │-- train_model.py      # Model training
│-- results/                # Visualizations, reports, and model outputs
│-- requirements.txt        # Dependencies list
│-- README.md               # Project overview (already created)
│-- LICENSE                 # Open-source license (e.g., MIT)
│-- .gitignore              # Files to exclude from Git tracking


## Dataset

Source: Kaggle (Brazilian E-Commerce Public Dataset by Olist)

Key Files:

olist_customers_dataset.csv,
olist_geolocation_dataset.csv,
olist_order_items_dataset.csv,
olist_order_payments_dataset.csv,
olist_order_reviews_dataset.csv,
olist_orders_dataset.csv,
olist_products_dataset.csv,
olist_sellers_dataset.csv,
olist_category_name_dataset.csv


## Project Workflow

1. Data Preprocessing

Load and clean the dataset

Handle missing values and duplicates

Merge relevant tables

2. Exploratory Data Analysis (EDA)

Understand the distribution of review scores

Identify trends and correlations

Visualize key insights using graphs

3. Machine Learning Model

Train classifiers (Logistic Regression, Random Forest, LSTM, etc.)

Evaluate model performance using accuracy, precision, recall, and F1-score

## Requirements

To run this project, install the following dependencies:
pandas,
numpy,
matplotlib,
seaborn,
nltk,
scikit-learn,
tensorflow

## Results & Insights

- Distribution of customer sentiment

- Key factors affecting sentiment trends

- Model performance evaluation

## Future Improvements

- Fine-tune deep learning models

- Deploy as a web app for real-time analysis

- Expand to multilingual sentiment analysis

## Contributors

Bárbara Gamarra,
Gabriel Cordoba,
Macarena Mandalari,
Andrés Bertero


## License

This project is licensed under the MIT License.



