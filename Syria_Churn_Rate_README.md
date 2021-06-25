# SyriaTel Churn Rate Machine Learning Project

**Authors**: Brian Matsiko, George Ferre

## Overview

This project creates a machine learning model that is able to predict the SyriaTel customers that are most likely to churn. Data for this project was sourced from the Kaggle website.The dataset includes 33 features and over 3,000 data points.
![logo](images/logo.jpeg)

## Business Problem

Microsoft is looking to develop an internal film department and needs clarity on how to be the most successful in the movie industry. Microsoft has never created a movie before. Choosing the first movie to make in this department is critical to their success in the movie industry. Through our analysis of various sources, we took a look at movies that were released in the last 10 years to get an idea of how recent movies have performed. Given that, we are going to provide recommendations to Microsoft based on the following:
***
* Syria Tel is a telecom company that provides service in United States
* Churn rate of ~15%
* Need to identify customer likely to leave
* Opportunity for proactive engagement and business retention
***

### Exploratory Data Analysis
The dataset churn has two categories:
* True = Customer churn.
* False = Customer won’t churn.

There are 2850 customers who churn and 483 (14.49%) who did not churn.
![customer churn](https://user-images.githubusercontent.com/20225277/46948212-de6c9880-d09a-11e8-8c32-3cb7587ba9fd.png)

###### State Wise Churn Analysis
![statewise](https://user-images.githubusercontent.com/20225277/46948261-065bfc00-d09b-11e8-9837-3f5fdfb42d2d.png)

###### Churn according to International Plan
Churn rate is more with customer using international plan. As only 323 customer
using International plan and 137 churning out of them.
![planvise](https://user-images.githubusercontent.com/20225277/46948340-5fc42b00-d09b-11e8-9be0-20c26b06ed21.png)

###### Churn according to Voicemail Plan
922 customer using voice mail plan and 80 out of them are churning
![voice mail plan vise](https://user-images.githubusercontent.com/20225277/46948361-74082800-d09b-11e8-9c83-f9a047633dfa.png)

###### Churn according to Customer Care Calls
Churn rate for Customer neither having voicemail plan nor international plan is
9.06%. Churning rate for customer having International plan but don’t have voicemail plan is
3.03% out of 6.93% customers. Churning of customer having both voicemail plan & international plan is 1.08% out of
2.76% 
![customer care calls vise](https://user-images.githubusercontent.com/20225277/46948289-2b506f00-d09b-11e8-8e39-1826c2a5eff8.png)

###### Collinear Plot
‘Total day minutes’ and ‘total day charges’ are highly correlated
‘Total eve minutes’ and ‘total eve charges’ are highly correlated
‘Total night minutes’ and ‘total night charges’ are highly correlated
‘Total intl minutes’ and ‘total intl charges’ are highly correlated
![correlation plot_py](https://user-images.githubusercontent.com/20225277/46948308-3dcaa880-d09b-11e8-8504-c9240fb55b92.png)

##### Distribution of variables
Most of thevariables are normally distributed.
![nr1](https://user-images.githubusercontent.com/20225277/46948317-49b66a80-d09b-11e8-8430-92757348c078.png)



## Methodology

This project utilizes descriptive analysis, including examination of correlation and relationship among the different variables. This provides insight for Microsoft into what characteristics of a movie can lead to higher box office earnings.

***

## Results


***


## Conclusions

This analysis leads to the following recommendations for creating a movie.
1. **Customer Service Calls.**
Establish Customer Service Calls audit program for continuous improvement
2. **Market Performance.**
Perform a market study to help understand how we can more competitive.
3. **Data plans.**
 Evaluate effectiveness of data plans  specifically for our international customers

## Project Limitations

Further analyses could provide even more insight into how you will create and distribute Microsoft's first movie:

**Customer churn rate coverage.**
Factors responsible for the different state churn rates not covered

**Area Codes.**
Dataset had only three unique area codes

**Call Rates.**
Assumed that rates were charged per time period 

**Customer Service Calls.**
Not able to perform in-depth analysis on the details here

## For More Information

Please review our full analysis in [our Jupyter Notebook](./Churn_final_notebook.ipynb) or our [presentation](./SyriaTel_Churn_presentation.pdf).

For any additional questions, please contact **Brian Matsiko matsikobrian@yahoo.com, George Ferre georgeaferre@gmail.com**.

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── Syria_Churn_Rate_README.md                         
├── Churn_final_notebook.ipynb  
├── SyriaTel_Churn_presentation.pdf         
├── data                            
└── images
```

