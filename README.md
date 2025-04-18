# 🎬 IMDb Sentiment Analysis (Colab + Gradio UI)

This project performs sentiment analysis on movie reviews using the IMDb dataset. It is designed to be run entirely in Google Colab and includes an interactive user interface built with Gradio.

---

## ✅ Features

- Uses the IMDb dataset from Kaggle (50K reviews)
- Cleans and preprocesses text data
- Builds and trains an LSTM-based neural network using TensorFlow
- Saves the trained model and tokenizer
- Provides a Gradio-powered UI directly within the Colab notebook for real-time predictions

---

## 🚀 How to Use

1. Upload your Kaggle API key (`kaggle.json`) to Colab.
2. Download and load the IMDb dataset.
3. Run the cells to preprocess data and train the sentiment analysis model.
4. Save the model and tokenizer for future use.
5. Launch the Gradio UI to test sentiment predictions in real-time inside the notebook.

---

## 🧠 Model Overview

- Embedding layer for word vector representation
- LSTM layer for sequential understanding
- Dense layers for final classification
- Outputs binary sentiment: Positive or Negative

---

## 📦 Tools & Libraries

- Google Colab
- TensorFlow / Keras
- Gradio
- Kaggle API
- Pandas, Numpy, Regex

---

## 📎 Dataset

- IMDb Movie Reviews Dataset  
- Source: [Kaggle - lakshmi25npathi/imdb-dataset-of-50k-movie-reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

---

## 🎯 Outcome

At the end of the notebook, you can input any movie review and get instant sentiment feedback through a simple and intuitive UI — all without leaving Colab.

