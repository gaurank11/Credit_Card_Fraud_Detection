# Credit Card Fraud Detection

## Overview
This project aims to develop a machine learning model for detecting fraudulent credit card transactions. By leveraging various data analysis techniques and machine learning algorithms, we can effectively identify and classify transactions as legitimate or fraudulent.


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data Exploration](#data-exploration)
- [Model Building](#model-building)
- [Evaluation Metrics](#evaluation-metrics)


## Installation

To run this project, you need to have Python 3.x installed. You can set up a virtual environment and install the required packages using the following commands:

```bash

# Install required packages
pip install numpy pandas seaborn matplotlib scikit-learn imbalanced-learn statsmodels
```

## Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/gaurank11/Credit_Card_Fraud_Detection

   ```

2. **Download the dataset:**
   Download the dataset from [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and place it in the project directory.


## Data Exploration

- The dataset contains 284,807 transactions with 31 features, including time, anonymized features (V1 to V28), amount, and a class label indicating fraud (1) or legitimate (0).
- The data is heavily imbalanced, with 99.83% legitimate transactions and only 0.17% fraudulent transactions.
- Various visualizations are used to understand the distribution of transactions and identify outliers in transaction amounts.

![image](https://github.com/user-attachments/assets/0326b6e8-f90d-4987-bb65-b556a9d6b62a)  ![image](https://github.com/user-attachments/assets/b63f101f-0bf2-49b3-9d09-959a8d57cc93)



## Model Building

The project utilizes the following machine learning algorithms to detect fraud:

- **Logistic Regression**
![image](https://github.com/user-attachments/assets/fba06452-95af-4ec6-9a49-3f3344f4b577)


- **Decision Tree Classifier**
![image](https://github.com/user-attachments/assets/f84a0cff-f585-482c-a90a-f5b3d38e4862)

  
- **Random Forest Classifier**
![image](https://github.com/user-attachments/assets/796a1eac-bd68-41c4-805e-2f5922964fe2)

Additionally, the project addresses class imbalance using the SMOTE technique (Synthetic Minority Over-sampling Technique) to improve model performance.

## Evaluation Metrics

The model's performance is evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- AUC-ROC Curve

![image](https://github.com/user-attachments/assets/3f4ac11d-ef6b-4598-a27f-68063f856453)


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
