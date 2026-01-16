# RNN IMDB Sentiment Analysis

This project implements a **Simple RNN-based sentiment classifier** using the **IMDB movie reviews dataset** from Keras.

The model predicts whether a movie review is **positive** or **negative** based on the text.

---

## 📚 Dataset

- Dataset: IMDB Movie Reviews (from Keras)
- Number of words considered: 1000 (top most frequent words)
- Sequence length: 500 (padded sequences)

---

## 🛠 Tech Stack

- Python 3.x  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

---

## 🏗 Model Architecture

1. **Embedding Layer** – Converts words into dense vectors.  
2. **SimpleRNN Layer** – 128 units, `tanh` activation.  
3. **Dense Layer** – Sigmoid activation for binary classification.

- Optimizer: `Adam`  
- Loss: `Binary Crossentropy`  
- Metrics: `Accuracy`  
- EarlyStopping used to prevent overfitting (monitoring validation loss)

---

## 📈 Results

- Training Accuracy and Validation Accuracy plotted for each epoch  
- Training Loss and Validation Loss plotted for each epoch  
- Model evaluation performed on the test set  

Example prediction:

