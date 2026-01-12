<p align= 'center'> <img width="240" height="220" alt="image" src="https://github.com/user-attachments/assets/f3c2dfa4-088b-4200-8f65-32e942cc9105" />

# <p align= 'center'> Store Performance Report


## <p align= 'center'> Client Background

<br>

**Citizen Savings Bank** is a major European global banking and financial services institution headquartered in Frankfurt, Germany. Serving millions of individual and corporate clients worldwide, the bank offers services ranging from retail banking to asset management and investment banking. 

In a highly competitive European financial market, customer acquisition and retention are essential for long-term profitability. However, rising churn rates have emerged as a significant operational and financial challenge for the bank. In response, Citizen Savings Bank is investing in advanced data analytics to better understand the drivers of customer attrition and develop targeted strategies to enhance client satisfaction and retention.

Citizen Savings Bank book of business has **5000** unique customers and includes many different variables such as, age, credit score, member activity and churn status.

Reporting to the Head of Operations, an in-depth analysis was conducted to evaluate Citizen Savings Bank performance. This project demonstrates how structured EDA and interaction analysis can uncover meaningful churn drivers and support strategic decision – making without relying solely on productive modeling.

<br>

### Churn Analysis Key Metrics:
- **Target Variable Analysis** – focusing on overall number of clients that have churned, percentage of customers churn and percentage of retained customers who remained with business.  
- **Univariate Analysis** – focusing on churn rate for single categorial variables such as education, location, members activity status and credit card possession as well as numerical variables including credit scores, months inactive and tenure groups. 
-	**Multivariate Analysis** – interaction analysis evaluating how two combined variables affect each other for potentially increased churn risk.

-	## <p align= 'center'> Executive Summary

**Churn is driven primarily by customer behavior rather than demographics.** 
  -	Customers with short tenure, extended periods of inactivity and single product engagement exhibit significantly higher churn rates while location, gender or age does not have a big impact on churn. 
  
 **Interaction analysis highlights that churn risk compounds when multiple risk factors occur together.**
  - Customers who become inactive within their first year have a substantially higher probability of churning compared to long – tenure or consistently active customers.

- **Business should focus on retention efforts:**
  1.  early customer engagement.
  2.	implementing triggers for inactive members.
  3.	promoting multi – product adoption to increase customer retention.   

## <p align= 'center'> Dataset Structure 

The database structure as seen below consists of one table with a total row count of **5000** records.

<img width="700" height="600" alt="image" src="https://github.com/user-attachments/assets/65971d9e-68a8-4d1d-86e6-8d6209f661b6" />

## <p align= 'center'> Target Variable Analysis (Churn)


## <p align= 'center'> % Churned vs Retained Customers

<img width="347" height="733" alt="image" src="https://github.com/user-attachments/assets/a995a919-bcdc-4e79-a5df-00019d800a89" />

-	Out of 5000 customers, 1610 customers closed their accounts and left Citizen Savings Bank. This number indicates a **churn rate of 32.2%.** 
-	Only **67.8%** of customers remained with business and continued to use Citizen Savings Bank services.  

## <p align= 'center'> Insights Deep-Dive

### <p align= 'center'> Churn by Category

<img width="720" height="659" alt="image" src="https://github.com/user-attachments/assets/e45c1dfd-c6c7-4618-937f-0e590d0177c5" />

	**Churn by Education and Geography** 
-	Churn rate by education indicates similar rate for customers with high school (31%), masters (32%) and bachelor’s diploma (33%). On the other hand, customers with PhD education are more likely to churn (40%).  
-	Location does not have a significant impact on churn. Customers from Germany, Spain and France have a very similar churn rate. 

<img width="872" height="385" alt="image" src="https://github.com/user-attachments/assets/d80e14bc-b866-467e-9f3d-1fcdb7b32471" />

**Churn by Member Activity and Possession of Credit Card** 
-	Churn rate varies whether customer is an active member or not. On Average, nonactive members are more likely to get churned by more than 20% compared to active members.  
-	Credit cards are not a significant factor for churn. Bank customers without a credit card are more likely to get churned only by 2.9% compared to a customer with a credit card.  

 
