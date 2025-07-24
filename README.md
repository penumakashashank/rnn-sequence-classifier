# rnn-sequence-classifier
# 🔁 Sequential Pattern Classification using RNN/LSTM/GRU

This project demonstrates a simple Recurrent Neural Network (RNN) model built with PyTorch to classify toy sequences based on whether they form a **strictly increasing pattern**.

## 🧠 Problem Statement

Given a sequence of 4 integers between 0–9, the model predicts whether the numbers are strictly increasing (e.g., `[2, 4, 6, 8]` → `1`) or not (e.g., `[4, 3, 7, 9]` → `0`).

## 🛠️ Model Architecture

- **Embedding Layer**: Converts input digits into dense vectors.
- **RNN Variants**: Choose between `RNN`, `LSTM`, or `GRU` for sequence modeling.
- **Fully Connected Layer**: Final binary prediction with sigmoid activation.

## 📊 Dataset

- **Synthetic dataset** generated on the fly.
- Each sample: A sequence of 4 digits and a label (0 or 1).

## 🔄 Workflow

1. Generate toy dataset.
2. Build a model using LSTM/GRU/RNN.
3. Train for 5 epochs using Binary Cross Entropy Loss.
4. Evaluate using accuracy and confusion matrix.

## 🔧 Requirements

- Python 3.x
- PyTorch
- Matplotlib
- Seaborn
- scikit-learn

Install requirements using:

```bash
pip install torch matplotlib seaborn scikit-learn
