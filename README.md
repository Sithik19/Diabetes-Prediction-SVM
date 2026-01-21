# Diabetes Prediction using SVM

This project focuses on predicting whether a person has diabetes using the
**Pima Indians Diabetes Dataset** and a **Support Vector Machine (SVM)** classifier.
It includes data analysis, visualization, model training, and evaluation.
The project is suitable for **machine learning placements and interviews**.

---

## Dataset Details

- Dataset Name: Pima Indians Diabetes Dataset
- Total Records: 768
- Features: 8
- Target Variable: `Outcome`

### Target Values
- `0` → Non-Diabetic
- `1` → Diabetic

### Features
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

---

## Data Visualization

The following visualization shows the relationship between **Glucose, BMI, Age**
and how they influence diabetes outcomes.

![Pairplot Visualization]
<img width="822" height="741" alt="image" src="https://github.com/user-attachments/assets/8a274086-e17a-4392-85b1-3358efbdcd2f" />


### Key Observations
- Diabetic patients tend to have **higher glucose levels**
- BMI and Age also show noticeable patterns
- Data distribution is **non-linear**, making SVM a suitable choice

---

## Machine Learning Model

- Algorithm: Support Vector Machine (SVM)
- Kernel Used: RBF (Radial Basis Function)
- Feature Scaling: StandardScaler
- Train-Test Split: 80% training, 20% testing

---

## Model Evaluation

The model was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

**Accuracy Achieved:** ~75–80%

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## How to Run the Project

1. Clone the repository
```bash
git clone https://github.com/Sithik19/Diabetes-Prediction-SVM.git

2.Navigate to the project folder
```bash
cd Diabetes-Prediction-SVM
