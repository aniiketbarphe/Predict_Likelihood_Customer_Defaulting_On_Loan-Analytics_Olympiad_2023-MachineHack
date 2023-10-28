![IMG1](https://github.com/aniiketbarphe/Predict_Likelihood_Customer_Defaulting_On_Loan-Analytics_Olympiad_2023-MachineHack/assets/84449238/88cd5095-8462-4c00-8899-082cd55a5d68)

# Predict_Likelihood_Customer_Defaulting_On_Loan-Analytics_Olympiad_2023-MachineHack

![Congrats-Image-V2](https://github.com/aniiketbarphe/Predict_Likelihood_Customer_Defaulting_On_Loan-Analytics_Olympiad_2023-MachineHack/assets/84449238/76790b2a-3f90-4fbc-b8f5-e9616782fec8)

**A) About Hackathon:-**

The Academy of Continuing Education at Shiv Nadar Institution of Eminence, in collaboration with MachineHack, is thrilled to announce the third edition of its hugely successful Analytics Olympiad. This annual event provides a much-desired platform for data scientists and machine learning professionals to showcase their predictive analytics prowess and win up to INR 1 lakh. 

Analytics Olympiad 3.0 is based on the theme — Predicting Customer Loan Default — and will provide valuable insights for the banking, finance, insurance (BFSI) and fintech industry.
#
**B) Problem Statement:-**

In today's financial landscape, an accurate prediction of customer loan default can reduce the risk and maintain a healthy lending portfolio. The challenge requires the participants to develop machine learning models to determine the likelihood of a customer defaulting on a loan. 

Contestants will be provided with credit history, payment behaviour, and account details to build the model. This challenge mirrors a huge real-world problem faced by financial institutions, thus making it extremely relevant.
#
**C) About the Dataset:-** Dataset contains following files,

**C1) Train:-** **11,06,674** rows x  **62** columns

**C2) Test:-**  **4,74,289** rows x  **60** columns

**C3) Submission:-** **4,74,289** rows x  **2** columns
#####
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

**2.6) days_till_primary_close:-** Planned number of days from data collection date until loan closing date.

**2.7) days_till_final_close:-** Actual number of days from data collection date until loan closing date.

**2.8) loans_credit_limit:-** Credit limit for the customer's loans.

**2.9) loans_next_payment_summary:-** Amount of the next loan payment.

**2.10) loans_outstanding_balance:-** Outstanding balance amount.

**2.11) loans_max_overdue_amount:-** Maximum overdue amount.

**2.12) loans_credit_cost_rate:-** Cost rate associated with loans.

**3) Loan Overdue Information:-**

**3.1) loans_within_5_days to loans_over_90_days:-** Number of loans overdue within different time frames.

**3.2) is_zero_loans_within_5_days to is_zero_loans_over_90_days:-** Binary indicators for zero loans overdue within different time frames.

**4) Credit Utilization and Limit Information:-**

**4.1) utilization:-** Credit utilization rate.

**4.2) over_limit_count:-** Count of instances where the customer went over the credit limit.

**4.3) max_over_limit_count:-** Maximum count of instances where the customer exceeded the credit limit.

**4.4) is_zero_utilization:-** Binary indicator if credit utilization rate is zero.

**4.5) is_zero_over_limit_count:-** Binary indicator if the count of over limit instances is zero.

**4.6) is_zero_max_over_limit_count:-** Binary indicator if the maximum over limit count is zero.

**5) Encoded Features:-**

**5.1) encoded_payment_X:-** Encoded information about payment X (categorical features converted to numerical values).

**5.2) encoded_loans_account_holder_type:-** Encoded information about the type of account holder for loans.

**5.3) encoded_loans_credit_status:-** Encoded information about the credit status of loans.

**5.4) encoded_loans_credit_type:-** Encoded information about the type of credit for loans.

**5.5) encoded_loans_account_currency:-** Encoded information about the currency used for loans.

**6) Close Flags:**

**6.1) primary_close_flag:-** Binary indicator for primary term close.

**6.2) final_close_flag:-** Binary indicator for final term close.
#
**D) Evaluation metric:-**  All submissions will be evaluated using the roc_auc_score.
#
**E) Public and Private Split:-**

**E1)** This competition supports private and public leaderboards

**E2)** The public leaderboard is evaluated on 30% of Test data

**E3)** The private leaderboard will be made available at the end of the phase 1 of the competition, which will be evaluated on 100% of Test data

**E4)** The Final Score represents the score achieved based on the Best Score on the public leaderboard

**E5)** Finalists will be judged as per the following criteria in the final jury round:-

**E5.1)** 30% Business Outcome/Impact,

**E5.2)** 20% Innovative + Creativity

**E5.3)** 20% Algorithm and ML approach

**E5.4)** 15% Statistically analysis

**E5.5)** 15% Presentation + Communication

# Summary

**a) Best Submission Score:-**

**1) Public Leaderboard :-** 0.99992

**2) Private Leaderboard :-** 0.99986
#
**b) Best Model:-** 

**b1) Target Variable :-** 'Primary_Close_Flag' [ Ensemble Technique (XGB Classifier + Gradient Boosting Classifier with best Hyperparameters)]

**b2) Target Variable :-** 'Final_Close_Flag' [ Ensemble Technique (XGB Classifier + Gradient Boosting Classifier with best Hyperparameters)]

#
**c) Competition Link:-**  https://machinehack.com/hackathons/analytics_olympiad_2023/leaderboard
#
**d) Rank Scored:-**

**After 2nd Round**

**Top 50** out of **1016** registered participants

**After 1st Round**

a) **81** out of **1016** registered participants (Public Leaderboard)

b) **103** out of **1016** registered participants (Private Leaderboard)


