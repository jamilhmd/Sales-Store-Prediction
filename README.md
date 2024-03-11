#Project Overview

This project analyzes historical sales data from 45 Walmart stores across the US, with the aim of predicting sales and accurately meeting demand. 
We examined various factors such as economic conditions, holiday markdown events, 
and seasonal variations to understand their impact on sales and to address stock shortages through better demand forecasting.

Key Insights

Temperature and Sales: Our analysis found no significant relationship between temperature and sales, 
suggesting that weather conditions might not be a primary driver of purchase decisions at Walmart.
Consumer Price Index (CPI): CPI appears not to directly affect sales. However, it enables us to categorize customers into two distinct segments:
Middle-class customers, who typically spend between $120 and $150.
High-class customers, who spend between $180 and $230.
Holiday Sales: Sales figures show a significant increase during special holiday weeks, highlighting the importance of adequate stock preparation in anticipation of increased demand.
Annual Sales Trend: The year 2011 marked a peak in sales performance, surpassing both 2010 and 2012.
Seasonality: Summer emerged as the most frequent season in our dataset, correlating with the highest number of weekly sales recorded.

Modeling and Results

In our pursuit to predict weekly sales, we explored three machine learning algorithms: Linear Regression, Decision Tree, and Random Forest. 
Through rigorous evaluation, we discovered that the Random Forest model was the most effective, boasting an accuracy of approximately 93.2%. 
This outcome illustrates the potential of ensemble models in handling the complexity and patterns of large datasets like Walmart's sales data, making it the best model for our analysis.

Business Problem

Walmart encounters challenges in predicting demand, especially during holidays, leading to potential stock shortages. 
This project seeks to leverage machine learning to consider factors like economic conditions, including CPI and Unemployment Index, to enhance demand forecasting.

About the Dataset

The Walmart_Store_sales dataset spans sales from 2010-02-05 to 2012-11-01, comprising fields such as Store number, Date, Weekly_Sales, Holiday_Flag, Temperature, Fuel_Price, and CPI.

Challenge

The task of modeling the effects of markdowns on holiday weeks is complicated by the lack of complete/ideal historical data. 
We aimed to overcome this by analyzing sales data and identifying trends that can facilitate accurate sales predictions.

Conclusion

This analysis has shed light on the various factors that influence sales at Walmart. 
By understanding these factors and utilizing advanced machine learning techniques like the Random Forest model, 
we can make well-informed decisions about stock management, particularly during holiday seasons and promotional markdown events. 
Our success with the Random Forest model in predicting weekly sales underscores the efficacy of analytical approaches in improving demand forecasting accuracy and optimizing business operations.
