# Data Science Awareness

Data science is not about:
1. Using the latest tools
2. Plotting the best graphs
3. Building the best ML model
4. Having the fancy title "Data Scientist"

Data science is about:
1. Understanding the business problem
2. Being curious to understand the data
3. Getting insights from data to solve the problem
4. Convincing stakeholders to take action

Remember,
You're a problem solver, Get the foundation right. 💪💪

🚀 If you just start your machine learning journey, you must learn about data splitting.

Splitting data is a process of splitting the original data into various datasets. The data is typically split into training, validation, and test sets.

Why data splitting? It's important to splitting the machine learning model as it ensures the model can generalize well to new, unseen data.

There are also several reasons for splitting the data into three kinds of datasets, including:

👉 Training set: The training set is used to train the model. The model learns patterns and relationships between input features and target labels.

👉Validation set: The validation set is used for model selection and hyperparameter tuning. By evaluating the model's performance on the validation set, you can prevent overfitting and adjust the model's hyperparameters.

👉Test set: The test set assesses the model's performance on completely unseen data. This gives an unbiased estimation of the model's generalization ability.

However, there are still a few common misconceptions related to data splitting, including:

🚨Using a single dataset for both training and evaluation will provide accurate performance estimates.

Truth: This approach leads to overfitting, as the model learns to perform well on the specific dataset but may fail to generalize to new, unseen data.

🚨 The larger the training set, the better the model.

Truth: While having more training data generally improves model performance, it's essential to maintain a balance between training, validation, and test sets. Allocating significant data to the validation and test sets ensures robust performance evaluation and prevents overfitting.

🚨Data splitting is not necessary for small datasets.

Truth: Even with small datasets, splitting data is crucial to prevent overfitting and assess model performance accurately. In such cases, cross-validation can be employed to make the most of the limited data.

🚨Randomly splitting data always guarantees a good model evaluation.

Truth: Random splitting is a common approach, but it may not be suitable for all cases. For time-series data, maintaining the temporal order is essential. In cases with class imbalance, stratified sampling should be used to ensure the proportion of classes is maintained in each subset.

Remember that data splitting is important to create a reliable and robust machine learning model. There are various techniques and considerations to ensure the splitting process is effective for your problem.
