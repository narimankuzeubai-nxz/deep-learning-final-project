Week 3: Deep Learning Model (LSTM)
1. Work Completed This Week

This week, I built a deep learning model for SMS spam classification using an LSTM (Long Short-Term Memory) neural network.

The goal was to improve performance compared to the baseline models from Week 2 by using a neural network that can understand sequence information in text.

2. Data Preparation for Deep Learning

To prepare the data for the LSTM model, I performed the following steps:

Tokenized the text messages using Keras Tokenizer
Converted text into sequences of integers
Applied padding to make all sequences the same length
Split the dataset into training and testing sets

These steps are required because neural networks cannot directly process raw text.

3. Model Architecture

The LSTM model consists of:

Embedding layer (to convert words into vectors)
LSTM layer (to learn sequential patterns in text)
Dropout layer (to reduce overfitting)
Dense output layer with sigmoid activation (binary classification)

Loss function: binary cross-entropy
Optimizer: Adam
Metric: accuracy

4. Training Results

The model was trained for 5 epochs.

Training Performance:
Accuracy stayed around 0.86
Loss slowly decreased but stabilized early
Test Performance:
Test Accuracy: 0.8664
5. Evaluation Results
Classification Report:
Class 0 (ham):
Precision: 0.87
Recall: 1.00
F1-score: 0.93
Class 1 (spam):
Precision: 0.00
Recall: 0.00
F1-score: 0.00
6. Observations
The model performs well on class 0 (ham messages)
However, it fails to correctly detect spam messages
The model predicts almost all samples as ham
This shows that the model is biased toward the majority class
