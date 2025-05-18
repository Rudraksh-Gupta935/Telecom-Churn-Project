 # "Customer Churn Analysis for the Telecom Industry" by Rudraksh Gupta

# 2. Introduction : "Customer churn, or customer attrition, refers to the phenomenon where customers stop doing business with a company."* "In the highly competitive telecom industry, churn is a critical problem that directly impacts revenue and profitability."

# "This project aims to analyze customer data to predict which customers are likely to churn and to identify the key factors contributing to churn."

# "The goal is to provide actionable insights that can help telecom companies develop effective customer retention strategies."

# 3. Data Source and Description : "The dataset used for this analysis was obtained from Kaggle dataset on Telecom Customer Churn.

# It contains 7043 customer records with:

# i) Customer ID: Unique identifier for each customer.

# ii) Tenure: Length of time the customer has been with the company.

# iii) Monthly Charges: Amount charged to the customer per month.

# iv) Total Charges: Total amount charged to the customer.

# v) Churn: Binary variable indicating whether the customer churned (Yes/No).

# Data preprocessing steps included handling missing values by [imputation with the mean/median], removing irrelevant columns, and converting categorical variables to numerical using one-hot encoding.

# 4. Exploratory Data Analysis (EDA): EDA was performed to understand the characteristics of the data and identify potential patterns related to churn.

# The churn rate in the dataset is 73.46% for the customers stating No and 26.53% for the customers stating Yes, indicating an imbalanced dataset.

# i)A confusion matrix reveals the relationships between different variables, highlighting potential predictors of churn.

# ii)Receiver's Operating Curve(ROC) showing the true positive rates and false positive rates.

# iii)Histogram to understand the range, criteria, central tendency, and skewness of variables like Tenure, Monthly Charges, Total Charges.

# iv)Box Plot to compare the distribution of numerical features across different groups(Churned vs Non-Churned customers)

# v)Bar Plot to count the customers for different categorial features(Contract,Internet Service, Payment Method)

# vi)Churn Analysis to show the churn rate

# vii)Correlation Heatmap for visualising the correlation between numerical features and churn.

# viii)Segment Distribution to compare the characteristics of different customer segments.

# 5.Feature Engineering: “Feature engineering was employed to create new features that could improve the model's predictive power."

# New features created include:
# i)Calculate Tenure Years
# ii)Interaction Feature
# iii)Binning Monthly Changes
# iv)Flag for Online Security

# “These features were designed to capture customer behavior and identify potential drivers of churn."

# 6. Model Selection and Training: A binary classification model was chosen to predict customer churn.
# i)The Logistic Regression model was selected due to its interpretability.
# ii)Random Forest model was selected due to its versatility.
# iii)Gradient Boosting Machine (GBM) model was selected due to its ability to handle non-linear relationships.
# iv)Decision Tree model was selected for its simplicity, interpretability, and ability to handle various data types and missing values.
# "The dataset was split into training and testing sets.”

# 7. Model Evaluation: "The models performance was evaluated on the testing set using the following metrics:
# i)Accuracy: Overall correctness of the predictions.
# a)Logistic Regression: 0.7283483199242783
# b)Decision Tree: 0.8767
# c)Random Forest: 0.8567
# ii)Precision: Ability to correctly identify churned customers.
# a)Decision Tree: 0.8986
# b)Random Forest: 0.8889
# iii)Recall: Ability to find all churned customers.
# a)Decision Tree: 0.8581
# b)Random Forest: 0.8258
# iv)F1-score: Harmonic mean of precision and recall.
# a)Decision Tree: 0.8779
# b)Random Forest: 0.8562
# v)AUC-ROC: Ability to distinguish between churned and non-churned customers.
# a)Decision Tree: 0.8850
# b)Random Forest: 0.9206

# “A confusion matrix visualizes the number of true positives, true negatives, false positives, and false negatives."
# "The model achieved good predictive accuracy. “

# 8. Conclusion: This project successfully developed a model to predict customer churn in the telecom industry.
# "Key drivers of churn were identified, including Technical Issues"
# “Targeted retention strategies were proposed to address the needs of different customer segments."
# "By implementing these recommendations, telecom companies can reduce churn, improve customer loyalty, and increase profitability."
# "Future work could include incorporating real-time data, and exploring more advanced models.”
