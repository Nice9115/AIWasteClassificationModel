# ♻️ AI Smart Waste Classification Project

### 🌍 SDG Focus: **SDG 11 – Sustainable Cities and Communities**

This project applies **Machine Learning (AI)** to automatically classify different types of waste such as **plastic, paper, glass, metal, and organic materials**.  
The goal is to support **smart waste management** and promote cleaner, more sustainable cities.

---

## 🧠 Project Summary

- **Goal:** Use image classification to help smart bins automatically sort waste into the right category.
- **Machine Learning Type:** Supervised Learning (Image Classification)
- **Model Used:** Convolutional Neural Network (CNN)
- **Framework:** TensorFlow / Keras (run in Google Colab)
- **Dataset Source:** [Garbage Classification Dataset – Kaggle](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification)
- **Training Accuracy:** ~90%
- **Validation Accuracy:** ~50%

---

## 🧩 Workflow Overview

1. **Dataset Preparation:**  
   - Uploaded and unzipped the waste image dataset in Google Colab  
   - Used `ImageDataGenerator` to normalize and split the data (80% training, 20% validation)

2. **Model Design:**  
   - Created a CNN with convolution, pooling, and dense layers  
   - Used ReLU and Softmax activations for classification  

3. **Model Training:**  
   - Trained for 10 epochs  
   - Observed learning curve with rising training accuracy  

4. **Evaluation:**  
   - Plotted accuracy graph for both training and validation sets  

---

## 📊 Results

The model successfully learned to distinguish different waste types.  
Below is a sample of the accuracy progress:

![Accuracy Graph](accuracy_graph.png)

> The training accuracy increased up to 90%, while validation accuracy stabilized around 50%, indicating potential for improvement with data augmentation or transfer learning.

---

## 🌱 Impact on SDGs

This project contributes to:
- **SDG 11 (Sustainable Cities & Communities):** By promoting efficient waste sorting and recycling.
- **SDG 13 (Climate Action):** Reducing pollution and landfill waste through smarter disposal systems.

---

## 🕊️ Ethical Reflection

AI bias can arise if the dataset is unbalanced (e.g., more plastic images than paper).  
Future improvements include collecting diverse, high-quality waste images and deploying the model in real smart bins.  
This ensures **fair, transparent, and sustainable AI solutions** that protect the environment.

---

## ⚙️ Tools & Technologies

- Google Colab  
- Python  
- TensorFlow / Keras  
- NumPy, Matplotlib  
- Kaggle Datasets  
- GitHub for version control  

---

## 💡 Next Steps

- Improve model performance using **data augmentation**  
- Experiment with **MobileNetV2 (Transfer Learning)**  
- Deploy as a **web app using Streamlit or Flask**  
- Integrate with real smart bin hardware for testing

---

👨‍💻 **Author:** *[Your Name]*  
🕓 **Date:** October 2025  
📬 **Contact:** *[Your Email or GitHub username]*

---

> “AI can be the bridge between innovation and sustainability.” — UN Tech Envoy
