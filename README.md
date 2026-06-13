# Diabetes-Prediction-Using-Machine-Learning
📌 Overview
This project analyzes a large-scale diabetes prediction dataset (100,000 samples) using Exploratory Data Analysis (EDA) and machine learning techniques. The primary goal is to identify key risk factors associated with diabetes and build predictive models that can support early detection and prevention strategies.

⚖️ Dataset Summary
Total samples: 100,000

Target variable: diabetes (0 = Non-diabetic, 1 = Diabetic)

Class distribution:

Non-diabetic: 91.5%

Diabetic: 8.5%

This imbalance highlights the importance of using techniques such as SMOTE (Synthetic Minority Oversampling Technique) or class weighting to ensure models do not become biased toward the majority class.

🔍 Exploratory Data Analysis (EDA)
Univariate Analysis: Histograms and boxplots reveal distributions and outliers in clinical biomarkers (e.g., glucose, BMI, insulin).

Bivariate Analysis: Feature distributions compared across diabetic vs. non-diabetic groups.

Correlation Analysis: Heatmaps identify strong predictors such as glucose, BMI, and age.

Class Imbalance Check: Outcome variable distribution confirms skewed dataset.

🤖 Machine Learning Models
Two approaches were tested to evaluate predictive performance:

Logistic Regression – interpretable model showing how each feature influences diabetes risk.

Random Forest Classifier – robust ensemble method ranking feature importance.

📊 Key Metrics
Accuracy – overall correctness of predictions.

Precision & Recall – critical for imbalanced datasets.

F1 Score – balance between precision and recall.

ROC AUC – ability to distinguish between diabetic and non-diabetic cases.

ROC curves were plotted to visually compare model performance.

🧩 Insights
Glucose levels and BMI emerged as the strongest predictors.

Age and Pregnancies also showed significant correlation with diabetes risk.

Handling class imbalance is essential for reliable predictions.
<img width="989" height="722" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/cc59da6a-fca2-4486-8e41-0de0f37cf49a" />

<img width="637" height="526" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/505dc755-eac6-4696-a9c6-ca57a9977b68" />

<img width="1108" height="623" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/3e74c646-9893-4167-a710-0683fe442624" />



