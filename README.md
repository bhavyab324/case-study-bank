# **Data Case Study - Direct Marketing Optimization**

## Project Description : 
To identify and match the right product offer (e.g., credit card, consumer loan, mutual fund) to the right customer in order to maximize revenue from a direct marketing campaign, while adhering to the contact constraints.
## Dataset :
* Social-Demographic Information: Age, gender, and bank tenure.
* Product Holdings and Volumes: Details on current accounts, savings accounts, mutual
funds, overdrafts, credit cards, and consumer loans.
* Financial Transactions: Aggregated inflow/outflow on current accounts and average
monthly card turnover over the past three months.
* Sales and Revenue Data: Available for 60% of clients, serving as a training set.
## Project Repository :
* **InputDataset**
    * casestudy_accountbal.csv
    * casestudy_demog.csv
    * casestudy_inflow_outflow.csv
    * casestudy_target_rev.csv
    * DataScientist_CaseStudy_Dataset.xlsx (for ref only)
* **Code**
    * 01_DataPrep.ipynb - It includes script used for Feature Engineering and Data Transformation
    * 02_Model_ConsumerLoan.ipynb - It includes script used for Top Feature Selection and ModelSelection for Consumer Loan Predictive Model
    * 03_Model_CreditCard.ipynb - It includes script used for Top Feature Selection and Model Selection for Credit Card Predictive Model
    * 04_Model_MutualFund.ipynb - It includes script used for Top Feature Selection and Model Selection for Mutual Funds Predictive Model
    * 05_Optimal_RevenueStrategy.ipynb - It includes script used for Combining all product-wise predicted probabilities and class and then calculating an effective revenue for each product for each customer/client.The final score is Maximum value of Effective Revenue per customer and the Recommended Offer is the Product corresponding to the maximum Effective Revenue.
      All customers are sorted by Score and saved to the **_sorted_combined_model_output.csv_** file.
* **TransformedData**
* **ModelOutput**
