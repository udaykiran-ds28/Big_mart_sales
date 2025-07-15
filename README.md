#Drug Recommendation System using Sentiment Analysis
Project Title:
Drug Recommendation System based on Sentiment Analysis of Drug Reviews using Machine Learning

📄 Project Description:
This project aims to build a medicine recommender system that suggests the most suitable drugs for specific health conditions using patient reviews. By applying Natural Language Processing (NLP) and Machine Learning, the system predicts the sentiment of each review and uses that information, along with review usefulness, to recommend top drugs.

🎯 Objective:
To reduce the workload of healthcare professionals

To support patients in making better medication choices

To apply sentiment analysis for recommending top-rated drugs

🧰 Technologies Used:
Python

Pandas, NumPy – Data processing

Matplotlib, Seaborn – Visualization

Scikit-learn – Machine Learning algorithms

NLTK – NLP preprocessing

TextBlob – Polarity feature extraction

SMOTE – Handling imbalanced data

Word2Vec, TF-IDF, Bag of Words – Feature vectorization

⚙️ System Architecture:
The system includes 4 key stages:

Data Preparation & Cleaning

Feature Extraction (TF-IDF, Word2Vec, Manual)

Model Training (SVM, Logistic Regression, Decision Tree, etc.)

Drug Recommendation Based on Sentiment + Usefulness Score

🔍 Dataset Used:
Source: Drugs.com Review Dataset

Total Records: 215,063 reviews

Columns: Drug Name, Condition, Review Text, Rating, Usefulness Count, Review Date

📈 Model Evaluation Metrics:
Accuracy

Precision

Recall

F1 Score

ROC-AUC

Best performance achieved with Linear SVC + TF-IDF, giving 93% accuracy.

🧪 Feature Engineering Includes:
Usefulness count

Sentiment polarity (TextBlob)

Date-based features (day, month, year)

Cleaned vs Uncleaned polarity

N-gram ranges (1,2) for vectorizers

🧮 ML Algorithms Used:
Logistic Regression

SVM (LinearSVC)

Naive Bayes

Random Forest
