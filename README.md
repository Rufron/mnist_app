# 🧠 Week 3 AI Tools & Applications — MNIST & NLP Project

👋 Hey everyone!  
This project was created as part of **Week 3: AI Tools & Applications**.  
It involves building an **MNIST digit classification model** using **TensorFlow** and performing **Named Entity Recognition (NER)** and **Sentiment Analysis** on **Amazon product reviews** using **spaCy**.

---

## 🚀 Project Overview

This project combines **Computer Vision** and **Natural Language Processing (NLP)** techniques:

### 🖩 Part 1: MNIST Digit Classification
- Trained a neural network to classify handwritten digits (0–9).  
- Achieved **97.4% test accuracy** after 5 epochs.  
- Included **error analysis** and visualization of misclassified digits.  

### 💬 Part 2: NLP with spaCy
- Extracted **brands and product names** using **Named Entity Recognition (NER)**.  
- Performed **sentiment analysis** (positive/negative) using a simple rule-based system.  
- Generated insights on **brand sentiment distribution** and entity recognition accuracy.

### ⚖️ Part 3: Ethics & Optimization
- Discussed **model bias**, **fairness**, and **optimization challenges**.  
- Suggested mitigation techniques like **TensorFlow Fairness Indicators** and **custom NER rules**.

---

## 🧩 Tech Stack

| Component | Library/Tool |
|------------|--------------|
| Deep Learning | TensorFlow / Keras |
| NLP | spaCy |
| Visualization | Matplotlib |
| Data Handling | NumPy, pandas |
| Environment | Google Colab / Local Jupyter |

---

## 📊 Results Summary

- **MNIST Model Accuracy:** 97.4%  
- **Training Duration:** 5 epochs (~7s per epoch)  
- **Key Finding:** Misclassified digits usually resembled other numbers visually (e.g., “5” predicted as “3”).  
- **NER Insights:** Brands like *Apple* and *Sony* were correctly detected; *Bose* was mislabeled (NORP).  
- **Sentiment Results:** Positive reviews dominated; sentiment linked closely with detected brands.

---

## 💾 Outputs

- **Saved Model:** `mnist_model.h5`
- **PDF Report:** [📄 View Here](https://week-3-assignment-4f86dqe.gamma.site/)
- **Code Repository:** [📘 GitHub Repo](https://github.com/Rufron/mnist_app)

---

## 🧠 Contributors

- **Brian Kipchumba** 
- **Borchar Gatwetch**
- **Masaiwe Rufina**

---

## 💬 Feedback

Had a great time exploring model performance, ethics, and optimization.  
Feedback and contributions are welcome! 🚀

---

### ⭐ Acknowledgments
Special thanks to the **PLP AI Tools & Applications Team** for providing the learning framework and guidance throughout this project.
