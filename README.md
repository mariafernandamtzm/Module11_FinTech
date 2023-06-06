# Module11_FinTech
Forecasting online prophet 
 This repository contains the code and analysis to predict the online prophet in MercadoLibre, the most popular e-commerce site in Latin America. The goal is to analyze the company's financial and user data to make forecasts and support growth strategies. 
  Languages and software used 
 The following languages and software were used in this activity: 
 
 Python 3.10 
 Jupyter Notebook 
 Pandas 
 NumPy 
 hvPlot 
 The prophet 
 Procedures 
 The activity is divided into four stages and an optional fifth stage: 
 
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
