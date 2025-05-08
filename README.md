# Depression Detection using Deep Learning with Emoji Integration

This project aims to detect depression from user-generated text on social media using a hybrid deep learning model. It combines sentiment-aware emoji embeddings with BERT-based language representations to improve detection accuracy, particularly in multilingual and informal settings.

## 📌 Features
- Emoji sentiment analysis integrated into text features
- BERT (Bidirectional Encoder Representations from Transformers) for contextual embedding
- Bidirectional LSTM with attention mechanism
- Handles multilingual data
- Early stopping and learning rate scheduling for optimal training

## 🧠 Model Architecture
- BERT Encoder for text
- Emoji-to-score mapping based on sentiment polarity
- Concatenated features passed through BiLSTM + Attention
- Final classification using softmax output

## 📊 Results
The model demonstrates strong performance in binary classification of depressive and non-depressive content using a curated dataset of social media posts.

## 🛠 Requirements
- Python 3.7+
- TensorFlow
- HuggingFace Transformers
- Pandas, NumPy, Matplotlib, Seaborn
- TQDM

Install them via:
pip install -r requirements.txt
