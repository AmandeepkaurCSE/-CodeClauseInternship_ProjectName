## CodeClause Internship Churn Prediction in Telecom Industry using Logistic Regression
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

### Screenshot
![Screenshot (158)](https://github.com/AmandeepkaurCSE/-CodeClauseInternship_ProjectName/assets/64351796/40b19c6a-9fce-4132-8760-479c92aad715)

![Screenshot (159)](https://github.com/AmandeepkaurCSE/-CodeClauseInternship_ProjectName/assets/64351796/fa77d21d-0e63-4e7f-b550-d54a50434ef7)

![Screenshot (160)](https://github.com/AmandeepkaurCSE/-CodeClauseInternship_ProjectName/assets/64351796/74d23d82-77fa-4675-806d-42c79ee054b3)

![Screenshot (161)](https://github.com/AmandeepkaurCSE/-CodeClauseInternship_ProjectName/assets/64351796/69ccb03c-0620-455d-ad9e-40fcc3c850c0)


### Logistic Regression Modeling:
Created feature and target variables.
Split the oversampled data into training and testing sets.
Built a logistic regression model.
Made predictions on the test data.
Plotted a confusion matrix heatmap to visualize the model's performance.
Generated a classification report, including precision, recall, and F1-score metrics.

![Screenshot (157)](https://github.com/AmandeepkaurCSE/-CodeClauseInternship_ProjectName/assets/64351796/602537f7-ee2b-48eb-a162-9b5691c53adb)

