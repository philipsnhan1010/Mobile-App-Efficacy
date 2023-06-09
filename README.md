# Mobile-App-Efficacy
A hotel chain “Smith Hotels” with properties including full-service hotels and resorts is considering whether to push a newly built app to its customers.  In this project, we will analyze data from a live test to determine the effectiveness of a new mobile app that has been built.

# Experiment Design
Here’s an overview of the experiment that was conducted. In this scenario, a before-after design of experiment was followed. To determine the app’s efficacy, the organization ran a live test with a beta version of the app.
A subset of customers who had been enrolled in the loyalty program run by the hotel chain for at least one year was selected at random and assigned to one of two groups - Control and Treatment, and the experiment was conducted as follows:

Control Group
- Number of customers: 2000 
- Before: At the beginning of the experiment, the spending behavior of all the customers in the control group was recorded for one-year
- Treatment: No changes were introduced to the control group
- After: The control group was tracked for another year, and their spending behaviors were recorded.

Treatment Group
- Number of customers: 2000 
- Before: At the beginning of the experiment, the spending behavior of all the customers in the treatment group was recorded for one-year
- Treatment: A mail was sent to all the customers in the treatment group with a link to download the beta version app. 
- After: All the customers in the treatment group started using the app, and their spending behavior was recorded for another year.

![image](https://user-images.githubusercontent.com/43742200/225185286-c4a819bc-8029-4fc9-b2ad-9b0a67f94c44.png)

# Overall Problem Statement
To make an appropriate decision about launching the app, the hotel chain’s management needs to find the answers to these questions:
- Will the app lead to increased spending on the part of customers?
- How much of an increase in spending do you expect? 
- Do you expect the app’s effect on spending to vary by customers’ characteristics?

# Understand Data set

![image](https://user-images.githubusercontent.com/43742200/225185465-a694211f-5e2b-4bdf-8943-50a3e30bc108.png)

# Project Tasks
## Part I - Data Preparation and Wrangling: Data Loading and Preparation

![image](https://user-images.githubusercontent.com/43742200/225488526-c8193a67-243f-4dba-84f7-bbcf2c0b94a2.png)

![image](https://user-images.githubusercontent.com/43742200/225488668-1c2dac14-1675-4e7d-b1cb-7229edcdb7a1.png)

## Part II: Exploratory Data Analysis
### Univariate Analysis I: Data summary of customers’ characteristics: Use appropriate tables for the summary statistics and bar charts and describe the customers’ characteristics.
-	Demographics: Gender, age, nationality
-	Loyalty membership and tenure with the hotel chain (in months)

![image](https://user-images.githubusercontent.com/43742200/225489340-e303db39-cb56-4fcf-84dc-886d0856e8a8.png)

![image](https://user-images.githubusercontent.com/43742200/225489414-0574d518-a40a-4098-9b2a-28f695ac77a0.png)

![image](https://user-images.githubusercontent.com/43742200/225489463-ddef86c7-0528-43b1-8b12-070c64f29d28.png)

### Univariate Analysis II: Data summary of customers’ purchase behavior: Use appropriate tables for the summary statistics and graphs and describe customers’ purchase behavior.
- Amount spent [Spending]
- Number of bookings [NumBookings] 

![image](https://user-images.githubusercontent.com/43742200/225489548-01693fe7-370d-48df-ae7b-18a92eaa5349.png)

![image](https://user-images.githubusercontent.com/43742200/225489614-cf57a5fa-cf34-439c-87d1-9dbf6c2c0436.png)

### Multivariate Analysis: 
- Construct relevant pivot tables, bar charts, and scatterplots to get a preliminary understanding of the relationship between customers’ characteristics and their purchase behavior.

![image](https://user-images.githubusercontent.com/43742200/225489656-35fb1d04-abf0-4e5c-aff7-e1ee632d4908.png)

![image](https://user-images.githubusercontent.com/43742200/225489689-a5308221-22ba-45a4-bfcd-4ef6c0f48915.png)

- Generate a table of the correlations of all numerical variables of the data set.

![image](https://user-images.githubusercontent.com/43742200/225489905-2d2e7051-0f7a-4cc4-be0c-78c7e5e85c99.png)

- Determine whether there is a statistically significant difference between the average spending of men and women (at a 5% significance level)? Conduct an appropriate hypothesis test to determine whether there is a difference in means. Construct a 95% confidence interval for the difference in means.

![image](https://user-images.githubusercontent.com/43742200/225490096-b2afd16f-c1ad-453e-a39e-9d0308e5fae8.png)

