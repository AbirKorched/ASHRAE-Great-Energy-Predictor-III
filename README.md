# ASHRAE-Great-Energy-Predictor-III
We are using a dataset related to ASHRAE – Great Energy Predictor III (How much energy will a building consume?). The goal is to develop models from ASHRAE’s 2016 data in order to better understand metered building energy usage in the following areas: chilled water, electric, hot water, and steam meters. The data comes from over 1,000 buildings over a one-year timeframe. The method chosen to solve the problem is Linear Regression.     
### Objective

The objective of this notebook is to provide a prdictive models using LSTM to predict
How much energy will a building consume? 

The train dataset has our target variable called “meter reading” with datatype float, hence the task could be solved by RNN. The following methodology is used: 



### Outline

1.Data Understanding

2.Data Preparation

2.1 Merge tables

2.2 Droping columns and filling null value for column: 'air_temperature', 'wind_speed', 'precip_depth_1_hr', 'cloud_coverage'
2.3 Prepare train & test data for LSTM

3.Modeling    
