# Hiring-Decision-Prediction-System
📌 Project Overview
This project builds a machine learning classification model to predict whether a candidate will be selected for hiring based on various features such as education level, experience, technical skills, aptitude score, certifications, and interview performance.
The goal of this project is to support fair and data-driven recruitment decisions by analyzing candidate attributes using multiple machine learning algorithms and selecting the best-performing model.

🎯 Objectives
Perform data preprocessing and cleaning
Handle missing values and duplicate records
Encode categorical variables
Handle class imbalance using SMOTE
Train multiple machine learning models
Compare model performance
Select the best-performing model
Deploy prediction interface using Gradio

📊 Dataset Features Used
The dataset includes candidate attributes such as:
Gender
Age
Education Level
Years of Experience
Skill Score
Aptitude Test Score
Technical Test Score
Communication Score
Certifications Count
Internship Experience
Hiring Decision (Target Variable)

⚙️ Technologies Used
Python 🐍
Pandas & NumPy
Matplotlib & Seaborn
Scikit-learn
SMOTE (Imbalanced-learn)
Pickle
Gradio (for deployment interface)

🧹 Data Preprocessing Steps

The following preprocessing steps were performed:
Filled missing categorical values using mode
Filled missing numerical values using mean
Removed duplicate records
Applied Label Encoding on categorical variables
Removed unnecessary columns like Candidate_ID
Handled class imbalance using SMOTE

🤖 Machine Learning Models Used

Three classification models were trained:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier

📈 Model Performance
Model accuracy comparison:
Logistic Regression → 83%
Decision Tree → 96.66%
Random Forest → 96.37%
✅ Decision Tree Classifier performed best and was selected as the final model.

💾 Model Deployment
The final trained model was saved using:
decision_tree_model.pkl
encoders.pkl
A Gradio web interface was created to allow users to input candidate details and get hiring predictions interactively.
