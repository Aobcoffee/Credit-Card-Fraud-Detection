# Credit Card Fraud Detection

## Description
This project analyzes a real-world dataset focused on credit card fraud detection, sourced from Kaggle.

Dataset URL: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Dataset Overview

This project leverages a dataset of credit card transactions from European users, specifically from September 2013.

- **Total Transactions:** 284,807  
- **Fraudulent Transactions:** 492  
- **Fraud Rate:** 0.172% (indicative of a significant imbalance in the data)  

## Data Attributes

1. **V1-V28:**  
   A series of numerical features obtained through Principal Component Analysis (PCA) transformation; original features are confidential.

2. **Time:**  
   Represents the elapsed time in seconds since the first transaction recorded in the dataset.

3. **Amount:**  
   Indicates the financial value of each transaction.

4. **Class:**  
   The target variable where:  
   - **1** signifies a fraudulent transaction  
   - **0** denotes a legitimate transaction

## Conclusion
This project employed two methods for dimensionality reduction: Principal Component Analysis (PCA) and t-Distributed Stochastic Neighbor Embedding (t-SNE) for unsupervised learning. For supervised learning, we tested K-Nearest Neighbors, Decision Tree, and Random Forest classifiers.

The highest accuracy achieved across the models was 89.33%. The K-Nearest Neighbors performed particularly well, demonstrating strong potential for effective fraud detection.
  
## To run the analysis:

1. Clone this repository.
2. Load the dataset and follow the analysis steps outlined in the notebook.

   
## Note
_This notebook has been adapted from coursework at the City University of Hong Kong's SDSC2001._
