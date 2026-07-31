# 🌊 Flood Prediction Using Machine Learning

Predicting flood occurrence using Machine Learning algorithms based on environmental and geographical factors.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Project Overview

Floods are among the most destructive natural disasters, causing significant damage to human life, infrastructure, and the environment.

This project uses **Machine Learning** techniques to predict whether a flood is likely to occur based on various environmental and geographical parameters. Three different classification algorithms are implemented and compared to identify the best-performing model.

---

## 🎯 Objectives

- Predict flood occurrence using historical environmental data.
- Compare the performance of multiple Machine Learning models.
- Identify the most accurate prediction model.
- Build a simple and efficient flood prediction system.

---

## 📂 Dataset Features

The dataset contains the following features:

- 📍 Latitude
- 📍 Longitude
- 🌧 Rainfall (mm)
- 🌡 Temperature (°C)
- 💧 Humidity (%)
- 🌊 River Discharge (m³/s)
- 📈 Water Level (m)
- ⛰ Elevation (m)
- 🌿 Land Cover
- 🌱 Soil Type
- 👥 Population Density
- 🏗 Infrastructure
- 📚 Historical Floods

### Target Variable

- **Flood Occurred**
  - `0` → Low Flood Risk
  - `1` → High Flood Risk

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🤖 Machine Learning Models

The following models are implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## ⚙ Project Workflow

```
Dataset
    │
    ▼
Data Preprocessing
    │
    ▼
Encoding Categorical Data
    │
    ▼
Train-Test Split
    │
    ▼
Model Training
    │
    ▼
Prediction
    │
    ▼
Performance Evaluation
```

---

## 📊 Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **90.15%** |
| Decision Tree | **99.40%** |
| Random Forest | **99.55%** |

> **Best Performing Model:** Logistic Regression Classifier

---

## 📁 Project Structure

```
Flood-Prediction-Using-Machine-Learning/
│
├── flood_prediction.py
├── Flood_Prediction_Analysis.ipynb
├── flood_risk_dataset_india.csv
├── requirements.txt
├── README.md
│
├── model/
│   └── flood_model.pkl
│
└── images/
    ├── confusion_matrix.png
    ├── feature_importance.png
    └── model_accuracy.png
```

---

## 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/Flood-Prediction-Using-Machine-Learning.git
```

### Navigate to the project

```bash
cd Flood-Prediction-Using-Machine-Learning
```

### Install required libraries

```bash
pip install -r requirements.txt
```

### Run the project

```bash
python flood_prediction.py
```

---

## 📈 Sample Prediction

Input:

```
Latitude             : 22.57
Longitude            : 88.36
Rainfall             : 250 mm
Temperature          : 30°C
Humidity             : 85%
River Discharge      : 700 m³/s
Water Level          : 6.5 m
Elevation            : 12 m
Land Cover           : Urban
Soil Type            : Clay
Population Density   : 5000
Infrastructure       : Good
Historical Floods    : Yes
```

Output:

```
Prediction : 1

Flood Risk : HIGH
```

---

## 📌 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature importance analysis
- Interactive web application using Streamlit or Flask
- Real-time weather API integration
- Interactive dashboard for visualization

---

## 👨‍💻 Author

**Tuhin Maji**

B.Tech in Computer Science & Engineering (AI & ML)

---

## ⭐ If you found this project useful

Give this repository a ⭐ and feel free to fork it!

---

## 📜 License

This project is intended for educational and learning purposes.
