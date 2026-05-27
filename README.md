# -Sentiment-Analysis-using-DistilBERT-for-Financial-News
This project performs sentiment analysis on financial-news related tweets using the DistilBERT model.

## Features
- DistilBERT based sentiment classification
- Predicts:
  - Bullish
  - Bearish
  - Neutral
- GUI for inference
- HuggingFace Trainer used for training

## Dataset
Dataset used:
`zeroshot/twitter-financial-news-sentiment`

## Technologies Used
- Python
- PyTorch
- HuggingFace Transformers
- DistilBERT
- Tkinter GUI

## Installation

```bash
pip install -r requirements.txt
```

## Run Training

```bash
python train.py
```

## Run GUI

```bash
python app.py
```
