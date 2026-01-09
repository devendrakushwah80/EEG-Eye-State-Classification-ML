# 🧠 EEG Eye State Classification using Machine Learning

## 📌 Project Overview
This project focuses on **classifying human eye states (Open / Closed)** using **EEG (Electroencephalogram) brain signal data**.  
By applying multiple **machine learning classification algorithms**, the project aims to identify the most effective model for EEG-based eye state detection.

The workflow includes **data preprocessing, feature scaling, model training, hyperparameter tuning, and performance evaluation** using industry-standard metrics.

---

## 📂 Dataset Information
- **Dataset:** EEG Eye State Dataset
- **File Used:** `EEG-Eye-State.csv`
- **Target Variable:** `eyeDetection`
  - `0` → Eye Open
  - `1` → Eye Closed

The dataset contains EEG signal values recorded from multiple sensors over time.

---

## ⚙️ Technologies & Libraries
- **Python**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **Scikit-learn**

---

## 🔄 Machine Learning Pipeline
A structured and leakage-free pipeline is implemented using Scikit-learn.

### Steps Involved:
1. Data Loading & Exploration
2. Train–Test Split
3. Feature Scaling using `StandardScaler`
4. Pipeline Integration
5. Model Training
6. Hyperparameter Tuning with `GridSearchCV`
7. Model Evaluation

---

## 🤖 Models Implemented
The following classifiers are trained and compared:

1. **Logistic Regression**
2. **Support Vector Machine (SVM)**
3. **K-Nearest Neighbors (KNN)**
4. **Random Forest Classifier**

Each model is optimized using **GridSearchCV** to ensure the best performance.

---

## 📊 Evaluation Metrics
To fairly assess model performance, the following metrics are used:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

This multi-metric evaluation ensures robustness beyond accuracy alone.

---

## 📈 Key Insights
- Feature scaling significantly improves **KNN** and **SVM** performance.
- **Random Forest** handles EEG noise effectively due to ensemble learning.
- Hyperparameter tuning prevents overfitting and underfitting.

---

## 📁 Project Structure
├── EEG_Eye_State_Classification_ML.ipynb
├── EEG-Eye-State.csv
├── requirements.txt
└── README.md


---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/EEG-Eye-State-Classification-ML.git
cd EEG-Eye-State-Classification-ML
2️⃣ Create a Virtual Environment
python -m venv venv
venv\Scripts\activate
3️⃣ Install Required Dependencies
pip install -r requirements.txt
4️⃣ Launch Jupyter Notebook
jupyter notebook EEG_Eye_State_Classification_ML.ipynb
5️⃣ Run the Notebook
```
🔮 Future Improvements

Apply Deep Learning models (CNN / LSTM) for temporal EEG analysis

Perform feature selection

Handle class imbalance techniques

Cross-dataset generalization testing

👤 Author

Devendra Kushwah
Machine Learning & Data Science Enthusiast
