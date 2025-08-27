# Next Word Prediction using LSTM RNN (Shakespeare's *Hamlet*)

This project implements a **Next Word Prediction** model using a **Long Short-Term Memory (LSTM) Recurrent Neural Network** trained on the text of William Shakespeare’s *Hamlet*.  
It demonstrates how deep learning models can understand word sequences and predict the next word in a phrase, capturing the style and language patterns of Early Modern English.

---

## 🚀 Features
- Trains an **LSTM RNN** on the text of *Hamlet*.
- Predicts the **most probable next word** in a sequence.
- Supports **iterative text generation** in Shakespearean style.
- Saves the trained model in `.keras` format for easy reuse.

---

## 🧠 Model Architecture
- **Embedding Layer** – converts words into dense vector representations.
- **LSTM Layers** – captures sequential dependencies in text.
- **Dense + Softmax Layer** – predicts the probability distribution of the next word.

---

## 📂 Dataset
- Public domain text of *Hamlet* by William Shakespeare.
- Preprocessing includes:
  - Cleaning special characters
  - Lowercasing text
  - Tokenizing and padding sequences

---

