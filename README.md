
# Diabetes Dataset — Machine Learning Project

Predict whether an individual has diabetes based on medical and demographic features (e.g., glucose level, BMI, age) using supervised machine learning.

---

## 🎯 Project Overview

- **Objective**: Build and train one or more machine learning models to classify individuals as diabetic or non-diabetic using a publicly available dataset.  
- **Motivation**: Early prediction of diabetes can assist in preventive healthcare and patient monitoring. (and this is my homesork machine learning class task to, irrelevant totaly) 
- **Dataset**: A standard diabetes classification dataset with features such as glucose, blood pressure, BMI, age, etc. (See the `data_sets/` folder).
- **New approach**: this time try a solid and repeatable approach, not perfect but better than last one
---

## 🧰 Technologies & Tools

- Python 3.x  
- Jupyter Notebook (`diabetes_dataset_ML.ipynb`)  
- Key libraries: `pandas`, `numpy`, `scikit-learn`, `seaborn`  
- Data handling, feature engineering, model training & evaluation

---

## 📂 Repository Structure
```
diabetes_dataset_ML/
│
├── data_sets/ # Source dataset(s)
│ └── <dataset_file>.csv # Raw data file
│
├── diabetes_dataset_ML.ipynb # Jupyter notebook with full workflow
├── README.md # Project documentation (this file)
└── LICENSE # MIT License
```



📊 Results & Evaluation

Models trained and compared using classification metrics such as Accuracy, Precision, Recall, F1-score.
Visualizations included: distribution of features, correlation heatmap, confusion matrix.
best result by:: “model SVC 0.773 accuracy and weighted avg f1_score of 0.75”).



🔮 Future Improvements(have in mind for now!)

Try additional algorithms (e.g., XGBoost, Neural Networks) and compare.

Add unit tests for data processing and model functions.
