# Working with Fintech Data Issue #1

### Problem Statement

- **Credit Marketing** -- Whom to target as new customer?
- **Credit Risk** -- How do we decide credit scoring and appraisal?

Following data from Shop.Happy is provided to us:
 
1. Credit data: Data about credit applications, approved/declined decisions, repayment details, and more at the customer level.

2. Marketing data: Transaction level data with details like merchant industry, price, chosen funding instrument, and more. 

3. AB Testing data: AB testing data for 3 months for transactions with random recommendation (nudge) of Funding Instrument as default (control group) and data-based recommendation (nudge) of Funding Instrument as default (test group). The test/control group tag for every transaction is provided.


![image](https://github.com/Vaibhav-sa30/Working-with-Fintech-Data-Issue-1/assets/86743451/c72bcc4d-6f11-47a8-b388-a78c38f48a82)

A/B testing to perform nudge in order to increase user engagement.

Consumer group is split into **TEST** and **CONTROL** group. 
Nudge is performed in test group

First we want to check the experiment is ran properly. Basically it shouldn't be a biased experiment.

To actually check that we want to know if the ratio of Average sum of transaction done on credit and debit card should be similar for **TEST** and **CONTROL** group.

