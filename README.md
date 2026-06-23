
# 📄 Quote Dataset Analysis & RNN Model Visualization

## 🚀 Project Title

**Text Analytics and Simple RNN Model Visualization on Quote Dataset**

---

## 📌 Overview

This project performs **exploratory data analysis (EDA)** and **deep learning model visualization** on a dataset of quotes.

It includes:

* 📊 Text data visualization
* ☁️ Word frequency analysis
* 🌥️ Word cloud generation
* 📈 Quote length analysis
* 🧠 RNN model architecture design (Keras)

---

## 📂 Dataset

📊 Dataset used:

* **Quote Dataset**
* Source: KaggleHub
* Link: [https://www.kaggle.com/datasets/marufchowdhury/quote-dataset](https://www.kaggle.com/datasets/marufchowdhury/quote-dataset)

### 📥 Download Code:

```python id="k9k4kq"
import kagglehub

path = kagglehub.dataset_download("marufchowdhury/quote-dataset")
```

---

## 📊 Dataset Information

* Contains inspirational / motivational quotes
* Column used: `Quote`
* Text-based dataset

---

## 🔍 Exploratory Data Analysis (EDA)

### 📈 Visualizations Included:

* Distribution of quote length (characters)
* Distribution of quote length (words)
* Top 20 most frequent words
* Quote category distribution:

  * Very Short
  * Short
  * Medium
  * Long
* Word Cloud visualization
* Cleaned vs original text comparison
* Sequence length distribution

---

## ☁️ Word Cloud

A word cloud is generated to visualize the most frequent words in the dataset.

---

## 🧠 Deep Learning Model

### Model Type:

**Simple RNN (Recurrent Neural Network)**

### Architecture:

* Embedding Layer (30000 vocab size, 50 dim)
* SimpleRNN Layer (128 units)
* Dense Layer (Softmax output)

---

## ⚙️ Technologies Used

* Python
* Pandas / NumPy
* Matplotlib / Seaborn
* WordCloud
* Scikit-learn (stopwords)
* TensorFlow / Keras

---

## 📊 Model Purpose

The RNN model is designed to:

* Demonstrate sequence modeling
* Visualize NLP architecture
* Prepare for next-word or text generation tasks (conceptual)

---

## 📈 Outputs Generated

* 📊 Histograms (quote length distribution)
* ☁️ Word cloud visualization
* 📉 Sequence analysis plots
* 🧠 RNN model architecture diagram (`rnn_model_architecture.png`)

---

## 🧪 Key Insights

* Most quotes are short (under 15 words)
* A few words dominate frequency distribution
* Dataset is ideal for NLP learning
* Cleaned text improves analysis clarity

---

## 💾 Model Visualization File

```
rnn_model_architecture.png
```

---

## 🎯 Conclusion

This project demonstrates:

* Strong EDA skills for NLP
* Text preprocessing techniques
* Basic RNN architecture understanding
* Visualization-driven machine learning workflow

---

## 🚀 Future Improvements

* Train RNN for text generation
* Use LSTM/GRU for better performance
* Add sentiment analysis
* Build quote generator web app


