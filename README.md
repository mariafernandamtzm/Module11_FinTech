# Module11_FinTech


## Introduction

This project focuses on analyzing financial and user data of MercadoLibre, the most popular e-commerce site in Latin America, in order to identify patterns and make accurate forecasts. The goal is to explore the relationship between Google search traffic, stock price patterns, and revenue. The project involves several steps, including finding unusual patterns in search traffic, identifying seasonality in search data, relating search traffic to stock price patterns, creating a time series model using Prophet, and optionally forecasting revenue using time series models.

Languages and Software Used
Python - Programming language used for data analysis, modeling, and visualization.
Jupyter Notebook - Interactive coding environment used for running Python code and documenting the project.
Pandas - Library used for data manipulation and analysis.
NumPy - Library used for numerical computing.
hvPlot - Interactive plotting library used for data visualization.
Prophet - Time series forecasting library developed by Facebook.
 
 ## Step 1: Look for unusual patterns in hourly Google search traffic 
 Read  search data into a DataFrame and analyze data patterns. Cut the data to  May 2020 and plot the results with hvPlot.  Calculate the total search traffic for the month and compare it to the monthly median.  
 
 ## Step 2: Mine seasonal search traffic data 
 Group  search data by hour and plot  average traffic by  day of the week.  Visualize  traffic as a heatmap with hvPlot.  Group  search data by  week of the year and analyze  traffic during the winter holiday season.


## Step 3: Combine search traffic with price sharing 
 Read and graph stock prices. Combine stock prices with  search data. Cut through the data for the first half of 2020 and analyze the overall trends.  Create lagged columns and calculate the relationship between search traffic and stock volatility/returns.  
 

##  Step 4: Create a time series model using Prophet 
 Configure Google search data for Prophet's prediction template. Evaluate the model and make a prediction. Analyze temporal components to identify popular  day, day of the week and low point in search traffic.  

## Step 5 (optional): Revenue forecasting using time series models 
 Read  daily historical sales data and use the Prophet model.  Identify seasonal patterns in company revenue. Prepare a sales forecast for the next quarter, including best and worst case scenarios.  The Jupyter Notebook in this repository provides  code and detailed analysis for each step. It includes explanations, visualizations and interpretation of  results. Note. The data used in this activity is not included in the archive. You can use your own dataset or get the required data from the respective sources mentioned in the Jupyter notebook. 
