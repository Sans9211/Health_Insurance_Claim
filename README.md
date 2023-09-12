# Prediction of Health Insurance Using Machine Learning
Certainly, here are the key bullet points for your project's storytelling on GitHub:

## Dataset Gathering
   - Obtained the health insurance claim dataset in CSV format from Kaggle.

## Data Preparation:
   - Converted the CSV data into a Pandas DataFrame for analysis.

## Exploratory Data Analysis (EDA):
   - Explored the dataset, checking data types, statistical information, size, and identifying outliers using the Interquartile Range (IQR).
   - Visualized outliers using box plots for better understanding.

## Feature Engineering:
   - Addressed outliers in the data, ensuring data integrity.
   - Handled missing values by imputing with the mean.
   - Encoded categorical values into numerical representations.
   - Applied standardization to handle outliers effectively.

## Feature Selection**:
   - Selected relevant features by analyzing correlations to the target variable.

## Model Building:
   - Split the dataset into training and testing sets for model evaluation.
   - Utilized three machine learning algorithms: Logistic Regression, Decision Tree, and Random Forest.

## Logistic Regression:
   - Performed binary classification due to two classes in the target column.
   - Achieved an accuracy of 88% on the training set and 87% on the testing set.

## Decision Tree Algorithm:
   - Addressed overfitting issues by tuning hyperparameters.
   - Achieved an accuracy of 84% on the training set and 82% on the testing set.

## Random Forest Algorithm:
   - Achieved a high accuracy of 96% on the training set and 94% on the testing set.
   - Conducted hyperparameter tuning to optimize the model's performance.

## Conclusion:
    - The Random Forest algorithm yielded the best results, with a 96% accuracy on the training set and 94% accuracy on the testing set.
    
