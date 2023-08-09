# CodeClause Internship Churn Prediction in Telecom Industry using Logistic Regression
### Data Preprocessing:
Loaded necessary libraries and suppressed warnings.
Loaded the dataset using pandas.
Cleaned the data by removing rows with missing values in the 'TotalCharges' column.
Encoded categorical variables using label encoding.
Converted the 'TotalCharges' column to a numeric format.
Scaled the feature variables using StandardScaler.
Split the data into training and testing sets.
Applied Synthetic Minority Over-sampling Technique (SMOTE) to handle the class imbalance issue.

### Exploratory Data Analysis:
Visualized the distribution of churn using both a bar chart and a pie chart.
Explored the distribution of payment methods.
Plotted kernel density estimation (KDE) plots to show the distribution of 'MonthlyCharges' and 'TotalCharges' based on churn status.
Created a correlation heatmap to visualize the relationships between features.

### Logistic Regression Modeling:
Created feature and target variables.
Split the oversampled data into training and testing sets.
Built a logistic regression model.
Made predictions on the test data.
Plotted a confusion matrix heatmap to visualize the model's performance.
Generated a classification report, including precision, recall, and F1-score metrics.
