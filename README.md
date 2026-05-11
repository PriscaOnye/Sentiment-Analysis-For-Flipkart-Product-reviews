# Sentiment-Analysis-For-Flipkart-Product-reviews
Flipkart Product Sentiment Analysis
This project performs sentiment analysis on Flipkart product reviews using Natural Language Processing (NLP) and Machine Learning. The goal is to automatically classify customer feedback into Positive, Negative, and Neutral categories to monitor customer satisfaction.

🚀 Interactive Notebook
You can view and run the full code, including data preprocessing and visualizations, directly on [Google Colab: Open in Google Colab](https://colab.research.google.com/drive/1yEPd3ZLYiX-L-WGp_xFIMUMGQVlHUVXa?usp=sharing)

📊 Project Overview
1. Exploratory Data Analysis (EDA)
I identified different language markers across sentiment groups:

Positive: Characterized by terms such as "best," "nice," and "quality."

Negative: Centered on "bad," "worst," and "waste."


2. Machine Learning Model
I implemented a Logistic Regression model using TF-IDF Vectorization to transform textual data into numerical features.

Overall Accuracy: 93.5%

Precision (Positive): 96%

Precision (Negative): 87%

While the neutral class remains a challenge due to class imbalance (fewer training examples), the system is highly reliable for identifying happy or unhappy customers.

🛠️ Tech Stack
Language: Python

Libraries: Pandas, Scikit-learn, Matplotlib, Seaborn, WordCloud

Vectorization: TF-IDF (Term Frequency-Inverse Document Frequency)

Algorithm: Logistic Regression

📁 Dataset
The project utilizes the Flipkart Product Customer Reviews Kaggle dataset, containing over 100,000 reviews. Preprocessing included standardizing text, handling missing values, and lemmatization.
