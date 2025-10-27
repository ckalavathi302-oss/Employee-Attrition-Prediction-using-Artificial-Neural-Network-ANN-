# Employee Attrition Prediction using Artificial Neural Network (ANN)

## 📘 Overview
This project predicts employee attrition using an Artificial Neural Network (ANN) trained on the **IBM HR Analytics Employee Attrition Dataset**. It applies deep learning techniques to analyze employee data, identify key factors influencing attrition, and predict the likelihood of employees leaving the organization.

---

## 📊 Dataset
- **Source:** [IBM HR Analytics Employee Attrition Dataset (Kaggle)](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Description:** The dataset includes features such as age, gender, education, job role, monthly income, work-life balance, and attrition status.
- **Target Variable:** `Attrition` (Yes / No)

---

## 🧠 Project Workflow
1. **Data Collection** – Import dataset from Kaggle.
2. **Data Preprocessing** – Handle missing values, encode categorical features, and scale numerical data.
3. **Exploratory Data Analysis (EDA)** – Visualize relationships using heatmaps and distribution plots.
4. **Feature Selection** – Identify key factors affecting attrition.
5. **Model Building** – Build an ANN with Keras Sequential API:
   - Input layer
   - Two hidden layers (ReLU activation)
   - Output layer (Sigmoid activation)
6. **Model Training** – Train using Binary Crossentropy loss and Adam optimizer.
7. **Evaluation** – Assess performance using accuracy, confusion matrix, and classification report.
8. **Prediction** – Predict attrition for new or unseen employee data.

---

## 📐 Mathematical Explanation
- **ReLU Activation:**  
  ReLU(x) = max(0, x)

- **Sigmoid Activation:**  
  σ(x) = 1 / (1 + e<sup>-x</sup>)

- **Binary Crossentropy Loss:**  
  L = - (1/N) Σ [y log(p) + (1 - y) log(1 - p)]

- **Optimizer:** Adam (Adaptive Moment Estimation)

---

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- TensorFlow / Keras
- Scikit-learn
- Matplotlib, Seaborn

---

## 📈 Results
The ANN model accurately predicts employee attrition by learning complex patterns in HR data.
Visualization of training accuracy and loss shows consistent improvement across epochs, confirming effective model learning.

---

## 💡 Future Scope
- Apply hyperparameter tuning for better accuracy
- Experiment with advanced deep learning models (LSTM, CNN)
- Integrate with HR dashboards for real-time attrition monitoring

---

## 👩‍💻 Author
**Elavarasi Chinnadurai**
