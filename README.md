
```markdown
# Devixo Solutions - Task 02: Student Academic Success Prediction

This repository contains the complete implementation of Task 02 for Devixo Solutions. The project focuses on building an end-to-end machine learning pipeline to predict students' academic outcomes (Dropout, Enrolled, or Graduate) using a real-world dataset.

---

## 📂 Folder Structure

```text
├── Dataset/         # Contains the raw dataset files (CSV/Semicolon separated)
├── Notebook/        # Contains the Jupyter Notebooks with full model training and code
└── Report/          # Contains the formal project documentation and reports

```

---

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Machine Learning (Scikit-Learn):**
* `Pipeline` & `ColumnTransformer` for structured preprocessing
* `StandardScaler` for feature scaling
* `LogisticRegression`, `RandomForestClassifier`, `KNeighborsClassifier` (KNN)
* `RandomizedSearchCV` for hyperparameter tuning
* Metrics: `accuracy_score`, `f1_score`, `classification_report`, `confusion_matrix`


* **Development Environment:** Jupyter Notebook / Google Colab
* **Version Control:** Git & GitHub

---

## 📊 Project Overview

1. **Data Preprocessing & Pipelines:** Configured automated pipelines using `ColumnTransformer` to handle numerical feature scaling cleanly.
2. **Model Training:** Trained three distinct classification models:
* Logistic Regression
* Random Forest
* K-Nearest Neighbors (KNN)


3. **Model Evaluation:** Evaluated models using accuracy, precision, recall, and F1-scores via detailed classification reports.
4. **Hyperparameter Tuning:** Applied `RandomizedSearchCV` on the Random Forest model to optimize performance parameters.
5. **Comparison & Conclusion:** Compared models based on accuracy, training time, advantages, and limitations to recommend the best-performing model.

---

## 🚀 How to Run the Project

1. Clone the repository:
```bash
git clone [https://github.com/HamzaWaseem2005/Devixo-Task02.git](https://github.com/HamzaWaseem2005/Devixo-Task02.git)

```


2. Navigate to the project directory and open the `Notebook/` folder.
3. Open the Jupyter Notebook and run the cells sequentially to reproduce data preprocessing, model training, and evaluation metrics.

---

## 📝 Author

**Muhammad Hamza Waseem**

```


```
