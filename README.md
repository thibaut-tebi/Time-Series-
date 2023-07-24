## Sales Forecasting Project

#### Overview
Welcome to the Sales Forecasting Project! This repository contains the code, data, and documentation for predicting sales at Corporation Favorita, a leading supermarket retailer in Ecuador. The goal of this project is to develop a robust sales forecasting model using time series analysis and machine learning techniques.

### PROJECT SUMMARY
| Project Name        | Description                                                                                             | Technologies Used                                    | Published Article                                           |
|---------------------|---------------------------------------------------------------------------------------------------------|------------------------------------------------------|-------------------------------------------------------------|
| Sales Forecasting   | Predicting future sales at Corporation Favorita using time series analysis and machine learning models. |SQL, Python, scikit-learn, pandas, NumPy, Matplotlib, Jupyter Notebook, Machine Learning models | [Link to Published Article](https://mavenanalytics.io/project/7588) |

Project Description
Sales forecasting is a crucial aspect of retail business operations. By accurately predicting future sales, Corporation Favorita can optimize inventory management, streamline promotions, and make informed strategic decisions. In this project, we explore various time series forecasting models and machine learning algorithms to identify the most effective approach for predicting future sales at Favorita stores.

#### METHODOLOGY:

We'll use CRISP-DM, an industry-proven approach, for data mining:
![image](https://github.com/thibaut-tebi/Time-Series-Sales-Forecasting/assets/113062383/56b7d8bd-fb96-4934-9e58-19a9802a08cb)

#### Data
The project's data is stored in the data directory and consists of several CSV files, including train.csv, test.csv, transaction.csv, stores.csv, oil.csv, and holidays_events.csv. These files contain information on sales, store locations, oil prices, holidays, and more.

### Exporatory Data analysis
![image](https://github.com/thibaut-tebi/Time-Series-Sales-Forecasting/assets/113062383/87d95d91-3f59-4a5f-90f9-aa80f981d5f2)


#### Usage
To use the Sales Forecasting model, follow these steps:

Preprocess the data: Use the Jupyter notebooks in the notebooks directory to explore and preprocess the data. Run the data preprocessing script using python data_preprocessing.py.

Model Training: Run the model training script using python train_model.py. This will train the various models, including SARIMAX, ARIMA, Auto Regressive, Random Forest Regressor, Linear Regression, Decision Tree Regression, and XGBoost.

Evaluation: Evaluate the models using different metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Root Mean Squared Logarithmic Error (RMSLE)

### Modeling and Evaluation
The modeling phase involved training various models on the preprocessed data. We evaluated each model's performance using metrics like RMSLE to identify the most accurate model for sales forecasting. The Linear Regression model stood out with the lowest RMSLE value, demonstrating its robustness in predicting future sales trends.

### Results
The Sales Forecasting model based on Linear Regression offers accurate predictions, enabling Corporation Favorita to make data-driven decisions for inventory management, promotions, and overall business strategies.


