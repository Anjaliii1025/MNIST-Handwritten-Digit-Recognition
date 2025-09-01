# 🔢 Handwritten Digit Recognition (MNIST)

This project uses **Convolutional Neural Networks (CNNs)** to recognize handwritten digits (0–9) from the **MNIST dataset**. The goal is to train a deep learning model that achieves high accuracy in digit classification and demonstrates the power of CNNs in image recognition.

---

## 📌 Objective

To build, train, and evaluate a CNN model that can classify handwritten digits with high accuracy using the MNIST dataset. The project also visualizes model performance and analyzes classification trends.

---

## 🗃️ Dataset

- **Source:** [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)  
- **Details:**  
  - 60,000 training images  
  - 10,000 testing images  
  - Image size: 28×28 pixels, grayscale  
  - Labels: Digits from 0–9  

---

## 📊 Project Outputs

### ✔️ Visualizations:
- **Sample Images:** Random handwritten digits with labels  
- **Training Curves:** Accuracy & loss across epochs  
- **Confusion Matrix:** Correct vs. misclassified digits  

### ✔️ Metrics:
- 📈 **Training Accuracy:** ~99%  
- ✅ **Test Accuracy:** ~98–99%  
- ❌ **Common Misclassifications:** Similar digits (e.g., 4 vs 9, 3 vs 5)  

---

## 🧰 Tools & Libraries

- `tensorflow` / `keras` for deep learning  
- `numpy` for numerical operations  
- `matplotlib` & `seaborn` for visualizations  
- `scikit-learn` for confusion matrix  

---

## 📌 Key Insights

- CNN achieved **~99% accuracy**, close to human-level performance.  
- Model generalizes well, with minimal overfitting.  
- Most errors happen between visually similar digits.  
- Demonstrates CNN’s effectiveness in **image recognition tasks**.  

---
