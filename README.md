# Telcom Customer Churn - EDA and Decision Trees
![](https://www.pwc.com/gx/en/tmt/5g/5G-hero-telco-page.gif)
## About the dataset

The _Telco customer churn_ data contains information about a fictional telco company that provided home phone and Internet services to 7043 customers in California in Q3. It indicates which customers have left, stayed, or signed up for their service. Multiple important demographics are included for each customer, as well as a Satisfaction Score, Churn Score, and Customer Lifetime Value (CLTV) index.

The data set includes information about:
- Customers who left within the last month – the column is called Churn
- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movie
- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents


## Exploratory Data Analysis

I have done Exploratory Data Analysis on this dataset which helped me gain the following insights:
- Most of the people are youngsters in Telco.
- There are equal number of male and female customers.
- The most preferred contract type offered by the people in Telco is Month-to-Month contract.
- The customer who has a partner has been with the company for longer tenure.
- The people who opted for 'Fiber optic' service have higher monthly charges than the people who opted for 'DSL' service.
- As the monthly charges are increasing, there is a higher possibility that the customers are inclined to leave the service.
- Most common tenure lies between 0-5 months, followed by 65-70 months.
- Device Protection plans have a very high cost as could be seen from the above. This means that people are paying a lot for device protection plans.
- Senior citizens pay less amount as compared to the non-senior citizens.
- There is a higher churn when the total charges are lower.

## Decision Tree Modelling

For the modelling part, the following steps were followed:

1. Looking at the statistics
2. Encoding categorical columns into numerical columns
3. Assigning a variable to the remaining columns that were already numerical
4. Creating a new dataframe df1 and storing all the variables in numeric form
5. Defining our 'x' and 'y'
6. Splitting the dataset into training and testing
7. Plotting the decison tree![enter image description here
8. Checking the training accuracy 
9. Checking the testing accuracy
  > **Training accuracy:  -0.396%**
  > **Testing Accuracy:  -10.00%**

## Creating a python function

At last, I created a python function where i can input my values and get a prediction of whatever I are trying to predict.


