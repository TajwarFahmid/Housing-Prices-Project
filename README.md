# Housing-Prices-Project

Description of the project:
This repository contains my attempt at creating a machine learning model to predict housing prices based on 79 different variables, there were a total of around 1450 entries in the dataset.

What I did:
- cleaned the whole dataset by removing null values and imputing them with suitable replacements such as the median for most numerical columns and "none" for categorical variables.
- Conducted exploratory data analysis to find insights and trends in the data.
- Engineered features to put into our XGBoost model (I chose this model because it is efficient for datasets with both numerical and categorical data).
- Built an XGB model to predict our target variable, the Sale Price. Got an intiaL R^2 score of 0.8635.
- Tuned the hyperparameters of the model by decreasing the learning rate , increasing the number of estimators, and increasing max depth.
- Got a final R^2 score of 0.9109!

Conclusion:
This was a kaggle challenge that I took part in for fun, I learnt a lot from this project and faced a few challenges while completing it such as the overfitting. My first model had an accuracy of 0.92 on the training data but did not do nearly as well on the test data. There were some class imbalances as well in some of the features. Overall, while the accuracy could have been slightly better, I think my model is performing relatively well on a real world dataset. 
