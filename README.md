# Credit Score Classification Using Random Forest

This project aims to classify credit scores using a Random Forest classifier, a robust and versatile ensemble learning technique. Random Forest constructs multiple decision trees during training and determines the final class based on the majority vote from these trees. This method enhances predictive accuracy and reduces overfitting.

## Overview

Credit scoring is a fundamental process in the financial sector, used to evaluate the creditworthiness of applicants. In this project, we leverage Random Forest to classify credit scores based on a range of financial attributes and applicant information. The objective is to predict whether a credit applicant is a good or bad credit risk.

## Key Components

- **Data Preparation**: The dataset contains various features related to credit applicants, including income, loan amount, and credit history. We preprocess the data by addressing missing values, encoding categorical variables, and normalizing numerical features to ensure a high-quality input for the model.

- **Model Training**: We utilize the Random Forest algorithm to train our model on the prepared dataset. By aggregating the predictions from multiple decision trees, Random Forest enhances classification accuracy and robustness.

- **Evaluation**: The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score. We also apply cross-validation techniques to verify the model’s generalizability.

- **Visualization**: We visualize feature importance to identify the most influential factors affecting credit scoring decisions. This insight aids in interpreting the model and making data-driven decisions.

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/HadiaTahir/Credit-Score-Clasification.git
   ```

2. **Install Dependencies**:
   Ensure you have all necessary libraries installed:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Code**:
   Execute the main script to train the Random Forest model and assess its performance:
   ```bash
   python main.py
   ```

## Contributions

Contributions are welcome! Feel free to submit issues or pull requests to enhance the project. Your feedback and improvements are greatly appreciated.

