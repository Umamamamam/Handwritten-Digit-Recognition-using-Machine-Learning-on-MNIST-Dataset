# Handwritten Digit Recognition using Machine Learning on MNIST Dataset

## 📌 Project Overview
This project focuses on recognizing handwritten digits (0–9) using the MNIST dataset. The objective is to build and compare multiple supervised machine learning models to identify the most accurate classifier for handwritten digit recognition.

---

## 🎯 Objectives
* Perform Exploratory Data Analysis (EDA) on the MNIST dataset.
* Preprocess image data for model training.
* Train multiple classification models.
* Compare model performance using evaluation metrics.
* Select the best model for production.

---

## 📂 Dataset
* **Dataset:** MNIST (Modified National Institute of Standards and Technology)
* **Image Size:** 28 × 28 pixels (Grayscale)
* **Classes:** 10 (Digits 0–9)

---

## 🛠️ Technologies Used
* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow / Keras
* Jupyter Notebook

---

## 🤖 Models Implemented
* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Random Forest
* MLP (Neural Network)

---

## 📊 Evaluation Metrics
* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Training / Prediction Time

---

## 📈 Workflow
1. Import Libraries
2. Load the MNIST Dataset
3. Exploratory Data Analysis (EDA)
4. Data Preprocessing
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Model Comparison
9. Final Prediction
10. Conclusion

---

## 🏆 Results

Five machine learning models were trained and compared using accuracy, training time, and prediction time.

| Model | Accuracy | Train Time (s) | Predict Time (s) |
|---|---|---|---|
| **SVM (RBF)** | **0.9649** | 12.72 | 34.60 |
| MLP (Neural Net) | 0.9586 | 35.48 | 0.09 |
| Random Forest | 0.9512 | 5.27 | 0.29 |
| KNN | 0.9480 | 0.01 | 5.36 |
| Logistic Regression | 0.9084 | 11.85 | 0.03 |

**Best Accuracy:** SVM (RBF) achieved the highest accuracy at **96.49%**, but with the slowest prediction time (34.60s).

**Best Overall for Production:** Random Forest offers the strongest balance — high accuracy (95.12%), fast training (5.27s), and fast prediction (0.29s) — making it the most practical choice for production deployment.

---

## 📁 Repository Structure
```text
├── notebook/
│   └── Handwritten_Digit_Recognition.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run
1. Clone the repository.
2. Install the required dependencies.
3. Open the Jupyter Notebook.
4. Run all cells sequentially.
5. Compare model performance and view predictions.

---

## 📌 Conclusion
This project demonstrates how different supervised machine learning algorithms perform on the MNIST handwritten digit dataset. A comparative analysis of Logistic Regression, KNN, SVM, Random Forest, and MLP was conducted to identify the most effective model for handwritten digit classification. SVM (RBF) delivered the highest accuracy at 96.49%, while Random Forest provided the best trade-off between accuracy and speed, making it the recommended model for production use.

---

## 👨‍💻 Author
**Umamaheshwara Reddy**
