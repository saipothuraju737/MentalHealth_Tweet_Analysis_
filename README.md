🧠 Mental Health Analysis on Tweets

A machine learning and Natural Language Processing (NLP) project that analyzes tweet-like text to identify mental health-related patterns, including depression-related language.

📌 Problem Statement

Mental health concerns are often discussed through text on social media. Analyzing this text using NLP can help identify language patterns associated with different mental health categories.

This project uses machine learning to classify text and display relevant support suggestions for depression-related predictions.

🎯 Objectives

Analyze text using Natural Language Processing.

Classify text into the categories supported by the trained model.

Provide relevant support suggestions for depression-related predictions.

Demonstrate how machine learning can be applied to mental health text analysis.

✨ Features

📝 Text input for analysis

🤖 Machine learning-based text classification

🔤 TF-IDF text feature extraction

📊 Prediction results displayed through a web interface

💙 Support suggestions for depression-related predictions

🛡️ Safety-oriented information for concerning predictions

🛠️ Tech Stack

Programming Language

Python

Machine Learning & NLP

Scikit-learn

TF-IDF Vectorizer

Natural Language Processing (NLP)

Web Application

Flask

HTML

CSS

JavaScript

Model and Data Processing

Pandas

NumPy

Joblib / Pickle

📂 Project Structure

MentalHealth_Analysis_on_tweets-main/
├── app.py
├── flask_app.py
├── requirements.txt
├── requirements-web.txt
├── mental_health_model.pkl
├── tfidf_vectorizer.pkl
├── label_encoder.pkl
├── templates/
├── static/
└── README.md

Note: The structure above is representative. Adjust it to match the actual files in your repository.

⚙️ Local Setup

Prerequisites

Python installed

Git

Visual Studio Code (recommended)

1. Clone the repository

git clone YOUR_GITHUB_REPOSITORY_URL
cd YOUR_PROJECT_FOLDER

2. Create a virtual environment

python -m venv .venv

Activate it on Windows PowerShell:

.\.venv\Scripts\Activate.ps1

3. Install dependencies

If you are running the Flask application:

python -m pip install -r requirements-web.txt

Alternatively, install the dependencies listed in requirements.txt if you are setting up the other application entry point.

4. Run the application

python flask_app.py

Open this address in your browser:

http://127.0.0.1:5000

🔄 Workflow

User enters text into the web interface.

The text is transformed into numerical features using the saved TF-IDF vectorizer.

The trained machine learning model predicts a category.

The application displays the prediction and any applicable support suggestions.

⚠️ Limitations

Predictions depend on the training dataset and model quality.

Text classification may produce incorrect results.

The application does not understand a person's complete circumstances.

It is an educational project, not a medical diagnosis or a substitute for professional support.

🚀 Future Improvements

Improve model performance with more representative datasets.

Evaluate precision, recall, and F1-score for each class.

Improve the user interface and accessibility.

Add multilingual text support.

Strengthen privacy and safety features.

👨‍💻 Author

pothuraju sai

GitHub: saipothuraju737.

📄 License

No license has been selected for this repository yet.
