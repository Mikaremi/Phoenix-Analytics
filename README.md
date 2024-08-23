# Phoenix-Analytics

Company X is a tech-led company that connects informal retailers and other similar outlets directly to fast-moving consumer goods companies (FMCGs) by communicating demand from retail outlets directly to FMCGs and their distributors and managing the delivery of the goods to the retailers.

## Question 1
### Dynamic Routing
Dynamic routing is an order fulfilment strategy where orders are dynamically grouped to create an optimum delivery route. An optimum delivery route is one that will cost the least and ensures that the vehicle is optimally utilized.
Assuming delivery costs are broken down as below;

⎯ Fuel costs = Distance (Kms) covered * Fuel cost per KM

⎯ Vehicle costs = cost per trip * no of trips

To create optimum routes, it therefore requires one to ensure that the vehicle covers the shortest distance and carries the most weight per trip.
Remember, per trip, a vehicle will carry a maximum of its capacity (vehicles have a standard carrying capacity as per the manufacturing specifications).
To achieve a dynamic route;
Per territory, per delivery window, select a combination of orders that will cover the shortest distance but provides the highest utilization. (Utilization = Vehicle capacity (as per manufacturer)/total weight of scheduled orders. There is also a consideration of the capacity in terms of space occupied by a product.

In this case study;
You are only required to address one element of dynamic routing which is clustering shops (customer_id) around the fulfilment centers.

## Question 2
### Churn Prediction
1. Using the attached dataset (dataset.csv) analyse the data and visualize the most important aspects using your preferred method. Furthermore, share three ideas on how to decrease the churn rate. Document your steps where needed.
  
2. Split the data into train and test sets. Predict whether a shop will churn or not. Please document your steps and method used. The csv, “Q2_sample_submission_file_churn” will help with the format.
The objective of this case study is to create a machine learning model that will predict whether a customer will churn or not.
