# Predict_Likelihood_Customer_Defaulting_On_Loan-Analytics_Olympiad_2023-MachineHack

**A) About Hackathon:-**

The Academy of Continuing Education at Shiv Nadar Institution of Eminence, in collaboration with MachineHack, is thrilled to announce the third edition of its hugely successful Analytics Olympiad. This annual event provides a much-desired platform for data scientists and machine learning professionals to showcase their predictive analytics prowess and win up to INR 1 lakh. 

Analytics Olympiad 3.0 is based on the theme — Predicting Customer Loan Default — and will provide valuable insights for the banking, finance, insurance (BFSI) and fintech industry.

**B) Problem Statement:-**

In today's financial landscape, an accurate prediction of customer loan default can reduce the risk and maintain a healthy lending portfolio. The challenge requires the participants to develop machine learning models to determine the likelihood of a customer defaulting on a loan. 

Contestants will be provided with credit history, payment behaviour, and account details to build the model. This challenge mirrors a huge real-world problem faced by financial institutions, thus making it extremely relevant.

**C) About the Dataset:-** Dataset contains following files,

**C1) Train:-** rows x  columns

**C2) Test:-**  rows x  columns

**C3) Submission:-**

**C4) Data description:-** The dataset provided to the participants will contain:

**1) Customer Information:-**

**1.1) customer_id:-** Unique identifier for each customer application.

**1.2) firstname:-**  First name of the customer.

**1.3) lastname:-** Last name of the customer.

**2) Credit Record Information:-**

**2.1) record_number:-** Sequence number of the credit product in the credit history.

**2.2) days_since_opened:-** Days from credit opening date to data collection date.

**2.3) days_since_confirmed:-** Days from credit information confirmation date till data collection date.

**2.4) primary_term:-** Planned number of days from credit opening date to closing date.

**2.5) final_term:-** Actual number of days from credit opening date to closing date.
days_till_primary_close: Planned number of days from data collection date until loan closing date.
days_till_final_close: Actual number of days from data collection date until loan closing date.
loans_credit_limit: Credit limit for the customer's loans.
loans_next_payment_summary: Amount of the next loan payment.
loans_outstanding_balance: Outstanding balance amount.
loans_max_overdue_amount: Maximum overdue amount.
loans_credit_cost_rate: Cost rate associated with loans.

3) Loan Overdue Information:

loans_within_5_days to loans_over_90_days: Number of loans overdue within different time frames.
is_zero_loans_within_5_days to is_zero_loans_over_90_days: Binary indicators for zero loans overdue within different time frames.

4) Credit Utilization and Limit Information:

utilization: Credit utilization rate.
over_limit_count: Count of instances where the customer went over the credit limit.
max_over_limit_count: Maximum count of instances where the customer exceeded the credit limit.
is_zero_utilization: Binary indicator if credit utilization rate is zero.
is_zero_over_limit_count: Binary indicator if the count of over limit instances is zero.
is_zero_max_over_limit_count: Binary indicator if the maximum over limit count is zero.

5) Encoded Features:

encoded_payment_X: Encoded information about payment X (categorical features converted to numerical values).
encoded_loans_account_holder_type: Encoded information about the type of account holder for loans.
encoded_loans_credit_status: Encoded information about the credit status of loans.
encoded_loans_credit_type: Encoded information about the type of credit for loans.
encoded_loans_account_currency: Encoded information about the currency used for loans.

6) Close Flags:

primary_close_flag: Binary indicator for primary term close.
final_close_flag: Binary indicator for final term close.

D) Evaluation metric:-  All submissions will be evaluated using the roc_auc_score.

E) Public and Private Split:-

This competition supports private and public leaderboards
The public leaderboard is evaluated on 30% of Test data
The private leaderboard will be made available at the end of the phase 1 of the competition, which will be evaluated on 100% of Test data
The Final Score represents the score achieved based on the Best Score on the public leaderboard

Finalists will be judged as per the following criteria, in the final jury round

30% Business Outcome/Impact,
20% Innovative + Creativity
20% Algorithm and ML approach
15% Statistically analysis
15% Presentation + Communication.

# Summary
