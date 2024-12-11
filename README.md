Loan Status Prediction Challenge
This challenge focuses on predicting loan approval status using machine learning. The workflow includes data exploration, model training, and selecting the best-performing model.

Repository Overview
eda.ipynb: Conducts Exploratory Data Analysis (EDA) to uncover insights and visualize the dataset.
model_.py: Contains the model training pipeline for Logistic Regression and Random Forest models.
model_selection.ipynb: Compares models using metrics like accuracy, precision, and recall to determine the best one.
Key Steps
EDA: Explore the dataset and visualize features for better understanding.
Model Training: Run model_.py to train and evaluate models.
Model Selection: Use model_selection.ipynb to finalize the best model based on evaluation results.
Results
Random Forest: Accuracy:  0.7602310037523452
Logistic Regression: Accuracy: 0.7646282833020638
The Random Forest model was selected for its superior accuracy and ability to handle complex relationships in the data. It was further improved using hyperparameter tuning.