# Text Generation using LSTM in TensorFlow

This project demonstrates a basic NLP pipeline for text generation using an LSTM model built with TensorFlow and Keras.
- Kaggle Dataset : https://www.kaggle.com/datasets/ronikdedhia/next-word-prediction/
## Features

- Load and preprocess raw text data
- Tokenize and create n-gram sequences
- Build and train an LSTM model
- Predict top 5 next-word suggestions based on seed input
- Visualize training and validation loss and accuracy

## Installation

Install the required packages:

```bash
pip install tensorflow pandas numpy scikit-learn spacy matplotlib seaborn
python -m spacy download en_core_web_sm
