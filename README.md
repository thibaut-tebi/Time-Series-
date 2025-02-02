#### Name: Thibaut Kwadzo Tebi
#### Email : thibaut.tebi@azubiafrica.org

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

We'll use CRISP-DM, an industry-proven approach, for this project:
![image](https://github.com/thibaut-tebi/Time-Series-Sales-Forecasting/assets/113062383/d2c5d482-a522-4105-b1fb-489ad20d1207)


#### Data
The project's data is stored in the data directory and consists of several CSV files, including train.csv, test.csv, transaction.csv, stores.csv, oil.csv, and holidays_events.csv. These files contain information on sales, store locations, oil prices, holidays, and more.

#### QUESTIONS
1. How are the clusters performing against each other?
2. What family brings in the most money across all stores?
3. Which locales are the busiest in terms of transactions?
4. In which year did most of the transactions happen?
5. How have sales been over the years?
6. What are the dates of the top 10 sales?
7. What were the dates of the highest sales for each year?

### ANSWER TO QUESTIONS USING DASHBOARD
To provide comprehensive insights and address critical business questions, we have crafted a powerful dashboard which answered all the questions above. This  dashboard serves as the focal point of our project, consolidating data from various sources and offering an intuitive interface to explore the results of our business understanding phase. You can get access to the interactive Dashboard via https://app.powerbi.com/groups/me/reports/6fd097ad-85c3-4c34-9c22-09761491d6a7?ctid=4487b52f-f118-4830-b49d-3c298cb71075&pbi_source=linkShare
![image](https://github.com/thibaut-tebi/Time-Series-Sales-Forecasting/assets/113062383/87d95d91-3f59-4a5f-90f9-aa80f981d5f2)


#### Usage
To use the Sales Forecasting model, follow these steps:

Preprocess the data: Use the Jupyter notebooks in the notebooks directory to explore and preprocess the data. Run the data preprocessing script using python data_preprocessing.py.

Model Training: Run the model training script using python train_model.py. This will train the various models, including SARIMAX, ARIMA, Auto Regressive, Random Forest Regressor, Linear Regression, Decision Tree Regression, and XGBoost.

Evaluation: Evaluate the models using different metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Root Mean Squared Logarithmic Error (RMSLE)


https://github.com/user-attachments/assets/d646b1e5-7ddc-460b-9fc1-ebe65ec81dc2




### Modeling and Evaluation

![image](https://github.com/thibaut-tebi/Time-Series-Sales-Forecasting/assets/113062383/f92bad45-98c3-4ca4-bd0f-c22b56abfcc3)

The modeling phase involved training various models on the preprocessed data. We evaluated each model's performance using metrics like RMSLE to identify the most accurate model for sales forecasting. The Linear Regression model stood out with the lowest RMSLE value, demonstrating its robustness in predicting future sales trends.

### Results 
The Sales Forecasting model based on Linear Regression offers accurate predictions, enabling Corporation Favorita to make data-driven decisions for inventory management, promotions, and overall business strategies.

### Recommendation
As we move forward, we highly recommend the implementation of the Linear Regression model for sales forecasting at Corporation Favorita. The model's consistent and accurate predictions will serve as a powerful tool to optimize inventory planning, strategize promotions, and make informed business decisions. Leveraging the data-driven approach offered by the Linear Regression model, Corporation Favorita can confidently navigate the ever-evolving retail landscape and embark on a path to sustainable growth and success

#### RESOURCES
1. https://towardsdatascience.com/exploratory-data-analysis-in-python-a-step-by-step-process-d0dfa6bf94ee
2. https://heartbeat.comet.ml/a-practical-guide-to-feature-engineering-in-python-8326e40747c8
3. https://www.influxdata.com/time-series-forecasting-methods/
4. https://neptune.ai/blog/select-model-for-time-series-prediction-task
5. https://vitalflux.com/steps-for-evaluating-validating-time-series-models/
6. https://scikit-learn.org/stable/modules/model_evaluation.html#regression-metrics
7. https://towardsdatascience.com/improve-linear-regression-for-time-series-forecasting-e36f3c3e3534
8. https://learn.microsoft.com/en-us/azure/machine-learning/how-to-tune-hyperparameters?view=azureml-api-2
   


