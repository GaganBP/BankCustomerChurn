Overview:
This project analyzes bank customer churn using machine learning techniques to predict which customers are likely to leave the bank. The dataset was sourced from YBI Foundation's public repository, and data preprocessing steps such as encoding, balancing, and scaling were applied to prepare the data for model training. Multiple sampling strategies, including Random Under Sampling (RUS) and Random Over Sampling (ROS), were employed to tackle class imbalance.

Key Data Preprocessing Steps:
Encoding Categorical Variables:

Replaced categorical features like 'Geography' (France, Germany, Spain) and 'Gender' (Male, Female) with numeric values.
Categorical encoding ensures that non-numeric data can be used for model training.
Handling Imbalanced Data:

Applied Random Under Sampling (RUS) and Random Over Sampling (ROS) techniques to address the imbalanced churn dataset.
ROS was found to be the most effective in improving model performance.
Feature Scaling:

Standardized continuous variables such as 'CreditScore,' 'Age,' 'Balance,' and 'Estimated Salary' using feature scaling to improve model convergence.
Model Training and Evaluation:
The project utilized multiple models with different sampling techniques (RUS, ROS).
ROS model produced the best results, achieving 93% accuracy and 98% recall, making it the optimal choice due to its ability to correctly identify customers who will churn.
Link to the Code and Dataset:
Colab Notebook: [https://colab.research.google.com/drive/1-R3rX0WGy-u3bMRdMAg8qlpWd9oOkZ4A?usp=drive_link]
Dataset: [https://github.com/YBI-Foundation/Dataset/raw/main/Bank%20Churn%20Modelling.csv]
