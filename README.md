# Walmart Sales Analysis

The analysis provides a comprehensive overview of Walmart's weekly sales data, examining various factors influencing sales, such as holidays, temperature, CPI, and unemployment. The visualizations and statistical analysis offer insights into trends, distributions, and relationships, aiding in better understanding and decision-making for sales strategies

<hr>

### Dataset Overview 
The dataset contains Walmart sales data with the following columns:

```Store:``` Store number <br>
```Date:``` Date of the sales data <br>
```Weekly_Sales:``` Weekly sales amount <br>
```Holiday_Flag:``` Indicates whether the week includes a holiday (1) or not (0) <br>
```Temperature:``` Temperature recorded during the week <br>
```Fuel_Price:``` Price of fuel during the week <br>
```CPI:``` Consumer Price Index <br>
```Unemployment:``` Unemployment rate <br>

### Data Transformation
- Converted `Date` column to datetime format for better handling of date-related operations.
- Filtered the data for specific date ranges to observe trends and perform analysis.

<hr>

### Visualizations and Insights

##### Weekly Sales Over Time

- A plot showing the trend of weekly sales over a specific date range indicates any seasonality or trends. There are fluctuations in sales, possibly due to promotional activities or seasonal effects. 
<br>

<img width="500" alt="image" src="https://github.com/p-diya/Walmart-Sales-Analysis/assets/61963099/82057e63-c7c6-47a9-b3d9-1ab2d68982ff">

##### Distribution of Weekly Sales

- The histogram of weekly sales shows the distribution and central tendency of the sales data. This helps identify the range and frequency of sales values.
<br>

<img width="500" alt="image" src="https://github.com/p-diya/Walmart-Sales-Analysis/assets/61963099/f379933c-4555-4bbd-9647-df059933e006">

##### Weekly Sales vs Temperature

- Scatter plots display the relationship between temperature and weekly sales, indicating whether sales are affected by weather conditions. Each point is uniquely colored to differentiate individual data points.
- A scatter plot with a regression line helps visualize the trend and correlation between temperature and weekly sales over a broader date range.
<br>

<img width="500" alt="image" src="https://github.com/p-diya/Walmart-Sales-Analysis/assets/61963099/2e379420-4aba-445d-b60e-17f32f9f9048">

##### Weekly Sales by Holiday Flag

- Box plots comparing sales on holidays versus non-holidays show that sales tend to be higher during holiday weeks, as expected.
<br>

<img width="500" alt="image" src="https://github.com/p-diya/Walmart-Sales-Analysis/assets/61963099/165270cf-552f-4fb3-b88c-7ec06d982a7e">


##### Correlation Matrix

- A heatmap of the correlation matrix visualizes the relationships between numerical variables. For example, the correlation between CPI and Weekly Sales, Temperature and Weekly Sales, etc.
<br>
<img width="500" alt="image" src="https://github.com/p-diya/Walmart-Sales-Analysis/assets/61963099/e2657ac1-fa5f-4584-b01d-cee43bc8357f">


##### CPI Over Time

- A plot of CPI over time helps understand the trend and how it fluctuates over the given period.
<br>
<img width="500" alt="image" src="https://github.com/p-diya/Walmart-Sales-Analysis/assets/61963099/dab55c23-b9cb-407c-8e2c-589d3e376185">


##### Weekly Sales vs CPI

- A scatter plot with a regression line displays the relationship between CPI and weekly sales, indicating how changes in CPI affect sales.
<br>
<img width="500" alt="image" src="https://github.com/p-diya/Walmart-Sales-Analysis/assets/61963099/1c5b836c-7a7f-4ee4-bd7d-631fc5bc3a74">


##### Seasonal Decomposition of Weekly Sales

- Seasonal decomposition of the weekly sales data shows the observed, trend, seasonal, and residual components, providing a clearer picture of underlying patterns.
<br>
<img width="500" alt="image" src="https://github.com/p-diya/Walmart-Sales-Analysis/assets/61963099/7b233b38-6783-4660-9457-5300c819614d)">


##### Regression Analysis

- The regression model includes variables like Holiday_Flag, Temperature, Fuel_Price, CPI, and Unemployment to predict Weekly Sales.
- The summary provides coefficients, R-squared value, and p-values, giving insights into the significance and impact of each variable.
<br>
<img width="500" alt="image" src="https://github.com/p-diya/Walmart-Sales-Analysis/assets/61963099/014d7bab-e843-459f-b01f-cb088810d0c5">


##### Store-Level Statistics

- Aggregated statistics for each store (mean, total, and standard deviation of weekly sales) provide insights into store performance.
- A bar plot of average weekly sales by store visualizes the comparative performance across different stores.
<br>
<img width="500" alt="image" src="https://github.com/p-diya/Walmart-Sales-Analysis/assets/61963099/584dad05-e7db-462c-828c-155ce042e744)">


##### Unemployment Analysis

- Distribution of unemployment rates and their trend over time is plotted to understand its fluctuation.
- The correlation between unemployment and weekly sales is calculated, and a scatter plot visualizes this relationship. The correlation coefficient helps quantify the strength and direction of the relationship.
<br>
<img width="500" alt="image" src="https://github.com/p-diya/Walmart-Sales-Analysis/assets/61963099/30318b7b-9809-49f4-b611-bb7b5b0de2db">
<img width="500" alt="image" src="https://github.com/p-diya/Walmart-Sales-Analysis/assets/61963099/199f43eb-ce45-4b58-bf90-2ca36afa3e2e">
<img width="500" alt="image" src="https://github.com/p-diya/Walmart-Sales-Analysis/assets/61963099/22b57dbc-bca2-45fc-b845-86d8139cdd48">

