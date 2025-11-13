📘 Churn Prediction System

📌 Overview

A machine learning system to predict customer churn.
Three models were tested using cross_val_score:

Decision Tree

XGBoost

Random Forest (Best Performance)


Random Forest achieved the highest accuracy and cross-validation score, so it was selected as the final model.




🛠 Tools & Methods

Pandas, NumPy – data processing

LabelEncoder – categorical encoding

SMOTE – oversampling imbalanced classes

Matplotlib – visualizations

Classification Report, Confusion Matrix, Accuracy Score – evaluation metrics





🔑 Key Outcomes

Identified the best-performing model (Random Forest)

Improved minority-class prediction using SMOTE

Achieved strong accuracy and balanced classification metrics

Built a reproducible churn prediction pipeline





⚙️ Running the Project

pip install -r requirements.txt