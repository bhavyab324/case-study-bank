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
   * processed_data_salesCC.csv
   * processed_data_salesCL.csv
   * processed_data_salesMF.csv
* **ModelOutput**
  * CC_predictions.csv
  * CL_predictions.csv
  * MF_predictions.csv
  * sorted_combined_model_output.csv
  * Top_100_Customers.csv
 
## Results and Evaluation

<img width="837" alt="image" src="https://github.com/user-attachments/assets/a9ec8eff-03ed-4972-a642-d7e61e61c81d" />

## Solution 
### 1. High-Propensity Client Lists and Targeting Strategy: Submissions must directly answer the following questions with justifications:
* Which clients have a higher propensity to buy a consumer loan? Refer CL_predictions.csv
* Which clients have a higher propensity to buy a credit card? Refer CC_predictions.csv
* Which clients have a higher propensity to buy a mutual fund? Refer MF_predictions.csv
 Confidential
* Which clients are to be targeted with which offer? Refer Top_100_Customers.csv
* What would be the expected revenue based on your strategy?
The expected Revenue = 1337 EUR
3. Deliverables
a. A concise executive summary (up to 2 pages) OR a slide deck (5–8 slides) for a technical audience.
b. A Targeted Client List specifying selected clients for each offer.
c. A Codebase with all necessary files
4. Instructions on How to Submit
• Commit all deliverables to a public GitHub repository in your personal account. (We do not accept zipped submissions attached in emails.)
• DO NOT include this document or sensitive terms like "Singlife" in the repository.
• Email the GitHub repository link to the sender of this test. Submission deadline is communicated by the sender of the test, please check your email.

