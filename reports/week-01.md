Week 1: Dataset Selection and Exploration
1. Work Completed This Week

This week, I selected and explored the SMS Spam Classification dataset.
The dataset contains 5572 SMS messages with two columns:

Category: shows if a message is "spam" or "ham"
Message: the text content of the SMS

I loaded the dataset using pandas and checked its structure, size, and basic information.

2. Dataset Description

The dataset is a real-world SMS spam collection dataset.
It is used for text classification tasks.

Total samples: 5572 messages
Features: 2 columns (Category, Message)
Task type: Binary text classification
Output: spam or ham
3. Exploratory Data Analysis (EDA)

I performed basic data exploration:

Checked number of rows and columns
Checked for missing values (none found)
Analyzed class distribution (spam vs ham)
Observed that the dataset is imbalanced (more ham than spam)
4. Data Understanding
The input data is text (SMS messages)
The output labels are categorical:
"ham" = normal message
"spam" = unwanted message

This dataset is suitable for Natural Language Processing (NLP) and deep learning models like LSTM or GRU.
