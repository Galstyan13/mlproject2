Project: Pre-Interview Acceptance Prediction
Overview
This project aims to predict pre-interview acceptance for job applicants based on a dataset available on Kaggle. The task involves using machine learning techniques to classify whether a candidate will be accepted for an interview, given various features about the candidate. We will explore the use of different classification models to solve this problem, including Naive Bayes and K-Nearest Neighbors (KNN), to compare their performance.

Dataset
The dataset used in this project is provided by raneemrefaie. The dataset contains several features regarding job applicants, such as:

Candidate Attributes: Information about the candidates (e.g., education, experience).
Interview Acceptance: Whether the candidate was accepted for an interview (binary target variable).
The data is split into input features and the target variable (interview acceptance), which makes it suitable for classification tasks.

Libraries Used
The following Python libraries were used in this project:

pandas: For data manipulation and analysis.
pandas is used to load the dataset, clean the data, and perform data wrangling tasks.
numpy: For numerical operations.
numpy is used for handling arrays and performing numerical calculations on the dataset.
scikit-learn: For machine learning algorithms and preprocessing.
scikit-learn provides the implementation of the Naive Bayes and KNN algorithms. It is also used for splitting the data, evaluating model performance, and performing scaling (if necessary).
matplotlib and seaborn: For data visualization.

These libraries are used to visualize distributions, correlations, and model performance metrics (e.g., confusion matrix).
Kaggle API: To download the dataset from Kaggle.

Steps
Data Loading and Exploration:

The dataset was loaded using pandas.read_csv() to explore the features and target variable.
Basic exploratory data analysis (EDA) was performed to check for missing values and understand the distribution of data.
Preprocessing:

Missing values were handled (if any).
Categorical variables were encoded into numerical formats using one-hot encoding or label encoding.
Modeling:

Two classification models were implemented:
Naive Bayes: A probabilistic classifier based on Bayes' theorem.
K-Nearest Neighbors (KNN): A distance-based algorithm for classification.
Logistic Regression: A probabilistic classifier based on sigmoid function.
Model Evaluation:

The models were evaluated using cross-validation and accuracy as the primary metric. Other metrics, such as precision, recall, and F1-score, were also considered for a more comprehensive evaluation.
Models Used
Accuracies of the Models you can see in the code.

Conclusion
This project demonstrates the use of machine learning classification algorithms (Naive Bayes and KNN and Logistic Regression) to predict pre-interview acceptance based on various candidate features.
