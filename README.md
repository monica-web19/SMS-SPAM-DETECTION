#  SMS Spam Detection using Machine Learning

# Project Overview
This project is an end-to-end Machine Learning system that classifies SMS messages as **Spam or Not Spam** using Natural Language Processing (NLP) techniques. It demonstrates a complete ML pipeline from data preprocessing to model training and evaluation.

#  Dataset
- SMS Spam Collection Dataset
- Contains labeled SMS messages:
  - **Not Spam (legitimate messages)**
  - **Spam (unwanted messages)**
- Total messages: ~5,500+

# Project Workflow

# 1. Data Preprocessing
- Removed unnecessary columns
- Cleaned dataset
- Converted labels into numerical format:
  - Not Spam = 0
  - Spam = 1

# Feature Engineering
- Applied TF-IDF (Term Frequency–Inverse Document Frequency)
- Converted text data into numerical feature vectors

# Model Building
- Algorithm used: **Multinomial Naive Bayes**
- Trained on 80% data and tested on 20%

# Model Evaluation
- Accuracy Score
- Confusion Matrix
- Prediction on custom messages

# Machine Learning Model
- **Algorithm:** Multinomial Naive Bayes  
- **Library:** Scikit-learn  
- **Type:** Supervised Learning (Text Classification)
- 
# Results
- Model achieved good accuracy in classifying messages correctly
- Performs well on unseen test data
- <img width="1193" height="330" alt="Screenshot 2026-06-11 135056" src="https://github.com/user-attachments/assets/6490b765-ada3-4903-a437-0b7e89849388" />

#  Sample Predictions

| Input Message | Prediction |
|------|--------|
| "Congratulations! You won a free prize" | SPAM |
| "Hey, are we meeting today?" | NOT SPAM |
| "Free entry in a cash contest" | SPAM |
| "Please send me the notes" | NOT SPAM |
<img width="1193" height="330" alt="Screenshot 2026-06-11 135056" src="https://github.com/user-attachments/assets/bdaa87c3-719b-495b-975d-1c82b6d6e36b" />

# Confusion Matrix
<img width="1279" height="476" alt="Screenshot 2026-06-11 135031" src="https://github.com/user-attachments/assets/4a306f86-d15b-4678-9fbc-8877d04eb47b" />

# Tech Stack
- Python 
- Pandas  
- NumPy  
- Scikit-learn  
- NLP (TF-IDF)

# Key Learnings
- End-to-end Machine Learning pipeline development
- Text preprocessing and NLP techniques
- Feature extraction using TF-IDF
- Model training and evaluation
- Real-world spam detection system
