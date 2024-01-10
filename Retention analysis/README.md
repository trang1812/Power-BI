# CUSTOMER RETENTION

## Problem
The Telecom Retention Manager has arranged a meeting with the partner at PwC to address critical points related to customer retention. Currently, churning customers were contacted after they terminated the contract. The manager seeks a proactive strategy, wanting to identify customers at risk beforehand. Additionally, comprehensive insights into customers are requested to be presented visually for easy comprehension by management.

## Objectives
The purpose of this analysis is to create a Dashboard in Power BI for the Customer Retention Manager that reflects relevant Key Performance Indicators (KPIs) to:
* Self-exploratory the customer demographics and insights.
* Actively approach who is at risk with the risk level of specific customer.
* Contain metrics and plots related to a single area of business for discussing with higher managers and generating further analysis.
* Based on finding recommend improving customer retention.

## Dataset:
Metadata
| | |
| --- | --- |
| File | 02 Churn-Dataset |
| Size	| 772KB |
| Fields |	23 |
| Rows |	7043 |

Description of Churn data
| Field Name |	Description |
| --- | --- |
| customerID |	Unique number of the customer |
| gender |	Gender of the customer |
| SeniorCitizen |	Whether the customer is a senior citizen or not |
| Partner |	Whether the customer has a partner or not	|
| Dependents |	Whether the customer has dependents or not |
| tenure |	Number of months the customer has stayed with the company |
| PhoneService | Whether the customer has a phone service or not |
| MultipleLines	| Whether the customer has multiple lines or not |
| InternetService |	Customer’s internet service provider (DSL, Fiber optic, No) |
| OnlineSecurity |	Whether the customer has online security or not |
| OnlineBackup |	Whether the customer has online backup or not |
| DeviceProtection | Whether the customer has device protection	or not |
| TechSupport	| Whether the customer has tech support or not |
| StreamingTV | Whether the customer has streaming TV or not |
| StreamingMovies | Whether the customer has streaming movies or not |
| Contract | The contract term of the customer |
| PaperlessBilling |	Whether the customer has paperless billing or not |
| PaymentMethod |	The customer’s payment method |
| MonthlyCharges |	The amount charged to the customer monthly |
| TotalCharges |	The total amount charged to the customer |
| numAdminTickets |	Number of admin tickets opened by the customer |
| numTechTickets |	Number of tech tickets opened by the customer	|
| Churn |	Whether the customer churned or not (Yes or No) |

* Relevant information about the Churn dataset:
  * Customers who left within the last month.
  * Services each customer has signed up for phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies.
  * Customer account information: how long as a customer, contract, payment method, paperless billing, monthly charges, total charges and number of tickets opened in the categories administrative and technical.
  * Demographic info about customers – gender, age range, and if they have partners and dependents.

## Analysis
![Dashboard](https://github.com/trang1812/Power-BI/assets/126154468/99b4b0ae-bc60-4716-aeb6-a88b7057298b)

### Customer Churn Overview
* The total number of customers is 7043, 1869 of which churned (26,5%). Revenue lost due to churn is $2.86M. The churn rate highlights the need for proactive measures to address customer concerns and improve retention strategies to mitigate further churn in the future.
* The average tenure for existing customers is around 38 months, but for those who have churned, the average period is only 18 months. This difference underscores the importance of prioritizing strategies aimed at retaining customers to extend their tenure.
* The average monthly charges for customers who have churned were significantly higher, amounting to approximately $74.44, in contrast to the average monthly charges of $61.31 for customers who have not churned. This suggests that pricing and value perception play crucial roles in customer retention efforts.
  
### Customer Demographic Information 
* Gender is not the major factor of churning as churn rate of male and female is almost same.
* Among those who terminated the company services, 74.53% belonged to the younger age group, while 25.47% were classified as senior citizens. The majority of customers who discontinued services did not have dependents. This indicates a higher rate of churn among younger customers without dependents and the need to address their unique needs and preferences for enhancing customer retention.
![Senior customers?](https://github.com/trang1812/Power-BI/assets/126154468/f00141cc-3cfa-4fad-b0d8-0b74e23fc615)
![Customer has dependents?](https://github.com/trang1812/Power-BI/assets/126154468/c637861c-6675-4a6f-a917-ed91349cbaa1)


### Service Subscriptions
* Among Internet services, there might be some issues with Fiber Optic (41.9% churn rate). Thus, the company should inspect the system, build strong technology & infrastructure to offer fast, quality, reliable digital experience. Another possible reason for high churn rate in Fiber Optic service could be high monthly charge ($91.5 on average).
* Customers that do not subscript to Online Security and Premium Tech Support are more likely to churn. I suggest company could provide 1-month free trial for Security and Tech Support subscription to existing customer to improve customer experience and increase retention rate.

### Customer Account Information
* Customers taking longer contracts tend to be more loyal and stay with the company. A significant number of customers with Month-to-Month contracts terminated the services (54,6%). In contrast, customers with Two Years contracts exhibited the lowest churn rate (7,2%). This indicates the potential benefits of longer contract terms in reducing customer churn. Company should come with more attractive long-term subscription plans rather than focusing on monthly plans.
* There is high percentage of customers pay with Electronic check, but 45,3% of them churned. This means the company need to address any issues related to the Electronic check mode of payment. Other modes of payment seem to be working fine but the technical team still needs to look into them. 

