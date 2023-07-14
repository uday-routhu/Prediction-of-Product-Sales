<p align = "center"> 
  <img src = "https://raw.githubusercontent.com/coding-dojo-data-science/CodingDojo_Images/main/data-science.jpg">
</p>

## Analyzing or prediction of product sales

Udaykumar Routhu

### Often times when choosing a career path, career seekers that have a love for data science want to work from home and earn the highest salary possible while doing so. There are so many options to choose from and knowing which path will be the best path to choose can be challenging.

## Data Source:
# Prediction-of-Product-Sales
/content/data/MyDrive/CodingDojo/01-Fundamentals/Week02/Data/sales_predictions_2023.csv
for this dataset, there were 8523 rows and 12 columns.

Data Dictionary

![image](https://github.com/uday-routhu/Prediction-of-Product-Sales/assets/24350354/a5666e5a-f7d7-4cf2-95a7-e4685fd88553)

To prepare this data, the data was cleaned, and the following processes were performed:
### Expanatory Data Analysis
- Here on the boxplot, you can clearly see that there are several outliers in the Item_MRP column column. These could be valid data points, or they could be an error.
- Since there are Item_Weight included in this dataset, and they most likely cause increase of Item_MRP rate, I will leave these datapoints in place.
![image](https://github.com/uday-routhu/Prediction-of-Product-Sales/assets/24350354/706fc0ae-3f59-4cfa-a8c3-c722518a98bc)

### Expanatory Data Analysis
- Outlevel level size is higher for medium 
- Low level size for the High
![image](https://github.com/uday-routhu/Prediction-of-Product-Sales/assets/24350354/75a4b1e5-37ce-4d8a-b6de-a2c62f02660f)


## Recommendations

Data Science Insights

- For those who have an interest in Data Science:
  - Data Analytics Leads & Principal Data Engineers earn the most amount of money. However, this are usually not entry level careers and I would recommend going through a program, like Coding Dojo, where you can earn your data science certificate and then map out your career to these positions.

  - Data Engineers & Data Scientists have the most 100% remote positions. So, if you are wanting to work from home, or work from anywhere in the world, choosing one of the top five remote positions would be a good choice to build your career upon.
  
  - Lastly, the trend for the last three years show that data science and related fields are increasingly earning more money each year. So, choosing a career in one of these fields can be very lucrative.

Model Performance
- Overall, the best model is definitely the tuned Random Forest Regressor Model. There was still some bias in the model, but by far it outperformed the linear regression model. 
