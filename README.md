Dataset: The example uses a synthetic dataset with features Weather, Road_Type, Visibility, and Accident (target variable).

Data Preprocessing: Categorical variables (Weather, Road_Type, Visibility) are one-hot encoded for use in the logistic regression model.

Model Training: Logistic regression is chosen as the classification algorithm to predict accidents based on the encoded features.

Model Evaluation: The model's performance is evaluated using a confusion matrix and classification report, showing metrics like precision, recall, and F1-score.

Prediction: A new set of features (new_data) is used to make a prediction on whether an accident is likely to occur based on the trained logistic regression model.
