<p align= 'center'> <img width="300" height="260" alt="image" src="https://github.com/user-attachments/assets/de297744-d9ad-48ab-bb8d-3e87d123083b" />

# <p align= 'center'> Bank Churn Analysis Report


## <p align= 'center'> Client Background

<br>

**Citizen Savings Bank** is a major European global banking and financial services institution headquartered in Frankfurt, Germany. Serving millions of individual and corporate clients worldwide, the bank offers services ranging from retail banking to asset management and investment banking. 

In a highly competitive European financial market, customer acquisition and retention is essential for long-term profitability. However, rising churn rates have emerged as a significant operational and financial challenge for the bank. In response, Citizen Savings Bank is investing in advanced data analytics to better understand the drivers of customer attrition and develop targeted strategies to enhance client satisfaction and retention.

Citizen Savings Bank book of business has **5000** unique customers and includes many different variables such as, age, credit score, member activity and churn status.

Reporting to the Head of Operations, an in-depth analysis was conducted to evaluate Citizen Savings Bank performance. This project demonstrates how structured EDA and interaction analysis can uncover meaningful churn drivers and support strategic decision – making.

<br>

### Churn Analysis Key Metrics:
- **Target Variable Analysis** – focusing on overall number of clients that have churned, percentage of customers churn and percentage of retained customers.  
- **Univariate Analysis** – focusing on churn rate for single categorial variables such as education, location, members activity status and credit card possession as well as numerical variables including credit scores, months inactive and tenure lenght. 
-	**Multivariate Analysis** – interaction analysis evaluating how two combined variables affect each other for potentially increased churn risk.

<br>

## <p align= 'center'> Executive Summary

**Churn is driven primarily by customer behavior rather than demographics.** 
  -	Customers with short tenure, extended periods of inactivity and single product engagement exhibit significantly higher churn rates while location, gender or age does not have a big impact on churn. 
  
**Interaction analysis highlights that churn risk compounds when multiple risk factors occur together.**
  - Customers who become inactive within their first year have a substantially higher probability of churning compared to long – tenure or consistently active customers.

**Business should focus on retention efforts:**
  1.  early customer engagement.
  2.	implementing triggers for inactive members.
  3.	promoting multi – product adoption to increase customer retention.   

<br>

## <p align= 'center'> Dataset Structure 

The database structure as seen below consists of one table with a total row count of **5000** records.

<br>

<img width="480" height="550" alt="image" src="https://github.com/user-attachments/assets/65971d9e-68a8-4d1d-86e6-8d6209f661b6" />

<br>

<br>

## <p align= 'center'> Target Variable Analysis (Churn)

## <p align= 'center'> % Churned vs Retained Customers

<br>

<img width="347" height="620" alt="image" src="https://github.com/user-attachments/assets/a995a919-bcdc-4e79-a5df-00019d800a89" />

-	Out of 5000 customers, 1610 customers closed their accounts and left Citizen Savings Bank. This number indicates a **churn rate of 32.2%.** 
-	Only **67.8%** of customers remained with business and continued to use Citizen Savings Bank services.  

<br>

# <p align= 'center'> Insights Deep-Dive

## <p align= 'center'> Churn by Category

<br>

<br>

<img width="600" height="700" alt="image" src="https://github.com/user-attachments/assets/e45c1dfd-c6c7-4618-937f-0e590d0177c5" />

<br>

<br>

**Churn by Education and Geography** 
-	Churn rate by education indicates similar rate for customers with high school (31%), masters (32%) and bachelor’s diploma (33%). On the other hand, customers with PhD education are more likely to churn (40%).  
-	Location does not have a significant impact on churn. Customers from Germany, Spain and France have a very similar churn rate. 

<br>

<img width="650" height="350" alt="image" src="https://github.com/user-attachments/assets/d80e14bc-b866-467e-9f3d-1fcdb7b32471" />

<br>

**Churn by Member Activity and Possession of Credit Card** 
-	Churn rate varies whether customer is an active member or not. On Average, nonactive members are more likely to get churned by more than 20% compared to active members.  
-	Credit cards are not a significant factor for churn. Bank customers without a credit card are more likely to get churned only by 2.9% compared to a customer with a credit card.  

<br>

 ## <p align= 'center'> Churn by Numerical Values

<br>

 <img width="400" height="500" alt="image" src="https://github.com/user-attachments/assets/7c122210-cce5-4588-a9f0-0cee16be054f" />

<br>

<br>

 **Churn rate by Credit score** 
-	Credit scores can be a big indicator for potential churned customers. We divided customers to four different credit bands: bands with poor credit (lower than 500 points), fair credit (500- 650 points), good credit (650-750 points), and excellent credit (750+).   
-	Customers with poor credit scores are more likely to churn by 10.1% when compared to customers with excellent credit scores. 
-	Customers with fair, good and excellent credit scores have similar churn rates and there is no significant difference between them.

<br>

  <img width="400" height="500" alt="image" src="https://github.com/user-attachments/assets/7b6f9ab6-cacd-45b3-acbf-9a4d5c2dd7e6" />

<br>

<br>

**Churn rate by Inactive Months**
-	This graph indicates churn rate by inactive months by members ranging from 0 months to 11 months   
-	There is a huge shift in churn rate when customers reach 5 inactive months. Customers with 5 or more inactive months are more likely to get churned by 14-18% depending on number of inactive months.

<br>

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/a75a5306-acbe-4250-8f29-e06b74151d4a" />

<br>

**Churn rate by Tenure Group**
-   Customers with lower tenure tend to churn faster. New clients who use bank services for a year or less are 9% more likely to get churned compared to customers with higher tenure rates.

  ### <p align= 'center'> Multivariate Analysis

<br>

<img width="400" height="150" alt="image" src="https://github.com/user-attachments/assets/d18b867d-3afa-406e-b0d2-6736fc0b1d75" />

<br>

 **Tenure X inactivity level**
-	Inactive and low tenure customers are more likely to get churned compared to active members with higher tenure. 
-	Customers who have used bank services for more than 3 years and are active members possess a churn rate of 22% which is 10% less than the average churn rate.
-	New inactive customers (with 12 or less months tenure) are very likely to leave business with 47% chance of churn.

<img width="450" height="250" alt="image" src="https://github.com/user-attachments/assets/56bc9809-bdb3-4e79-834b-847493b960c1" />

<br>

**Credit Score X Number Of Products**
- 	Bank customers with excellent credit score and 4 products in use are less likely to get churned (9% less compared to average rate). 
-	Number of products in use is not a significant factor for Bank customers with poor, fair or good credit. Number of products affects only 1-4% churn rate for this customer segment.

  <img width="400" height="100" alt="image" src="https://github.com/user-attachments/assets/20b82c44-da33-4287-8193-422725a31055" />

<br>

<br>

<br>

**Credit Score X Number Of Products**
-	Inactive members of Citizen Savings Bank are more likely to get churned compared to active members in all three locations. 
-	In Spain, inactive members are more likely to get churned and leave business by 22%, France by 21% and Germany by 18% compared to active members.
  
## <p align= 'center'> Recommendations

### Based on the uncovered insights, here are actionable items that OfficeSupplies can take away from our analysis:
  
**Customers with short tenure (0-12months) show significantly higher churn – especially when combined with inactivity (47% churn rate).** 
	-	Business should launch a 90 – day onboarding & engagement program to reduce early-stage churn and increase long – term customer lifetime value. 

**Customers inactive for 5+ months are more likely to get churned by 15-18%.**
	-	Establish inactivity trigger (for example, 3 months no activity) helping to re-engage distracted visitors with offers, support, or reminders before they leave.

**Customers with excellent credit score and 4 products churn at a much lower rate (23%) compared to average number (32%)** 
	-	Target customer segment with excellent credit score and offer business products such as savings account, credit card and low- risk financial tools because they are less likely to leave business. 

**Customers with poor credit scores (39% churn rate) and low engagement (44% churn rate) represent the highest churn risk.** 
	-	Provide free credit score monitoring and improvement tips within the bank’s app.
	-	Offer credit-building loan products and financial literacy resources to support customers with lower credit scores and low engagement. 


