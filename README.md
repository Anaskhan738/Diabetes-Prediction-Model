# Diabetes-Prediction-Model
A machine learning project that uses the PIMA Diabetes Dataset to predict whether a person has diabetes. The model is built and evaluated using a Support Vector Machine (SVM) classifier.

This project aims to predict the likelihood of a person having diabetes based on various health-related features. The model is trained on the PIMA Diabetes Dataset and uses a Support Vector Machine (SVM) classifier for prediction.

---

### **Overview of the Project**

The core of this project is a machine learning pipeline that includes the following steps:

1.  **Data Collection and Analysis:** Loading and exploring the PIMA Diabetes Dataset.
2.  **Data Preprocessing:** Cleaning and preparing the data for the model. This includes handling missing values and standardizing the data.
3.  **Model Training:** Splitting the data into training and testing sets and training a Support Vector Machine (SVM) classifier.
4.  **Model Evaluation:** Assessing the model's performance using accuracy metrics.
5.  **Prediction System:** Creating a function to take new data as input and predict the outcome (diabetic or not diabetic).

---

### **Technologies Used**

* **Python:** The primary programming language.
* **Google Colab:** The environment where the project was developed.
* **Pandas:** For data manipulation and analysis.
* **NumPy:** For numerical operations, especially with arrays.
* **Scikit-learn:** The machine learning library used for data preprocessing, model training, and evaluation.

---

### **Dataset**

The project uses the `diabetes.csv` file, which contains the PIMA Diabetes Dataset. This dataset includes medical predictor variables and one target variable (`Outcome`).

| Column                     | Description                                            |
| -------------------------- | ------------------------------------------------------ |
| `Pregnancies`              | Number of times pregnant                               |
| `Glucose`                  | Plasma glucose concentration a 2 hours in an oral glucose tolerance test |
| `BloodPressure`            | Diastolic blood pressure (mm Hg)                       |
| `SkinThickness`            | Triceps skin fold thickness (mm)                       |
| `Insulin`                  | 2-Hour serum insulin (mu U/ml)                         |
| `BMI`                      | Body mass index (weight in kg/(height in m)^2)         |
| `DiabetesPedigreeFunction` | Diabetes pedigree function                             |
| `Age`                      | Age in years                                           |
| `Outcome`                  | Class variable (0: Not Diabetic, 1: Diabetic)          |

---

### **Results**

The SVM model achieved a final accuracy of **77.27%** on the test data.
