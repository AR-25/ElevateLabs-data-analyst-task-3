# ElevateLabs-data-analyst-task-3

# Task 3: Predictive Modeling - Key Findings

This project focused on building a predictive model to identify customers who are likely to respond to a marketing campaign.

* **Objective**: To build a binary classification model using the cleaned customer dataset.
* **Model Used**: A Logistic Regression model was chosen for its simplicity and interpretability as a baseline model.
* **Feature Engineering**: A `customer_tenure` feature was created, and categorical variables like `education` and `marital_status` were one-hot encoded to prepare the data for modeling.
* **Performance**: The model achieved an accuracy of approximately **88%** on the unseen test data. The classification report shows strong performance in identifying non-responders, but has lower recall for responders, which is typical for imbalanced datasets and suggests areas for future improvement.
* **Conclusion**: This baseline model provides a solid foundation for predicting customer response. It could be used to create more targeted marketing campaigns, potentially increasing conversion rates and reducing costs.
