# Credit Card Fraud Detection

## Overview
This project addresses the challenge of credit card fraud detection using advanced machine learning models. The study focuses on a highly imbalanced dataset featuring transactions from European cardholders over a two-day period in September 2013. The aim is to effectively identify fraudulent transactions using various machine learning models, considering the class imbalance through specific data handling techniques.

## Models
- **Decision Trees and Random Forest:** These models are used both as baseline models and for advanced analytics. The Random Forest model, in particular, is emphasized for its effectiveness in managing the unbalanced dataset. It leverages ensemble learning techniques, which involve multiple decision trees to improve classification accuracy and robustness, making it particularly adept at handling the skewed data distribution found in fraud detection tasks.
- **Feedforward Neural Network (FNN):** This model is utilized for fraudulent transaction classification, with a specific focus on addressing the challenges posed by class imbalance.
- **Autoencoder:** Employed for anomaly detection, this model identifies unusual patterns that could indicate fraud, learning to distinguish normal from anomalous behavior in transaction data.
- **Data Handling Techniques:** To further address the imbalance in the dataset, the project incorporates techniques such as the Synthetic Minority Over-sampling Technique (SMOTE) for oversampling and various undersampling methods. These techniques help to balance the dataset, thereby improving the performance and generalizability of the models.

## Data Description
The dataset contains transactions over a two-day period in September 2013 from European cardholders. Due to confidentiality, the features are transformed using PCA, except for 'Time' and 'Amount'. The 'Time' feature represents seconds elapsed between each transaction and the first transaction, and
