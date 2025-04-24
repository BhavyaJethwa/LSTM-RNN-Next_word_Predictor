# LSTM-RNN-Next_word_Predictor

This project implements a **Next Word Prediction** model using **LSTM (Long Short-Term Memory)**, a type of **Recurrent Neural Network (RNN)**. The model is trained on a text dataset and can predict the next word given a sequence of words. It’s designed for natural language processing (NLP) tasks.

## Project Overview

The model is trained to predict the next word in a sequence based on a training dataset. Using LSTM cells helps in capturing long-term dependencies in the input text, making the model more effective in language modeling.

### Key Features
- **LSTM-based Architecture**: Uses LSTM layers to capture sequential dependencies in text.
- **Word Embeddings**: Converts text to numerical representation for training.
- **Next Word Prediction**: The model predicts the next word in a sequence of words based on the context.

## Requirements

Make sure you have the following installed to run this project:

- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- Pandas

You can install these dependencies using `pip`:

```bash
pip install tensorflow numpy matplotlib pandas
