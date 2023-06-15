# Naive-Bayes -Classification Problem
In this machine learning model, we are working with the Social Network Advertisement dataset ( taken from Kaggle), which is used to predict whether a user has purchased a product based on certain user information.

The dataset consists of five columns: User ID, Gender, Age, Estimated Salary, and Purchased. The User ID column is unique for each user and does not contribute to predicting the target variable,
so it is excluded from the features. The remaining features used for training the model are Gender, Age, and Estimated Salary. The target variable is Purchased, which contains binary values (0 and 1) indicating whether the user has made a purchase.

To prepare the data, we convert the categorical variable Gender into a numeric format using label encoding. Then, we split the dataset into training and testing sets and apply feature scaling to ensure consistent scales across the features.

Next, we train the machine learning model using the Naive Bayes algorithm. Naive Bayes is a classification algorithm that works well with categorical features like Gender. By fitting the model on the training data, it learns the patterns and relationships between the features and the target variable.

After training the model, we evaluate its performance using various evaluation metrics. These metrics help us understand how well the model is performing in terms of accuracy, F1 score and area under ROC curve.
Based on the evaluation results, we can assess the model's effectiveness in predicting whether a user will make a purchase.

Finally, we can use the trained model to make predictions on new or random values from the dataset. By providing the Gender, Age, and Estimated Salary values as input to the model, we can predict the corresponding Purchased value, indicating whether the user is likely to make a purchase or not.
