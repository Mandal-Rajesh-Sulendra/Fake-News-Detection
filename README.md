📰 Fake News Detection App

Author: Mandal Rajesh Sulendra
Role: B.Tech CSE (AI & ML) Student


---

Project Overview

In today's fast-paced world, misinformation spreads rapidly across social media and online platforms. This project presents a Fake News Detection system that helps users instantly identify whether a news article is real or fake using machine learning.

Using Natural Language Processing (NLP) techniques and Logistic Regression, the app analyzes the content of news articles and provides a confidence score along with the prediction.

> Goal: Equip users with a smart tool to combat fake news and make informed decisions.




---

Key Features

Interactive User Interface: Built with Streamlit for a user-friendly experience.

Real-Time Predictions: Detects fake or real news instantly.

Confidence Scores: Provides a probability percentage to indicate model certainty.

Reusable Model: Saves trained model and TF-IDF vectorizer for fast loading.

Scalable: Can handle multiple news inputs efficiently.



---

How It Works

1. Input: Users enter a news article or a sentence.


2. Text Preprocessing: Converts text to lowercase, removes stop words, and vectorizes using TF-IDF.


3. Prediction: Logistic Regression model predicts if the news is Fake (0) or Real (1).


4. Output: Shows a clear, human-readable prediction with confidence.




---

Tech Stack & Keywords

Programming Language: Python

Framework: Streamlit (Interactive Web App)

Machine Learning: Logistic Regression

NLP: TF-IDF Vectorizer, Text Preprocessing

Data Handling: Pandas, LabelEncoder

Persistence: Joblib (Saving model and vectorizer)

Keywords: Fake News Detection, Machine Learning, NLP, Streamlit App, Logistic Regression, TF-IDF, Real-time Prediction, Data Science



---

Usage

1. Clone the repository:



git clone https://github.com/yourusername/fake-news-detection.git

2. Install dependencies:



pip install -r requirements.txt

3. Run the app:



streamlit run app.py

4. Enter any news text in the text area and click Predict to see results.




---

Demo



> Users can easily paste news text, and the app highlights whether the news is FAKE 🚨 or REAL ✅ with confidence.




---

Why This Project Matters

Helps combat misinformation online.

Useful for journalists, researchers, and everyday users.

Demonstrates practical application of Machine Learning and NLP in real-world scenarios.



---

Future Enhancements

Integrate more advanced models like BERT or RoBERTa for higher accuracy.

Add a browser extension to detect fake news on-the-go.

Support multiple languages for global reach.

Visualize news credibility trends over time.



