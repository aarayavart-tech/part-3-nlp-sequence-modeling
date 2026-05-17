# NLP and Sequence Modeling Mini Project

## Overview
This project builds a basic NLP pipeline using a customer support text classification dataset. The aim is to compare traditional text vectorization methods with sequence-based deep learning concepts.

## Dataset
The dataset used is `customer_support_text_classification.csv`.

### Input Feature
- customer_message

### Target Label
- sentiment_label

Classes:
- positive
- neutral
- negative

## Tasks Completed

### Task 1: Dataset Understanding
- Loaded dataset
- Checked number of records
- Identified target labels
- Displayed sample text
- Calculated average text length
- Visualized class distribution

### Task 2: Text Preprocessing
- Converted text to lowercase
- Removed special characters
- Tokenized text
- Removed stopwords

### Task 3: Text Vectorization
- Applied TF-IDF vectorization
- Converted text into numerical vectors

### Task 4: Baseline Model
- Trained Logistic Regression model
- Evaluated using accuracy and classification report

### Task 5: Sequence Model
- Created LSTM-based sequence model
- Used tokenizer and padded sequences
- Designed architecture for sequence processing

### Task 6: Attention and Transformer Reflection
- Explained RNN limitations
- Explained LSTM memory mechanism
- Discussed attention
- Discussed transformer importance

## Files Included

- notebook.ipynb
- requirements.txt
- results/model_evaluation.png
- results/sample_predictions.txt

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- NLTK
