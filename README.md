# E-commerce Customer Device Usage Analysis
This project analyzes customer behaviour on an e-commerce platform using data from [Kaggle](https://www.kaggle.com/datasets/iyadavvaibhav/ecommerce-customer-device-usage/data).
The goal is to explore the relationship between customer usage patterns (across devices) and their yearly spending.

**Note:** This is a training project. This means that the data is not real and the project is for education purposes only.

## Dataset Overview
- **Source**: [Kaggle- Ecommerce Customer Device Usage](https://www.kaggle.com/datasets/iyadavvaibhav/ecommerce-customer-device-usage/data)
- **File**: ecommerce.csv
- **Size**: 500 entries

## Features
| Column                      |   Description                               |
|-----------------------------|---------------------------------------------|
| 'Email'                     | Customer email(not used in modeling)        |
| 'Address'                   | Physical Address(not used in modeling)      |
| 'Avatar'                    | Avatar name (not used in modeling)          |
| 'Avg. Session Length'       | Average session length(in minutes)          |
| 'Time on App'               | Time spent on the mobile app                |
| 'Time on Website'           | Time spent on the website                   |
| 'Length of membership'      | Years as a customer                         |
| 'Yearly Amount spent'       | Target variable (in dollars)                |

## 🎯 Project Goals
- Explore the data with visualizations.
- Build a **linear regression model** to predict yearly spending.
- Evaluate model performance using MAE, MSE, RMSE.
- Interpret feature importance.


## 🛠️ Technologies Used
- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

## 📈 Key Findings

- **Mobile App usage** has a stronger correlation with spending than website usage.
- **Length of membership** is a strong predictor of customer value.
- Linear regression gives a good baseline performance.

## 📉 Model Metrics

- **Mean Absolute Error (MAE)**:8.426091641432116
- **Mean Squared Error (MSE)**: 103.91554136503333
- **Root Mean Squared Error (RMSE)**: 10.193897260863155

Feel free to explore, fork, or contribute — feedback and improvements are always welcome! 