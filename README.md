# TASK_2

This project addresses a binary classification problem using three datasets:
Train set: for model training and validation
Test set: for evaluation on unseen data
Blinded test set: for final predictions
Models Used
Logistic Regression
Random Forest
XGBoost
Workflow
Data preprocessing: one-hot encoding and standard scaling
SMOTE applied for class balancing
5-fold cross-validation for model evaluation
Metrics reported: Accuracy, AUROC, Sensitivity, Specificity, F1-score
Output
Each model generates prediction CSVs for test and blind datasets with:
ID, Class_0_Prob, Class_1_Prob columns
How to Run
Install required packages (see requirements.txt)
Run Task_2.ipynb in Jupyter or Colab
Improvements
Try feature selection
Tune hyperparameters further
Add more models (e.g., LightGBM, stacking)


