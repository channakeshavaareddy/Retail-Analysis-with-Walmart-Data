# Retail-Analysis-with-Walmart-Data
Retail sales analysis and demand forecasting using Walmart sales data. Performed EDA, holiday impact analysis, sales trend visualization, outlier detection, feature engineering, and predictive modeling using Linear Regression with Python, Pandas, NumPy, Seaborn, Matplotlib, and Scikit-learn.

##  Project Aim:
The aim of this project is to analyze Walmart’s historical sales data to understand key business patterns and factors affecting demand. It focuses on performing exploratory data analysis to identify sales trends, holiday impacts, and store-wise performance variations. The project also includes studying the influence of economic indicators like CPI, fuel price, and unemployment on sales. Finally, the goal is to build a machine learning model using Linear Regression to forecast weekly sales accurately and support better business decision-making for inventory and demand planning.

## Steps Involved in the Project:
### Data Collection
- Loaded the Walmart historical sales dataset containing store-wise weekly sales and economic indicators such as CPI, fuel price, temperature, and unemployment rate.
  
### Data Cleaning & Preprocessing
- Converted the Date column into datetime format, checked for missing values, and ensured data consistency across all records.

### Feature Engineering
- Extracted new features such as Day, Month, and Year from the Date column to support time-based analysis.
  
### Exploratory Data Analysis (EDA)
- Analyzed sales distribution, store-wise performance, and overall sales trends using statistical summaries and visualizations.
  
### Store-wise Sales Analysis
- Identified stores with maximum and minimum total sales and measured sales variability using standard deviation and coefficient of variation.
  
### Holiday Impact Analysis
- Studied the effect of major holidays (Super Bowl, Labour Day, Thanksgiving, and Christmas) on weekly sales patterns.

### Sales Trend Analysis
- Visualized monthly and yearly sales trends to understand seasonality and demand fluctuations over time.

### Outlier Detection & Handling
- Used boxplots to detect outliers in economic variables and filtered abnormal values for improved model performance.

### Model Building
- Built a Linear Regression model using store, economic indicators, and time-based features to forecast weekly sales.
  
### Model Evaluation
- Evaluated model performance using MAE, MSE, and RMSE to measure prediction accuracy.
  
### Business Insights
- Derived key insights on sales behavior, holiday impact, and economic influence to support demand forecasting and inventory planning.

## Tools, Software, and Libraries Used:

**Programming Language**
- Python
  
**Development Environment**
- Jupyter Notebook

**Libraries Used**
- Pandas – for data manipulation and analysis
- NumPy – for numerical computations
- Matplotlib – for data visualization
- Seaborn – for advanced statistical visualizations
- Scikit-learn – for machine learning model building and evaluation.

**Version Control**
- Git & GitHub – for project tracking and repository management

**Operating System**
- Windows

##  Key Visualizations:
### Store-wise Sales Analysis
![image alt](https://github.com/channakeshavaareddy/Retail-Analysis-with-Walmart-Data/blob/main/Screenshots/Screenshot%202026-05-12%20124814.png)

### Sales Distribution Analysis
![image alt](https://github.com/channakeshavaareddy/Retail-Analysis-with-Walmart-Data/blob/main/Screenshots/Screenshot%202026-05-12%20124850.png)

### Holiday Sales Impact
![image alt](https://github.com/channakeshavaareddy/Retail-Analysis-with-Walmart-Data/blob/main/Screenshots/Screenshot%202026-05-12%20125030.png)
![image alt](https://github.com/channakeshavaareddy/Retail-Analysis-with-Walmart-Data/blob/main/Screenshots/Screenshot%202026-05-12%20125150.png)

### Monthly Sales Trend
![image alt](https://github.com/channakeshavaareddy/Retail-Analysis-with-Walmart-Data/blob/main/Screenshots/Screenshot%202026-05-12%20125240.png)

### Outlier Detection
![image alt](https://github.com/channakeshavaareddy/Retail-Analysis-with-Walmart-Data/blob/main/Screenshots/Screenshot%202026-05-12%20125314.png)

### Model Prediction Results
![image alt](https://github.com/channakeshavaareddy/Retail-Analysis-with-Walmart-Data/blob/main/Screenshots/Screenshot%202026-05-12%20125429.png)

### Model Evaluation Metrics
![image alt](https://github.com/channakeshavaareddy/Retail-Analysis-with-Walmart-Data/blob/main/Screenshots/Screenshot%202026-05-12%20125442.png)

##  Conclusion

This project successfully analyzed Walmart’s historical sales data to understand key business patterns and factors affecting weekly sales. Through exploratory data analysis, important insights were identified related to store-wise performance, seasonal trends, and the impact of major holidays on sales.

Economic factors such as CPI, fuel price, and unemployment were also analyzed to understand their relationship with sales behavior. Additionally, feature engineering helped improve data usability for modeling.

A Linear Regression model was built to forecast weekly sales, and its performance was evaluated using standard metrics like MAE, MSE, and RMSE. Although the model showed limited accuracy, it provided a baseline understanding of demand prediction and highlighted the need for more advanced time-series or ensemble models for better accuracy.

Overall, the project demonstrates how data analysis and machine learning can be applied in retail to support better inventory planning, demand forecasting, and business decision-making.

