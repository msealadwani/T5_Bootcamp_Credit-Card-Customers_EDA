
# Credit Card Customers
A business manager of a consumer credit card portfolio is facing the problem of customer attrition. They want to analyze the data to find out the reason behind this and leverage the same to predict customers who are likely to drop off.
This study aims to predict of which customer is going to get churned so they can proactively go to the customer to provide them better services, by analyzing the data.

# Dataset
To achieve the goal of this study the dataset Credit Card Customers will be used. This dataset can be found at [Kaggle](https://www.kaggle.com/sakshigoyal7/credit-card-customers). **There is 10128 rows and 23 columns.**

This dataset contains **15 features**:

- **CLIENTNUM** which is a client number. Unique identifier for the customer holding the account
- **Attrition_Flag** which is an internal event (customer activity) variable - if the account is closed then 1 else 0
- **Customer_Age** which is a demographic variable - Customer's Age in Years
- **Gender** which is a demographic variable - M=Male, F=Female
- **Dependent_count** which is a demographic variable - Number of dependents
- **Education_Level** which is a demographic variable - Educational Qualification of the account holder (example: high school, college graduate, etc.)
- **Marital_Status** which is a demographic variable - Married, Single, Divorced, Unknown
- **Income_Category** which is a demographic variable - Annual Income Category of the account holder (< $40K, $40K - 60K, $60K - $80K, $80K-$120K, >
- **Card_Category** which is a product Variable - Type of Card (Blue, Silver, Gold, Platinum)


The sample of data is shown in the following table:

<table width="100%">
 <tr>
  <th>CLIENTNUM</th><th>Attrition_Flag</th><th>Customer_Age</th><th>Gender</th><th>Dependent_count</th><th>Education_Level</th><th>Marital_Status</th><th>Income_Category</th><th>Card_Category</th>
 </tr>
 <tr>
  <th>768805383</th><th>Existing Customer</th><th>45</th><th>M</th><th>3</th><th>High School</th><th>Married</th><th>60K-80K</th><th>blue</th>
 </tr>
</table>


## Tools
There are tools that will be used to achieve the goal of this study, such as: pandas, numpy, matplotlib for discovering the data, The work will be done through Jupyter notebook.


## Questions that needs to be answered:
- Why do customers attrite?
- What is the relationship between the customer age and attrition flag?
- What happens if customers don't use their credit card for a year?
- Does credit card limit	affiect on the customer choice to leave?
