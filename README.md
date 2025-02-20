# Sentiment Analysis on Movie Reviews
## 📌 Project Overview
This project implements a Sentiment Analysis model using Recurrent Neural Networks (RNN) with `Gated Recurrent Unit (GRU)` to classify movie reviews as positive or negative. The model is trained on a dataset of movie reviews, leveraging word embeddings and deep learning techniques to improve classification accuracy.

## 📂 Dataset

The dataset consists of labeled movie reviews, where each review is categorized into one of **five sentiment classes**:

0: Negative

1: Somewhat Negative

2: Neutral

3: Somewhat Positive

4: Positive
## 🏋️‍♂️ Model Architecture

1. The model is built using TensorFlow/Keras and consists of the following layers:

2. **Embedding Layer**: Converts words into dense vectors.

3. **GRU Layers**: Captures long-term dependencies in text.

4. **Fully Connected Layer**: Classifies the review as positive or negative.

5. **Softmax Activation**: Outputs class probabilities.

## 📈 Results
The model achieves **63.4%** accuracy on the test set. 

## 🔍 Kaggle Competition
[Kaggle link](https://www.kaggle.com/competitions/sentiment-analysis-on-movie-reviews/overview)
