Week 1 Report: Dataset Selection, Repository Setup and Exploratory Data Analysis (EDA)
Goals and Completed Tasks:
Dataset Selection:
The dataset chosen for the project is the Spam Emails dataset, available on Kaggle (Spam Emails Dataset).
The dataset consists of email text messages classified as Spam or Non-Spam (Ham).
This dataset is suitable for text classification tasks, which is the focus of the project, and it provides a practical example of applying deep learning to text data.

Repository Setup:

Exploratory Data Analysis (EDA):
Performed an initial exploration of the dataset to understand its structure:
Message: The text of the email.
Category: The label indicating whether the email is Spam or Non-Spam.
Checked for missing values or anomalies in the dataset. No missing values were found.
Observed the class distribution: the dataset is imbalanced, with more Non-Spam emails than Spam emails. This could affect model performance, especially for the minority class (Spam).
Identified the need for data preprocessing, including text tokenization and label encoding.

Creation of README File:
The README.md file was created with the following key information:
A description of the project (Spam vs. Non-Spam email classification).
The source and details of the dataset.
Overview of the steps that will be undertaken in the project.
Information on the methods and technologies to be used.

Plan for Next Week:
Data Preprocessing:
Tokenize the email text and convert it into a vector representation (e.g., using TF-IDF or Word Embeddings).
Convert the Category labels (Spam, Non-Spam) into binary format.
Split the data into training, validation, and test sets.
Baseline Model Implementation:
Implement a simple neural network model (e.g., MLP) for binary classification of Spam and Non-Spam emails.
Evaluate the model's performance using basic accuracy metrics.
Documentation of Progress:
Prepare the second-week report, outlining the steps taken for data preprocessing and the initial model implementation.
