# Loan Approval Prediction System
*A Machine Learning project to predict loan approvals using Logistic Regression and XGBoost.*

This project predicts whether a loan application will be approved based on applicant details such as income, education, credit history, and property area. The dataset was taken from Kaggle (Loan Prediction Dataset).

---

## Project Overview
- Performed **data cleaning** (handled missing values, removed duplicates, fixed text formatting issues).
- Applied **feature encoding** to convert categorical values into numerical format.
- Trained two models:
  - Logistic Regression → ~80% accuracy
  - XGBoost → ~90% accuracy
- Evaluated performance using accuracy and false rejection rate to ensure genuine customers are not rejected.
- Added some visuals and a basic setup for a Flask app (`app.py`), but my main contribution was **model building and evaluation**.

---

## Tech Stack
- **Languages/Tools:** Python, Pandas, NumPy, Scikit-learn, XGBoost, Jupyter Notebook
- **Optional Demo:** Flask (for future deployment)

---

## Glance of the Project
Below are some images showing the workflow and results of the project:  

![image](https://user-images.githubusercontent.com/81796368/120915010-ff0c1580-c6be-11eb-938f-a73d52332447.png)  

![image](https://user-images.githubusercontent.com/81796368/120915027-1e0aa780-c6bf-11eb-9812-46800011a61c.png)  

---

## Future Work
- Build a simple web app using Streamlit/Flask for easier interaction.
- Try hyperparameter tuning to improve model accuracy.
