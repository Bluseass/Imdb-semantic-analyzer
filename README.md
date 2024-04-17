# IMDb Sentiment Analysis with Transformer

## Overview

This repository contains code for sentiment analysis on the IMDb dataset using a Transformer model implemented with TensorFlow and Keras.

### Components

1. **Data Loading and Preprocessing**: IMDb dataset is loaded and preprocessed. Sequences are padded to a maximum length.

2. **Tokenization**: Text data is tokenized using the Tokenizer provided by Keras.

3. **Transformer Model**: A Transformer model is constructed with multiple layers, each containing multi-head self-attention and feed-forward neural network blocks.

4. **Training**: The model is compiled and trained on the IMDb dataset.

5. **Text Analysis Widget**: A widget is provided for users to input text for sentiment analysis. The model predicts whether the input text has a positive or negative sentiment.

## Dependencies

- TensorFlow 2.x
- NumPy
- ipywidgets (for the interactive text analysis widget)

## Usage

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
2. **Install Dependencies:**:

   ```bash
   pip install -r requirements.txt

**Run the Code**:

Execute the script containing the code. Ensure you have access to a GPU if training the model.

**Use the Text Analysis Widget**:

After running the code, an interactive widget will be displayed where you can input text for sentiment analysis. Click the "Analyze" button to get the sentiment analysis result.

## Code Structure

- `transformer_model.py`: Defines the Transformer model architecture.
- `train.py`: Script for training the model on the IMDb dataset.
- `text_analysis_widget.py`: Contains the code for the interactive text analysis widget.

## Acknowledgments

- The Transformer model architecture is inspired by the original paper "Attention is All You Need" by Vaswani et al.
- IMDb dataset is obtained from Keras datasets.
