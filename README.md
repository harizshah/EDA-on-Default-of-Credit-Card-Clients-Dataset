# EDA-on-Default-of-Credit-Card-Clients-Dataset

This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

## Content
Total 25 columns, with 1 target variable default.payment.next.month, and 23 explanatory variables (ID excluded).

(1) ID: ID of each client
(2) LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit)
(3) SEX: Gender (1 = male, 2 = female)
(4) EDUCATION: (1 = graduate school, 2 = university, 3 = high school, 0,4,5,6 = others)
(5) MARRIAGE: Marital status (0 = others, 1 = married, 2 = single, 3 = divorce)
(6) AGE: Age in years
(7) PAY_0: Repayment status in September, 2005
(-2 = No consumption, -1 = paid in full, 0 = use of revolving credit (paid minimum only), 1 = payment delay for one month, 2 = payment delay for two months, ... 8 = payment delay for eight months, 9 = payment delay for nine months and above)

(8) PAY_2: Repayment status in August, 2005 (scale same as above)
(9) PAY_3: Repayment status in July, 2005 (scale same as above)
(10) PAY_4: Repayment status in June, 2005 (scale same as above)
(11) PAY_5: Repayment status in May, 2005 (scale same as above)
(12) PAY_6: Repayment status in April, 2005 (scale same as above)
(13) BILL_AMT1: Amount of bill statement in September, 2005 (NT dollar)
(14) BILL_AMT2: Amount of bill statement in August, 2005 (NT dollar)
(15) BILL_AMT3: Amount of bill statement in July, 2005 (NT dollar)
(16) BILL_AMT4: Amount of bill statement in June, 2005 (NT dollar)
(17) BILL_AMT5: Amount of bill statement in May, 2005 (NT dollar)
(18) BILL_AMT6: Amount of bill statement in April, 2005 (NT dollar)
(19) PAY_AMT1: Amount of previous payment in September, 2005 (NT dollar)
(20) PAY_AMT2: Amount of previous payment in August, 2005 (NT dollar)
(21) PAY_AMT3: Amount of previous payment in July, 2005 (NT dollar)
(22) PAY_AMT4: Amount of previous payment in June, 2005 (NT dollar)
(23) PAY_AMT5: Amount of previous payment in May, 2005 (NT dollar)
(24) PAY_AMT6: Amount of previous payment in April, 2005 (NT dollar)
(25) default.payment.next.month: Default payment (1=yes, 0=no)

Description gather from Kaggle Dataset > Overview & Discussion. But some column need to be rename and value need to be edit later.

