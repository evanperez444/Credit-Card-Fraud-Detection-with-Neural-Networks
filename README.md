# Credit Card Fraud Detection using Neural Networks

![image](https://github.com/user-attachments/assets/3bfc7794-198d-4380-97ec-0c052bcc8c6a)


- Original 2023 CUNY Tech Prep Authors: Evan Perez, Anthony Poon, and Jonathan Shields
- Continued in 2024 by Evan Perez
- Link to CUNY Tech Prep Repo: (https://github.com/anthonypoon12/CTP-Team-2-Final-Project)
  
- In this project, we aim to expand upon current methods of binary classification of fraudulent credit card transactions in a synthesized dataset. Current methods with this dataset have been with Support Vector Machine (SVM) and Logisitc Regression. We propose a neural network as it can take advantage of the large number of samples within the dataset and potentially pick out complex patterns effectively.
- In this notebook, we explore the dataset's features by checking for multicollinearity, analyzing feature distributions and class distribution, and augmenting the dataset by appending a new column called "Per Change" which represents the percent change from the beginning of a transaction to the end of the transaction.
- We implement a leakyReLu activation function to take into account the negative values that our augmented dataset contains. We also perform the Synthetic Minority Oversampling Technique to make up for our dataset's class imbalance. 
- Variance Inflation Factor (VIF) is implemented to give a better view of multicollinearity in our features by comparing each feature's linearity against all other features. This complements our feature matrix which only highlights pairwise relationships
- Our results achieve an accuracy of over 90% and a recall of around 80%. This means that our solution is able to correctly identify fraudulent transactions around 80% of the time and correctly classify fraud/non-fraud samples over 90% of the time.
-  We leave this work open for exploration in implementing dimensionality reduction techniques such as principal component analysis to further enhance detection capabilities and model efficiency.

