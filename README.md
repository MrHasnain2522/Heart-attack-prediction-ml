# project title:
  Heart Attack Risk Prediction using Machine Learning


# intro:
  Cardiovascular diseases are one of the leading causes of death worldwide, and early detection of heart-related conditions can save countless lives.
  This project uses machine learning techniques to predict the risk of a heart attack based on various medical indicators such as age, blood pressure,
  cholesterol levels, and more.
  By training and evaluating different classification algorithms, the model aims to assist medical professionals and individuals in identifying high-risk,
  cases and taking preventive action. This project is a step towards leveraging AI for healthcare and preventative medicine.

# Objective:
  To develop a machine learning model that predicts whether a person is likely to experience a heart attack based on historical health data.

# Features:

- **Age** – Age of the patient  
- **Sex** – Gender (0 = female, 1 = male)  
- **cp** – Chest pain type (4 types)  
- **trestbps** – Resting blood pressure  
- **chol** – Serum cholesterol in mg/dl  
- **fbs** – Fasting blood sugar > 120 mg/dl  
- **restecg** – Resting electrocardiographic results  
- **thalach** – Maximum heart rate achieved  
- **exang** – Exercise-induced angina  
- **oldpeak** – ST depression induced by exercise  
- **slope** – Slope of the peak exercise ST segment  
- **ca** – Number of major vessels (0–3) colored by fluoroscopy  
- **thal** – Thalassemia (normal/fixed defect/reversible defect)  
- **target** – 1 = risk of heart attack, 0 = low risk

#  ML Workflow:
 1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical features
   - Feature scaling

2. **Exploratory Data Analysis (EDA)**
   - Correlation matrix
   - Histograms & pair plots
   - Target distribution

3. **Model Training**
   - Logistic Regression
   - Random Forest Classifier
   - K-Nearest Neighbors
   - Support Vector Machine (SVM)

4. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Precision, Recall, F1-Score
   - ROC-AUC Curve

# Technologies Used:
 Python
 pandas
 matplotlib
 seaborn
 numpy
 scikit_learn

# Future Improvements
Hyperparameter tuning with GridSearchCV
Deploy as a web app using Streamlit or Flask
Add feature importance plots
Test on real-time or larger datasets
 
