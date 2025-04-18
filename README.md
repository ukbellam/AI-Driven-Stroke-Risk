Project Overview
The AI-Driven Stroke Risk Prediction project focuses on using artificial intelligence to predict the likelihood of stroke in adults between the ages of 45 and 60. By analyzing medical and lifestyle data, this project aims to build a smart system that can support doctors in catching stroke risks early and taking preventive actions before it's too late.
Objective
The goal of this project is to create a machine learning model that can identify people at high risk of having a stroke. By using real-world data and AI methods, the system helps in early detection, supports clinical decision-making, and encourages proactive healthcare planning to reduce the number of strokes and related complications.
Technologies & Tools Used
    •    Python (Pandas, Sklearn, Matplotlib) – for data analysis, modeling, and visualization
    •    Logistic Regression – selected as the final prediction model
    •    SMOTE – used for balancing the dataset
    •    StandardScaler – for feature scaling
    •    GridSearchCV – for hyperparameter tuning
    •    ROC & PR Curves – to evaluate model performance
Dataset Description
    •    Source: Kaggle Stroke Prediction Dataset
    •    Records: 5,110 patient entries
    •    Features: Age, Gender, Hypertension, Heart Disease, Marital Status, Work Type, Glucose Level, BMI, Smoking Status
    •    Target: Stroke occurrence (1 = Stroke, 0 = No Stroke)
Key Outcomes
    •    Best model: Logistic Regression
    •    ROC AUC Score: 0.8670
    •    Strong recall score helps minimize false negatives
    •    Applied probability calibration for more reliable predictions
    •    Demonstrated prediction on a simulated patient with 81% stroke probability
Challenges Faced
    •    Imbalanced dataset – solved using SMOTE
    •    Model tuning – required cross-validation and careful preprocessing
    •    Data quality – needed to handle missing values and encode categories
    YOUTUBE VIDEO LINK:
    https://youtu.be/qFyiLNnUNqI
 
Outcomes Achieved
    •    Developed a reliable and interpretable model
    •    Improved real-world usability with calibrated probabilities
    •    Aligned results with established research benchmarks
    •    Created a tool that could be integrated into clinical decision support systems in the future
