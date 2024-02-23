## Performance-Metrics
* This project investigates the performance of a Logistic Regression model in predicting heart disease based on clinical data. The analysis explores various performance metrics, including accuracy, precision, recall, F1-score, and confusion matrix, to evaluate the model's effectiveness.

*Data:*
* The project utilizes the UCI Heart Disease dataset, publicly available for research purposes. It contains 14 attributes for each patient, including demographics, medical history, and the presence of heart disease.

*Methodology:*

1. Data Preprocessing:
* Load the dataset using pandas.
* Explore data distribution and check for missing values.
* Handle missing values appropriately 
* Separate features (X) and target variable (y).
* Split data into training and testing sets for model evaluation.

2. Model Training:
* Create and train a Logistic Regression model using scikit-learn.
* Consider potential hyperparameter tuning (regularization) to optimize performance.

3. Model Evaluation:
* Evaluate the model on the testing set using various metrics:
* Accuracy: Percentage of correctly predicted outcomes.
* Precision: Ability to correctly identify true positives.
* Recall: Ability to identify all true positives.
* F1-score: Harmonic mean of precision and recall.
* Confusion Matrix: Visualization of true and false positives/negatives.
* Interpret the results and their implications for heart disease prediction.

4. Visualization:
* Creating data visualizations to explore feature relationships and model performance.
