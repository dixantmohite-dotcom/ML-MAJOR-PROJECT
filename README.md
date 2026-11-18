# Movie Review Sentiment Analysis (DistilBERT Fine-Tuning)

This project fine-tunes a pre-trained `distilbert-base-uncased` transformer model to classify movie reviews from the IMDb dataset as positive or negative.

## Overview
- **Model:** DistilBERT (`distilbert-base-uncased`)
- **Dataset:** IMDb Movie Reviews (400 training samples, 100 test samples)
- **Framework:** PyTorch & Hugging Face `transformers`
- **Results:** Reached 72% accuracy and a 0.714 F1-score after 2 epochs of fine-tuning on CPU.

## Files
- `DistilBERT_Sentiment_FineTuning.ipynb` – Complete notebook containing data preprocessing, model fine-tuning, evaluation metrics, sample predictions, and project notes.
