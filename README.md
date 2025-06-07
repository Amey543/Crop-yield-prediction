# 🌾 Crop Yield Prediction Web Application
A full-stack web application built with Flask, HTML, and Bootstrap that predicts crop yield per country based on user inputs like crop type, average rainfall, pesticide usage, year, and average temperature. The machine learning model used is KNeighborsRegressor, selected based on model performance metrics.

## 🔍 Features
- 🌱 Predict crop yield based on agricultural and climatic inputs  
- 🤖 Machine Learning backend with multiple model comparisons  
- 🧼 Data preprocessing using OneHotEncoder and StandardScaler  
- 🌐 Responsive UI using HTML and Bootstrap  
- 🔄 Real-time interaction between frontend and Flask backend  

## 🚀 Technologies Used
- Frontend: HTML, Bootstrap  
- Backend: Flask (Python)  
- Machine Learning Models: KNeighborsRegressor, Linear Regression, Lasso, Ridge, Decision Tree Regressor  
- Data Processing: Pandas, NumPy  
- Model Evaluation Metrics: Mean Squared Error (MSE), R² Score  

## 📊 Model Performance

The following regression models were evaluated on the dataset. Performance metrics are based on Mean Squared Error (MSE) and R² Score:

| Model                  | MSE              | R² Score       |
|------------------------|------------------|----------------|
| Lasso                  | 1,822,127,464.77 | 0.7486         |
| Ridge                  | 1,822,594,694.32 | 0.7485         |
| KNeighbors Regressor   | 117,396,514.97   | 0.9838         |
| Decision Tree Regressor| 171,061,526.88   | 0.9764         |

> 🔍 **Note:** KNeighbors Regressor was chosen for deployment due to its superior performance in both MSE and R² metrics.
