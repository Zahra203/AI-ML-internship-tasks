# Task 3 - Heart Disease Prediction


## Objective
Build a machine learning model to predict if a person is at risk of heart disease using their health data.

---

## Dataset Details
- **Source**: UCI Heart Disease Dataset (via Kaggle)
- **Samples**: 303 rows
- **Target column**: `target`  
  - 0 = No Heart Disease  
  - 1 = At Risk of Heart Disease

###  Features of the Dataset:

| Feature        | Description                                             |
|----------------|---------------------------------------------------------|
| `age`          | Age of the person                                       |
| `sex`          | 1 = Male, 0 = Female                                     |
| `cp`           | Chest Pain Type (0–3)                                   |
| `trestbps`     | Resting blood pressure (mm Hg)                          |
| `chol`         | Serum cholesterol (mg/dl)                               |
| `fbs`          | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)   |
| `restecg`      | Resting ECG results (0–2)                               |
| `thalach`      | Max heart rate achieved                                 |
| `exang`        | Exercise induced angina (1 = yes, 0 = no)               |
| `oldpeak`      | ST depression after exercise                            |
| `slope`        | Slope of the peak exercise ST segment (0–2)            |
| `ca`           | Number of major vessels colored by fluoroscopy (0–3)    |
| `thal`         | Thalassemia (1 = normal, 2 = fixed defect, 3 = reversible) |
| `target`       | Target class (0 = No Disease, 1 = Heart Disease)        |

---

##  Models Used
- Logistic Regression
- Decision Tree Classifier

---

## Final Insights 

1. **Clean Data**: The dataset had no missing values and required minimal preprocessing.
2. **EDA**: Target variable is balanced enough for binary classification. Age, chest pain type, and cholesterol showed meaningful patterns.
3. **Model Performance**:
   - Logistic Regression was fast and had decent accuracy.
   - Decision Tree captured feature interactions and performed slightly better in ROC-AUC.
4. **Important Features**:
   - Chest Pain Type (`cp`)
   - Maximum Heart Rate (`thalach`)
   - ST Depression (`oldpeak`)
5. **Conclusion**: Both models are effective for risk prediction. Decision Tree allows interpretability via feature importance.



---

## Libraries Used

| Library           | Purpose                                      |
|-------------------|----------------------------------------------|
| **pandas**        | Load and process data                        |
| **matplotlib**    | Create visualizations                        |
| **seaborn**       | Statistical and stylish plots                |
| **scikit-learn**  | Machine learning models and evaluation       |
| **StandardScaler**| Normalize feature values                     |
| **roc_auc_score** | Measure model’s ability to separate classes  |

---

## Files Included
- `heart_disease_prediction.ipynb`: Complete Jupyter notebook
- `README.md`: Task overview, dataset info, results, and libraries
- dataset file
