# 🔤 Telugu to English Transliterator

## Overview

This project is a deep learning–based character-level transliteration system that converts Telugu script into Roman (English) script. It uses an attention-based encoder-decoder architecture implemented in TensorFlow to learn transliterations from real Telugu-English word pairs.

---

## ✨ Features

- 🔁 **Character-level Encoder-Decoder**: Handles each character individually for fine-grained transliteration.
- 🧠 **Attention Mechanism**: Helps the decoder focus on relevant parts of the input sequence at each decoding step.
- 📊 **Evaluation Metrics**: Supports accuracy calculation and visualization for model performance.
- ✅ **Inference Mode**: Predict transliterations without ground truth during testing.
- 📦 **Clean TensorFlow Implementation**: Easy-to-read, modular code built for learning and customization.

---

## 🧱 Architecture

- **Encoder**: GRU-based RNN that encodes the input Telugu sequence.
- **Attention Layer**: Computes attention weights between encoder outputs and decoder state.
- **Decoder**: GRU-based RNN that predicts Roman script characters sequentially.
- **Output Layer**: Dense layer with softmax activation to map hidden states to character probabilities.

---

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Jupyter Notebook

---

## Steps to Run

To set up the project locally, follow these steps:

1. *Clone the repository*:
   ```bash
   git clone https://github.com/AkshithReddy12/telugu-transliterator
   cd telugu-transliterator

3. *Install Requirements*:
   ```bash
   pip install
4. *Make sure dataset files are present in same path*:
   
5. *Run the notebook*:
    
    
