# LLM Fine-Tuning with LoRA on IMDB Dataset

This repository contains code for fine-tuning a Large Language Model  (DestilBERT) on the IMDB dataset for sentiment analysis. It compares two approaches:

1. **LoRA Fine-Tuning**: A lightweight approach for fine-tuning LLMs, which reduces memory usage and training time.
2. **Full Fine-Tuning**: The traditional approach of fine-tuning all parameters of the model.

## Dataset

The IMDB dataset is used for training the sentiment analysis model. It is a popular dataset for binary sentiment classification, where the goal is to predict whether a review is positive or negative based on its text.

- Dataset Link: [IMDB Sentiment Analysis Dataset]([(https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)]
  
## Requirements

To run this project, you need the following dependencies:

- Python 3.x
- PyTorch
- Transformers
- Datasets
- Huggingface's Accelerate (for LoRA fine-tuning)


