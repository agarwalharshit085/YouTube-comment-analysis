# YouTube Comment Sentiment Analysis using DistilBERT

This project fine-tunes the `distilbert-base-uncased` transformer model to perform sentiment analysis on YouTube comments, classifying them into **positive**, **neutral**, or **negative** categories.

## 📁 Files Included
- `YoutubeCommentsDataSet.csv` – Dataset used for training and testing  
- `YouTube Project.ipynb` – Complete training pipeline in a Jupyter Notebook  
- `trained_model.pkl` – Pickled trained model  
- `tokenizer.pkl` – Pickled tokenizer  
- `/distilbert-base-uncased-finetuned-youtube-comment-sentiment/` – Directory containing the saved model and tokenizer  
- `README.md` – Project overview and instructions

## 🚀 Features
- Data preprocessing and label encoding
- Train-test split with class stratification
- Tokenization using Hugging Face Transformers
- Fine-tuning using `Trainer` API
- Accuracy and F1 score evaluation
- Saving and loading models for inference
- Real-time sentiment predictions

## 🛠️ Requirements
Install required libraries using:

```bash
pip install pandas scikit-learn datasets transformers torch
