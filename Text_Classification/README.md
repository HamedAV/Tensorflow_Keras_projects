# 🎭 NLP Sarcasm Detection using MLP with Pre-trained Embeddings
## 📋 Project Overview
This project implements a sarcasm detection system using a Multi-Layer Perceptron (MLP) neural network combined with Google's pre-trained GNews-Swivel word embeddings. The model classifies news headlines as sarcastic or non-sarcastic, demonstrating the power of transfer learning in natural language processing tasks.
## 🎯 Objectives

Binary Classification: Detect sarcasm in news headlines with high accuracy
Transfer Learning: Leverage pre-trained word embeddings for better text representation
Deep Learning: Implement MLP architecture for text classification
Performance Analysis: Evaluate model performance with comprehensive metrics

## 📊 Dataset
Sarcasm Detection Dataset

Source: Google Storage - Learning Datasets
Format: JSON file with structured data
Size: ~26,000 news headlines
Features:

headline: The news headline text
is_sarcastic: Binary label (1 = sarcastic, 0 = not sarcastic)
article_link: Source URL of the article



## Dataset Statistics:

Total samples: ~26,000
Sarcastic headlines: ~13,000 (50%)
Non-sarcastic headlines: ~13,000 (50%)
Average headline length: ~10-15 words

## 🧠 Model Architecture
Pre-trained Embeddings

Model: Google GNews-Swivel
Source: Kaggle Models Hub
Dimensions: 20D vector representations
Training Data: Google News corpus
Vocabulary: Pre-trained on millions of news articles


## Embedding Layer: TensorFlow Hub layer (non-trainable)
Hidden Layers: Dense layers with ReLU activation
Dropout: Regularization to prevent overfitting
Output Layer: Single neuron with sigmoid activation for binary classification
