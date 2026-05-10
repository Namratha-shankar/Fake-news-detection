# Fake-news-detection
# Fake News Detection using NLP

This project detects whether a news article is REAL or FAKE using Natural Language Processing (NLP) and Deep Learning techniques.

## Technologies Used
- Python
- TensorFlow
- NLP
- NumPy
- Pandas
- Scikit-learn
- Google Colab

## Features
- Text preprocessing and tokenization
- Word embedding using GloVe
- Deep learning model using:
  - Embedding Layer
  - Conv1D
  - LSTM
- Predicts whether news is real or fake

## Dataset
Dataset used: Fake and Real News Dataset (`news.csv`)

## Model Architecture
- Embedding Layer
- Dropout Layer
- Conv1D Layer
- MaxPooling1D
- LSTM Layer
- Dense Output Layer

## How to Run
1. Upload `news.csv` dataset
2. Run the notebook in Google Colab
3. Train the model
4. Enter custom news text for prediction

## Sample Prediction
Input:
"Karry to go to France in gesture of sympathy"

Output:
This news is True

## Future Improvements
- Improve accuracy with larger dataset
- Add Flask web interface
- Deploy as a web application

## Author
Namratha H S
