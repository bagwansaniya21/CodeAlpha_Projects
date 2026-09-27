# 💬 AskMate – FAQ Chatbot

A local FAQ chatbot built with Python, NLP preprocessing, TF-IDF and cosine similarity.

## Features
- Attractive dark-mode GUI
- FAQ knowledge base
- Text cleaning/preprocessing
- TF-IDF vectorization
- Cosine similarity matching
- Confidence display
- No internet required

## Run
```bash
pip install -r requirements.txt
python app.py
```

## How it works
1. FAQ questions are cleaned.
2. TF-IDF converts questions into numerical vectors.
3. The user's question is converted into the same vector space.
4. Cosine similarity is calculated.
5. The FAQ with the highest similarity is returned.
