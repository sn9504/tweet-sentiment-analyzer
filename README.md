# Tweet Sentiment Analyzer

This is a Streamlit-based web application for classifying tweets into **Positive**, **Negative**, or **Neutral** sentiments using a deep learning model trained on GloVe embeddings with LSTM.

## 🚀 Features

- Pretrained LSTM model with GloVe-200D embeddings
- Real-time tweet classification
- Streamlit-based user interface
- Tokenizer + model reuse for fast inference

## 📁 Files

- `app.py` – Streamlit interface
- `glove_lstm_sentiment_trained_full.h5` – Pretrained Keras model (LSTM)
- `tokenizer.pkl` – Tokenizer for input preprocessing
- `cleaned_tweets.csv` – Optional data source
- `requirements.txt` – All required Python packages

## 📦 Installation

```bash
pip install -r requirements.txt
streamlit run app.py
```

## 🧠 Model Details

- Embeddings: GloVe Twitter 200D
- Architecture: Embedding → BiLSTM → Dense → Dropout → Softmax
- Trained on ~19,000 labeled tweets

## 🖥 Demo

To try the app locally:
```bash
streamlit run app.py
```

## 🤝 License

Open-sourced for educational and non-commercial use. Attribution appreciated.