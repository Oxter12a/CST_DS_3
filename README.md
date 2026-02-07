📊 Decision Tree Classifier – Bank Marketing Dataset
📌 Project Overview
Google collab file:-https://colab.research.google.com/drive/1H9m5osH7jAFUvmcAXafgOFySb1pEiET6?usp=sharing
This project implements a Decision Tree Classification model to predict whether a customer will purchase a product/service (term deposit) based on their demographic and behavioral data.
The model is built using the Bank Marketing Dataset from the UCI Machine Learning Repository.

This project is completed as Task 3 of a Data Science / Machine Learning learning series.

🎯 Objective

To build and evaluate a Decision Tree Classifier that can:

Analyze customer attributes

Predict customer purchase behavior (yes / no)

Provide interpretable decision rules for business insights

📂 Dataset Information

Dataset Name: Bank Marketing Dataset

Source: UCI Machine Learning Repository

File Used: bank.csv

Target Variable: y

yes → Customer purchased the product

no → Customer did not purchase

Sample Features

age

job

marital

education

balance

housing

loan

contact

campaign

previous

poutcome

🛠️ Tools & Technologies Used

Python

Jupyter Notebook / Google Colab

Libraries

pandas

numpy

matplotlib

seaborn

scikit-learn

🔄 Project Workflow

Dataset loading and exploration

Data preprocessing

Handling categorical variables

Feature encoding

Train-test split

Model building using Decision Tree Classifier

Model evaluation

Accuracy score

Confusion matrix

Classification report

Decision tree visualization

⚙️ Model Details

Algorithm: Decision Tree Classifier

Criterion: Gini Index

Max Depth: 5

Train-Test Split: 80% – 20%

📈 Results

The model successfully predicts customer purchase behavior.

Important influencing features include contact duration, balance, and campaign details.

Decision Tree visualization helps understand customer decision paths clearly.

✅ Advantages

Easy to interpret and visualize

Handles both categorical and numerical data

Useful for business and marketing decision-making

⚠️ Limitations

Can overfit if tree depth is too high

Performance may be lower compared to ensemble models

📌 Conclusion

A Decision Tree Classifier was successfully developed to predict customer purchase behavior using the Bank Marketing dataset. The project demonstrates the application of supervised learning techniques and highlights the importance of data preprocessing and model interpretability in real-world scenarios.

📎 Future Improvements

Hyperparameter tuning

Try ensemble models like Random Forest or XGBoost

Feature importance analysis

👤 Author

Kishor S
Engineering Student at govt Engineering college Palakkad | Data Science & Machine Learning Enthusiast
linkdln:-https://www.linkedin.com/in/kishor-a1164132a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
