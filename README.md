you can access the python notebook using this link
https://github.com/Chandanraxit07/Telecom_Churn_Analysis/blob/main/Notebook_of_Telecom_Churn_Analysis.ipynb


# Telecom Churn Analysis
Customer churn refers to when a customer (player, subscriber, user, etc.) ceases his or her relationship with a company. Businesses typically treat a customer as churned once a particular amount of time has elapsed since the customer’s last interaction with the site or service. The full cost of customer churn includes both lost revenue and the marketing costs involved with replacing those customers with new ones. Reduction customer churn is important because cost of acquiring a new customer is higher than retaining an existing one. Reducing customer churn is a key business goal of every business. This case is related to telecom industry where particular organizations want to know that for given certain parameters whether a person will churn or not.
# Exploratory Data Analysis
Our target variable has two categories which include True and False values. True = Customer will move or churn out. False = Customer won’t move We can clearly see that our data is highly imbalanced. The occurrence of false is higher than True. There are 2850 (85.51% ) customers who churn out and 483 (14.49%) customers retained. customer churn
# State Wise Churn Analysis
statewise
# Area Wise Churn Analysis
Most of the churned customers are from 415 area. area_wise

# Churn according to International Plan
Churn rate is more with customer using international plan. As only 323 customer using International plan and 137 churning out of them. planvise

#Churn according to Voicemail Plan
922 customer using voice mail plan and 80 out of them are churning voice mail plan vise

# Churn according to Customer Care Calls
Churn rate for Customer neither having voicemail plan nor international plan is 9.06%. Churning rate for customer having International plan but don’t have voicemail plan is 3.03% out of 6.93% customers. Churning of customer having both voicemail plan & international plan is 1.08% out of 2.76% customer care calls vise

#Collinear Plot
‘Total day minutes’ and ‘total day charges’ are highly correlated ‘Total eve minutes’ and ‘total eve charges’ are highly correlated ‘Total night minutes’ and ‘total night charges’ are highly correlated ‘Total intl minutes’ and ‘total intl charges’ are highly correlated correlation plot_py

# Distribution of variables
Most of thevariables are normally distributed. nr1

# Solution to Reduce Customer Churn
Modify International Plan as the charge is same as normal one. Be proactive with communication. Ask for feedback often. Periodically throw Offers to retain customers. Look at the customers facing problem in the most churning states. Lean into best customers. Regular Server Maintenance. Solving Poor Network Connectivity Issue. Define a roadmap for new customers. Analyze churn when it happens. Stay competitive.

# Conclusion

The four charge fields are linear functions of the minute fields.

The area code field and/or the state field are anomalous, and can be omitted.

Customers with the International Plan tend to churn more frequently.

Customers with four or more customer service calls churn more than four times as often as do the other customers.

Customers with high day minutes and evening minutes tend to churn at a higher rate than do the other customers.

There is no obvious association of churn with the variables evening calls, night calls, international calls, night minutes, international minutes, account length.

# RECCOMENDATIONS
Improve network coverage churned state

In international plan provid some discount plan to the customer

Improve the voice mail quality or take feedback from the customer

Improve the service of call center and take frequently feedback the customer regarding their issue and try to solve it as soon as possible
