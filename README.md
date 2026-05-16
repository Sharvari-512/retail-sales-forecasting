# 📊 Retail Sales Forecasting using SARIMA

## 📌 Project Overview
This project focuses on forecasting future retail sales using historical Superstore sales data and time-series forecasting techniques. The project applies SARIMA (Seasonal ARIMA) modeling to analyze sales trends, identify seasonality, and predict future sales performance.
The objective is to build an accurate forecasting model that can help businesses understand future demand patterns and support data-driven decision-making.

## 🎯 Objectives
- Clean and preprocess historical sales data
- Perform time-series analysis
- Identify trends and seasonal patterns
- Build forecasting models using SARIMA
- Evaluate model performance using MAE and RMSE
- Forecast future sales trends

## 🗂️ Dataset
The dataset used is the Superstore retail dataset containing:
- Order Date
- Sales
- Profit
- Quantity
- Category and Sub-Category
- Customer and Regional information

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Scikit-learn

## 📈 Project Workflow

### 1. Data Preprocessing
- Converted `Order Date` into datetime format
- Sorted data chronologically
- Checked for missing values
- Aggregated sales data monthly

### 2. Time-Series Transformation
The transactional sales data was converted into monthly time-series format:

### 3. Time-Series Decomposition
Performed decomposition to identify:
- Trend
- Seasonality
- Residual components

### 4. Model Building
Implemented SARIMA forecasting model to capture:
- Trend
- Seasonality
- Sales fluctuations
Final selected model: SARIMA(2,1,2)(1,1,1,12)

### 5. Model Evaluation
Evaluation metrics used:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## 📊 Final Model Performance
### Metric	Value
- MAE=	11,380
- RMSE= 13,693
The SARIMA model significantly improved forecasting accuracy compared to the initial ARIMA model.

## 📉 Visualizations Included
- Monthly Sales Trend
- Time-Series Decomposition
- Actual vs Predicted Sales
- Future Sales Forecast

## 📌 Key Learnings
- Time-series preprocessing
- Seasonal forecasting using SARIMA
- Trend and seasonality analysis
- Forecast evaluation techniques
- Retail sales forecasting methods

## 🔮 Future Improvements
- Implement Facebook Prophet forecasting
- Add holiday-based forecasting
- Build interactive dashboard using Power BI
- Deploy forecasting model as a web application
- Forecast category-wise sales

## 💡 Conclusion
This project demonstrates how predictive analytics and time-series forecasting techniques can be applied to historical retail sales data to generate meaningful future predictions. The SARIMA model successfully captured seasonal sales behavior and improved forecasting performance.
