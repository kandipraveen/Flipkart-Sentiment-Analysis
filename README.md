# Flipkart Sentiment Analysis 🛒📊

This project performs sentiment analysis on real-time Flipkart product reviews to classify customer feedback as **Positive** or **Negative** and identify customer pain points.

## 📌 Project Overview
- Product: **YONEX MAVIS 350 Nylon Shuttle**
- Total Reviews: **8,518**
- Platform: Flipkart
- Task: Sentiment Classification & Deployment

## 🧠 Objective
- Classify customer reviews into positive or negative
- Identify dissatisfaction reasons from negative reviews
- Deploy a real-time sentiment prediction web app

## 🗂 Dataset
The dataset contains:
- Reviewer Name
- Rating
- Review Title
- Review Text
- Place of Review
- Date of Review
- Up Votes
- Down Votes

Sentiment Labeling:
- Rating ≥ 4 → Positive
- Rating ≤ 2 → Negative
- Rating = 3 → Removed

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- NLTK
- Scikit-learn
- TF-IDF
- Streamlit
- AWS EC2

## 🔍 NLP Pipeline
1. Text Cleaning
2. Stopword Removal
3. Lemmatization
4. Feature Extraction (BoW, TF-IDF)
5. Model Training (Logistic Regression)
6. Evaluation using F1-Score

## 🚀 Model Deployment
A Streamlit web application is built to predict sentiment for user-input reviews and deployed on AWS EC2.

## 📁 Project Structure

Flipkart-Sentiment-Analysis/
│
├── data/
│ └── yonex_mavis_350_reviews.csv
│
├── notebooks/
│ └── sentiment_analysis.ipynb
│
├── src/
│ ├── preprocessing.py
│ ├── train_model.py
│ └── utils.py
│
├── app/
│ └── app.py
│
├── models/
│ ├── sentiment_model.pkl
│ └── vectorizer.pkl
│
├── requirements.txt
├── README.md
└── .gitignore

⭐ Acknowledgement

This project uses real-time Flipkart review data provided as part of an academic assignment for sentiment analysis and NLP learning
