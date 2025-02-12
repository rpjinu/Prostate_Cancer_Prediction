# Prostate_Cancer_Prediction
The project aims to predict prostate cancer at an early stage using machine learning by analyzing patient data and selecting the most relevant features for improved model accuracy. 🚀

<img src="https://github.com/rpjinu/Prostate_Cancer_Prediction/blob/main/Project_image.png">

# 🚀 Prostate Cancer Early Prediction

## 📌 Project Overview
Prostate cancer is one of the most common types of cancer among men. This project aims to build a **machine learning model** that predicts the likelihood of prostate cancer **at an early stage** using patient medical data. By leveraging feature selection and advanced ML techniques, we improve prediction accuracy and help in early diagnosis.

---

## 🏗️ Tech Stack
- **Programming Language:** Python 🐍
- **Libraries & Frameworks:**
  - Pandas 🏷️ (Data Handling)
  - NumPy 🔢 (Mathematical Operations)
  - Scikit-Learn 🤖 (Machine Learning)
  - Matplotlib & Seaborn 📊 (Data Visualization)
  - TensorFlow / PyTorch 🧠 (Deep Learning - if applicable)

---

## 📂 Dataset
The dataset includes **various medical features** related to prostate cancer detection:
- **Demographic Features**: Age, Race
- **Medical History**: Diabetes, Hypertension, Smoking & Alcohol History
- **Symptoms**: Pelvic Pain, Blood in Urine, Difficulty Urinating
- **Test Results**: PSA Level, Biopsy Result, DRE Result
- **Lifestyle Factors**: Exercise, Diet
- **Cancer-Related**: Family History, Genetic Risk, Cancer Stage

### 🎯 Target Variable:
- **`Early_Detection`** → Binary classification (1 = Cancer detected early, 0 = No early detection)

---

## 📊 Data Preprocessing
1. **Handle Missing Values** 🚫
2. **Encode Categorical Variables** 🔢 (Label Encoding & One-Hot Encoding)
3. **Feature Scaling** 📏 (Standardization / Normalization)
4. **Feature Selection** 🎯 (Using Correlation & Random Forest Feature Importance)

---

## 🏋️ Model Training & Evaluation
### 🔍 Models Tested:
- **Logistic Regression** 📈
- **Random Forest Classifier** 🌳
- **XGBoost** 🚀
- **Neural Networks (Optional)** 🧠

### 🏆 Performance Metrics:
- **Accuracy** ✅
- **Precision & Recall** 🎯
- **F1-Score** 📊
- **ROC-AUC Score** 📈

---

## 📌 Results & Insights
✔️ Important features for early detection: **Biopsy Result, PSA Level, DRE Result, Family History**
✔️ Feature selection improved model accuracy 🎯
✔️ Random Forest & XGBoost performed best 🚀
✔️ Data visualization helped in understanding medical trends 🩺

---

## 📢 How to Run the Project 🏃‍♂️
### 🔧 Prerequisites
- Install required libraries:
  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn xgboost
  ```

### ▶️ Run the Model
```bash
python main.py
```

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repo, create a feature branch, and submit a pull request. 🚀

---

## 📜 License
This project is open-source under the **MIT License**. Feel free to use and modify it!

---

## 🏆 Acknowledgments
🙏 Thanks to the **medical research community** for providing valuable datasets and insights.

💡 Let's fight **prostate cancer** with **AI & Data Science**! 🏥🔬

