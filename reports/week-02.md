Week 2: Data Preprocessing and Baseline Models
1. Work Completed This Week

This week, I prepared the dataset for modeling and built baseline machine learning models for SMS spam classification.

I performed text vectorization using TF-IDF and split the dataset into training and testing sets.

After preprocessing, I trained two baseline models:

Logistic Regression
Naive Bayes
2. Data Preparation

The dataset contains SMS messages labeled as:

0 = ham (normal message)
1 = spam (unwanted message)

Steps performed:

Loaded cleaned dataset from Week 1
Extracted input features (Message) and labels (Category)
Converted text into numerical form using TF-IDF
Split data into training (80%) and testing (20%) sets

Train size: 4457 samples
Test size: 1115 samples

3. Baseline Models

Two baseline models were used:

1. Logistic Regression

A linear classification model used for text classification tasks.

2. Naive Bayes

A probabilistic model often used for NLP tasks like spam detection.

4. Results
Logistic Regression Results
Accuracy: 0.9695
Spam recall: 0.77
Spam precision: 1.00
F1-score (spam): 0.87
Naive Bayes Results
Accuracy: 0.9713
Spam recall: 0.79
Spam precision: 1.00
F1-score (spam): 0.88
5. Model Comparison
Model	Accuracy
Logistic Regression	0.9695
Naive Bayes	0.9713

Naive Bayes performed slightly better than Logistic Regression in terms of accuracy and recall.
