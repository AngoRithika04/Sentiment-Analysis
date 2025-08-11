# Twitter Sentiment Analysis Using Artificial Intelligence

## Overview
This project focuses on **classifying Twitter posts** into **Positive, Negative, or Neutral sentiments** using **Machine Learning techniques**.  
It aims to help **businesses, researchers, and policymakers** analyze public opinion, monitor social media trends, and make **data-driven decisions**.  
The model was implemented and tested in a **Kaggle Notebook**, with **Logistic Regression** as the primary classifier.

The proposed solution leverages:
- **Logistic Regression** for effective classification
- **TF-IDF feature extraction** for text representation
- **Preprocessing techniques** such as tokenization, lemmatization, and stopword removal
- A balanced dataset to ensure fairness across sentiment categories

---

## Methodology

### 1. **Data Collection**
- Gathered tweets from **Kaggle datasets**
- Included multiple topics and sentiment categories

### 2. **Data Preprocessing**
- Removed URLs, mentions, and irrelevant symbols
- Converted text to lowercase and corrected spelling
- Applied tokenization and lemmatization
- Balanced sentiment classes to avoid bias

### 3. **Feature Extraction**
- Used **TF-IDF** to represent tweet content numerically

### 4. **Model Training**
- Implemented **Logistic Regression** for sentiment classification
- Compared with **LinearSVM** and **BernoulliNB**

### 5. **Evaluation**
- Achieved **83% accuracy**
- **Confusion Matrix**:
  - True Negative (TN): 40.94% (~32,752 instances)
  - False Positive (FP): 9.05% (~7,240 instances)
  - False Negative (FN): 8.10% (~6,480 instances)
  - True Positive (TP): 41.91% (~33,528 instances)

---

## Results
The Logistic Regression model successfully:
- Classified tweets into **Positive, Negative, and Neutral**
- Performed well in distinguishing clear sentiments like:
  - `"I hate Twitter"` → Negative
  - `"May the Force be with you"` → Positive
- Generalized well to unseen data

---

## Future Scope
- Multi-Language Sentiment Analysis
- Emotion Detection (joy, anger, sadness, etc.)
- Real-Time Sentiment Tracking
- Integration with Other Data Sources (news, forums, etc.)
- Deep Learning and Transformer-based models
- Industry-Specific Sentiment Models
- Visual Sentiment Analysis

---

## How to Run (Kaggle)
1. Open the Kaggle Notebook containing the code.
2. Upload the dataset or link to the Kaggle dataset.
3. Run preprocessing and model training cells sequentially.
4. Evaluate results using provided metrics and visualizations.

---

**Author:** Ango Rithika  
