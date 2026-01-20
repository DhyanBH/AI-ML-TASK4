# AI-ML-TASK4
AI & ML Internship: Task 4 - Feature Preprocessing
📌 Project Overview
This repository contains the implementation of Task 4 for the AI & ML Internship. The objective was to perform feature engineering on the Adult Income Dataset to prepare it for machine learning algorithms.  
🛠️ Implementation Steps
Feature Identification: Classified data into categorical and numerical features.  
Label Encoding: Applied to ordinal features where a mathematical order exists.  
One-Hot Encoding: Applied to nominal features where no inherent order exists.  
Feature Scaling: Utilized StandardScaler to normalize numerical features, ensuring a mean of 0 and a standard deviation of 1.  
Data Preparation: Compared model readiness before and after scaling to ensure data consistency.  
🧠 Key Insights (Interview Prep)
Why Scaling? It prevents features with larger magnitudes from dominating the model and ensures faster convergence during training.  
Encoding Strategy: Label encoding is used for ranked data, while One-Hot encoding is used to treat categories as independent entities.  
Affected Algorithms: Scaling is vital for distance-based models like KNN and SVM, as well as gradient-based models.
