TEXT CLASSIFICATION WITH TENSORFLOW

This project focuses on building a text classification model with TensorFlow to perform sentiment analysis on the IMDB movie reviews dataset. The task is to classify reviews as either positive or negative based on their textual content. The dataset is loaded using TensorFlow Datasets (TFDS) and split into training, validation, and test sets for proper evaluation. Preprocessing techniques are applied to clean and prepare the text data, and the model leverages pre-trained embeddings from TensorFlow Hub to capture semantic meaning more effectively. A deep learning model is then built and trained using the TensorFlow Keras API, and its performance is evaluated through metrics like accuracy and loss. This project demonstrates the complete workflow of text classification—from dataset preparation and preprocessing to training, evaluation, and interpretation of results—while showcasing the power of transfer learning in natural language processing tasks.


🔑 Key Highlights:

Uses TensorFlow Datasets (TFDS) to load the IMDB reviews dataset.
Splits data into training (60%), validation (40%), and test sets.
Implements preprocessing pipelines for text data.
Leverages pre-trained embeddings from TensorFlow Hub for better accuracy.
Builds and trains a deep learning model with Keras API.
Evaluates model performance using accuracy and loss metrics.

🎯 Objective

The main goal is to show how to:
Preprocess raw text data.
Use transfer learning with embeddings.
Train a binary classifier for sentiment analysis.
Evaluate and visualize performance.
