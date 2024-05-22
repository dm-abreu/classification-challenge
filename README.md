# Classification-challenge

# Module 13

# Background

At our Internet Service Provider (ISP), we are enhancing the email filtering system to improve our customers' experience. We have a dataset that classifies emails as spam or not spam. Our goal is to develop a supervised machine learning (ML) model that can accurately detect spam emails.

We will create two classification models:
- Logistic Regression Model
- Random Forest Model

We will evaluate which model is more accurate at detecting spam.


## Before You Begin
- Create a new repository named `classification-challenge`.
- Clone the repository.
- Add the `spam_detector.ipynb` starter file.
- Push the changes to GitHub or GitLab.

## Instructions
The challenge consists of:
1. Splitting the data into training and testing sets.
2. Scaling the features.
3. Creating a logistic regression model.
4. Creating a random forest model.
5. Evaluating the models.


### Split the Data into Training and Testing Sets
- Read the data into a Pandas DataFrame from spam-data.csv.
- Predict which model will perform better.
- Create labels (y) from the "spam" column.
- Create features (X) from the remaining columns.
- Check the balance of labels using `value_counts`.
- Split the data using `train_test_split`.

### Scale the Features
- Create a `StandardScaler` instance.
- Fit the scaler with the training data.
- Scale both training and testing features.

### Create a Logistic Regression Model
- Fit a logistic regression model using scaled training data (`X_train_scaled`, `y_train`) with `random_state=1`.
- Save predictions on testing data labels using `X_test_scaled`.
- Evaluate the model's performance using the accuracy score.

### Create a Random Forest Model
- Fit a random forest classifier model using scaled training data (`X_train_scaled`, `y_train`).
- Save predictions on testing data labels using `X_test_scaled`.
- Evaluate the model's performance using the accuracy score.

### Evaluate the Models
Answer the following questions:
- Which model performed better?
- How does that compare to your prediction?

## Requirements
Your Jupyter notebook must include:
- A prediction about which model will perform better.
- Creation of labels (y) and features (X).
- Use of `value_counts` to check the balance of labels (y).
- Correct splitting of data into training and testing datasets.
- Creation and fitting of a `StandardScaler` instance.
- Scaling of training and testing features.
- Creation, fitting, and evaluation of a logistic regression model.
- Creation, fitting, and evaluation of a random forest model.
- Answers to evaluation questions.

