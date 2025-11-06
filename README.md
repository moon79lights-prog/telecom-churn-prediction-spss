1. Objective of the Project

To predict customer churn in a telecom company using IBM SPSS Modeler, and to identify the key factors that influence customer attrition.

To analyze customer demographic and service usage data.

To build a CHAID decision tree model for churn prediction.

To classify customers into “Churn” and “Not Churn” categories.

To generate churn probabilities for each customer.

To help the telecom company identify high-risk customers for targeted retention campaigns.

2. Key Insights from the Project 

 . Dropped Calls influence churn the most.	Customers with a higher number of dropped calls are more likely to leave the service.
 
 . Tariff Plan plays a major role.	Customers on lower or basic tariff plans showed higher churn rates than those on premium plans.
 
 . Handset Type affects customer loyalty.	Certain handset models (possibly older or incompatible ones) were linked to more churn.
 
 . Age impacts churn behavior.	Younger customers (below 30) tend to churn more frequently compared to older ones.
 
 . Predictive model is effective.	The CHAID model successfully predicts churn with reasonable accuracy and gives probabilities for each customer.

6. Business Use:

Helps the telecom company retain customers, reduce revenue loss, and improve satisfaction by targeting at-risk customers with special offers or better service plans.

3. Tools and Techniques Used
   
Data Format	Excel Files (.xlsx) — telco_x_customer_data, telco_x_customer_info

Modeling Technique	CHAID (Chi-squared Automatic Interaction Detection) Decision Tree

Data Preparation	Select / Filter Node, Type Node, Derive Node, Reclassify Node

Model Evaluation	Model Viewer, Table Nodes

Final Output	Scored dataset with $C-Churn and $RC-Churn=Yes values

Export Format	Excel / CSV (for final churn prediction results)
