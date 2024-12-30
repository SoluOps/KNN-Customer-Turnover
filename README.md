# Customer Churn Prediction with KNN

This project implements a K-Nearest Neighbors (KNN) classification model to predict customer churn rates, developed during a Le Wagon workshop on 12/04/23. The model analyzes patterns in customer attributes to identify potential customer turnovers, enabling proactive retention measures.

## Dataset

The dataset contains various customer attributes including:
- Credit Score
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Exited (target variable)

## Model Implementation

1. Data visualization with Seaborn
2. Feature importance analysis through permutation importance
3. Train-test split via Scikit-learn
4. KNN model training and implementation
5. Model evaluation using performance metrics

## Results

The model demonstrates the ability to predict customer churn with approximately 73% accuracy when using categorical features only. Key findings include:

- Approximately 20% of customers churned in the dataset
- The model achieved better performance when using both numerical and categorical features (77% accuracy) compared to using categorical features alone (73% accuracy), showing a 4% improvement in prediction accuracy

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Numpy
- Scikit-learn
- Seaborn
