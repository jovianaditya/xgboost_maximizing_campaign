# Maximizing Term Deposit Campaign With XGBoost Modelling

A term deposit is an investment product issued by a bank. Where the scenario is that the customer will give a certain amount of money to the bank and the money cannot be withdrawn within a certain time. However, in return, the bank will provide interest to the customer in accordance with the initial agreement. Money given by customers to the bank will be used by the bank to provide business capital to customers. So this can also be said to be a circulation cycle of money from customers and back to the customers..

Goals : Increase CVR minimal 5%.

Information about the Dataset & Machine Learning Model:
- Dataset contains 45211 customers. Only around 11% of customers interested in opening term deposit (imbalanced data). <br>
- The final model that was used to classify the customers is XGBoost.
- The metrics that used to evaluate the model is AUC-ROC and Recall. The reason why using AUC-ROC and not using accuracy metrics is because the dataset is imbalanced. If still insist on using accuracy the result will be biased. In this project i will prioritized to maximize recall more than precision, because the goal is to increase conversion rate but **the cost aspect will also be considered (precision will not very low)** and it will be proved through simulation.


Result : The simulation results show the model increase the conversion rate by up to 6% and can also reduce phone costs by up to 68%.
