# PRODIGY_DS_03

## Decision Tree Classifier for Customer Prediction

### Objective:

To build a Decision Tree Classifier that predicts whether a customer will subscribe to a term deposit based on demographic and behavioral data.

### Dataset Used:

Bank Marketing Dataset – UCI Machine Learning Repository

### Tools & Libraries:

Python

Pandas

NumPy

Scikit-learn (DecisionTreeClassifier, train_test_split, accuracy_score)

Matplotlib / Seaborn

### Steps Involved:

Loaded and explored the dataset to understand feature types and distributions.

Cleaned the dataset by handling missing values and ensuring proper data types.

Performed label encoding and one-hot encoding on categorical variables (e.g., job, marital status, education).

Split the dataset into training and testing sets using train_test_split.

Trained a Decision Tree Classifier using Scikit-learn.

Evaluated the model using accuracy score, confusion matrix, and classification report.

Visualized the structure of the decision tree to understand decision paths.

Plotted feature importance to see which variables influenced predictions the most.

### Key Insights:

Features such as contact method, previous marketing outcomes, job type, and duration of the last call had a strong impact on whether a customer would subscribe.

The decision tree provided a clear and interpretable model for classification.

The model performed well on the test set, showing a good balance between precision and recall.

### Skills Applied:

Data preprocessing and feature encoding

Supervised machine learning using decision trees

Model evaluation techniques (accuracy, precision, recall, F1-score)

Tree visualization and feature importance analysis
