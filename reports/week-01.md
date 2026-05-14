# Project Proposal

## 1. Project Title
Sentiment Classification of Russian Bank Reviews

## 2. Problem Statement
**What problem are you trying to solve?** The goal of this project is to automatically classify customer reviews of banks into "Positive" or "Negative" sentiments. 
**Why is this problem useful or interesting?** Banks receive thousands of reviews and feedback messages daily. Automating the sentiment analysis allows businesses to monitor customer satisfaction in real-time, quickly identify critical issues, and route negative feedback to the support team for immediate resolution.
**What will the model predict or generate?** Given a text sequence (a customer's review in Russian), the model will predict a binary sentiment label: `Positive` or `Negative`.

## 3. Dataset
* **Dataset name:** Russian Bank Reviews Sentiment Dataset
* **Dataset source link:** [Provide the link to the Kaggle/source dataset here]
* **Number of examples:** ~14,000 training examples and ~6,000 test examples.
* **Input features:** `Text` (String) - the raw text of the customer review in Russian.
* **Target labels:** `Score` (String/Binary) - 'Positive' or 'Negative'.
* **Data format:** TSV (Tab-Separated Values) format saved as `.csv` files.
* **License:** [Specify if known, otherwise write "Unknown / Educational use"].

## 4. Planned Method
* **Baseline:** TF-IDF Vectorization followed by a Logistic Regression or Naive Bayes classifier.
* **Deep learning model:** A Recurrent Neural Network (LSTM or GRU) with an Embedding layer, or fine-tuning a pre-trained Transformer model (e.g., RuBERT - Russian BERT).
* **Loss function:** Binary Crossentropy.
* **Evaluation metrics:** Accuracy, F1-score (macro/micro), and Confusion Matrix.
* **Train/validation/test split plan:** The provided `train.csv` will be split into 80% for training and 20% for validation. The separate `test.csv` file will be used for final predictions and evaluation.

## 5. Expected Challenges
* **Russian Language Morphology:** Russian is highly inflected, which might require complex tokenization, lemmatization, or subword tokenization (BPE) to avoid huge vocabulary sizes.
* **Sequence Length:** Some reviews are very long and detailed, which may lead to truncation of important context or high memory consumption during training.
* **Class Imbalance:** Bank reviews often skew negative (people complain more often than they praise), which might require class weighting or oversampling.
* **Sarcasm and Context:** Customers often use sarcasm (e.g., "Great bank, they blocked my card for no reason"), which is difficult for simple models to capture.

## 6. Weekly Plan

| Week | Planned Work | Expected Output |
|------|--------------|-----------------|
| **Week 1** | Dataset selection, repository setup, exploratory data analysis | Proposal, README, dataset summary, Week 1 report |
| **Week 2** | Data preprocessing, tokenization, train/validation split, baseline model | Baseline results and Week 2 report |
| **Week 3** | Deep learning model training (RNN/Transformer) and hyperparameter tuning | Model results, loss curves, error analysis, Week 3 report |
| **Week 4** | Improvements, final evaluation on test set, final report and presentation | Final code, final report, slides/demo, Week 4 report |
