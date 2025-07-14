## Traffic Violation Detection using Machine Learning
This project detects traffic violations using real-world data from Indian roads. It uses a rule-based labeling approach combined with a Random Forest classifier. The model is interpretable and evaluated using SHAP values and classic metrics.
## Key Features
Rule-based labeling of violations 
End-to-end preprocessing pipeline with ColumnTransformer  
Random Forest classifier with `class_weight='balanced'`  
Feature importance via both `model.feature_importances_` and SHAP  
Custom evaluation function with classification report + heatmap  
Clean, readable code with visualizations
## Files
trafficviolationProject.ipynb
## Project Overview
Goal: Detect if a driver is violating traffic rules (e.g., over-speeding, no helmet, alcohol level).
Tech Stack: Python, Pandas, Scikit-learn, SHAP, Matplotlib, Seaborn
Model used: Random Forest (with class balancing and hyperparameter tuning)
Explainability: SHAP summary plots and feature importance
## Evaluation 
 Acuuracy: ~97%
 Classification report: Precision, Recall, F1 for violation/no-violation
 Visuals: Heatmap + SHAP plots
 ## Author
 K.Neeli Meghana
 ## If you find this useful or insightful, please consider giving it a star on GitHub


