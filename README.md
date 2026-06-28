# 😊 Sentiment Analysis Using RNN

## 📌 Project Overview

This project performs Sentiment Analysis using a Recurrent Neural Network (RNN) on the IMDb movie review dataset. The model classifies movie reviews as Positive or Negative sentiments by learning sequential patterns in text data.

The project demonstrates the application of Deep Learning and Natural Language Processing (NLP) techniques for text classification tasks.

---

## 🎯 Objectives

* Classify movie reviews into positive and negative sentiments.
* Learn text sequence patterns using RNN.
* Evaluate model performance using classification metrics.
* Visualize training performance and prediction results.

---

## 🛠 Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 📂 Dataset

Dataset: IMDb Movie Reviews Dataset

* 50,000 movie reviews
* Binary Sentiment Classification
* Positive Reviews
* Negative Reviews

The dataset is loaded directly from TensorFlow Keras.

---

## 🚀 Project Workflow

1. Import Required Libraries
```python
!pip install tensorflow numpy pandas matplotlib seaborn scikit-learn
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from tensorflow.keras.datasets import imdb
from tensorflow.keras.preprocessing.sequence import pad_sequences
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import Embedding, SimpleRNN, Dense, Dropout
from sklearn.metrics import confusion_matrix, classification_report
 
```

---

## 🧠 Model Architecture

* Embedding Layer
* Simple RNN Layer
* Dropout Layer
* Dense Hidden Layer
* Output Layer (Sigmoid)

---

## 📊 Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Classification Report
* Precision
* Recall
* F1-Score

---

## 📈 Visualizations

The project includes:


# Training Accuracy & Loss:

<img width="1289" height="495" alt="image" src="https://github.com/user-attachments/assets/98f3e579-6d46-4021-a560-bb20e59ec7b7" />

# Confusion matrix 

<img width="527" height="393" alt="image" src="https://github.com/user-attachments/assets/91bdfd45-9cf0-477a-9d7a-b86951cb6007" />

Four Type Visualization

<img width="1390" height="985" alt="image" src="https://github.com/user-attachments/assets/a1b02d05-8888-4bfd-927e-72ec22680092" />

#Six Type Visualization

<img width="1990" height="1181" alt="image" src="https://github.com/user-attachments/assets/2c859007-147e-4e50-a115-0cd781f9ec2a" />

---

## ▶️ Installation

```bash
pip install tensorflow numpy pandas matplotlib seaborn scikit-learn
```

---

## ▶️ Run the Project

```bash
jupyter notebook/google colab
```

Open:

```bash
Sentiment_Analysis_Using_RNN.ipynb
```

---

## 💡 Applications

* Movie Review Analysis
* Customer Feedback Analysis
* Product Review Classification
* Social Media Monitoring
* Opinion Mining

---

## 👩‍💻 Author

**Pattammal M**

---

## ⭐ GitHub

If you found this project useful, please give it a ⭐ on GitHub.
