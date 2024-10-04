*PROJECT BACKGROUND*

TelecomX is a telecommunication company that is aiming to increase its market share in the telecommunication industry, and with the mobile market saturated and dominated by a few players 
there is intense competition among service providers.
The company wants to understand the customer behavior and churn situation so they can offer competitive services to new customer and also retain existing customers. 
Since it costs up to 5 times as much for a service provider to acquire a new subscriber as to retain an existing one, it wants to build a system that identifies the ideal churner and provide better services to potential churners. This project analyses and identify factors contributing to customer churn and also a machine learning model that predicts customer churn.


*EXECUTIVE SUMMARY*

With a churn rate of 26.5% over six years, and highest at 61% in the first month of subsciption, churn rate gradually reduces with increasing monthly charges, longer tenure and contracts, getting to 47% for customers subscribed in their fisrt year. The Company generated $16.1 million in revenue from 7043 subscribers and lost $500K from churned customers in their first year.

![Alt text](https://github.com/EmmaDokyi/images/blob/main/Customer%20Churn%20Summary.png?raw=true)


*KEY INSIGHTS*
1. Churn rate is highest in the first year of subscription at 47% with reducing churn rate in longer-tenured customers, getting as low as 6.6% amongst customers in their 6th year of subscription.

2. Customers with higher monthly charges tend to churn more often. This suggests that pricing or perceived value might be a challenge for high-paying customers, possibly due to service dissatisfaction or competition.

3. Customers with month-to-month contracts have significantly higher churn rate(43%) compared to longer-term contracts (one-year, two year). This suggest offering more incentives for longer-term contracts could help reduce churn.

4. Customers who use fiber optics as their internet service, have no online security, no online backup, no device protection or no technical support have at least 41% churn rates. Offering bundled services at discounted rates may reduce churn by increasing the perceived value of the services.

5. While gender did not significantly affect churn, customers with no partners, senior citizens or no dependents were more likely to churn possibly due to different consumption pattern and financial constraints.

6. Customers who use electronic check payment method have the highest churn rate at 45% compared to those whose use mailed checks, automatic bank transfers and credit cards.

*MODEL BUILDING*

Built two machine learning models from scikit-learn using Decision Tree and Random Forest Classifiers. The Decision Tree Classifier model had a score of 92% with 94% and 92% precision in predicting non-churners and churners respectively. The Random Forest Classifier had a score of 93% with 96% and 92% precision in predicting non-churners and churners respetively. The model built with the Random Forest Classifier was selected for its higher accuracy and precision in predicting non-churners.
