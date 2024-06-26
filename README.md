# Python-Bank-Marketing-Campaigns-Analysis

This project entails the comprehensive analysis of the outcomes of bank marketing campaigns. The principal objective of this analysis is to discern and forecast the subset of customers who exhibit a likelihood of subscribing to term deposits subsequent to the execution of the marketing campaigns.

**1. Context:**

You are a data analyst in the Data department at Bank X, which is headquartered in Spain.
During this time, there has been a decrease in revenue for the bank, and the director wants to know what measures need to be taken.

After investigating, the head of Data found out that the core reason is that their customers are not depositing money as often as before.
There is a fact that term deposits allow banks to keep customers' deposits for a specific period of time, so banks can use that money to invest in higher-yielding financial products to generate profits.

In addition, banks also often persuade customers that in addition to making term deposits, they can buy other products such as funds or insurance to increase revenue.
Therefore, Bank X wants to identify current customers who have the opportunity to sign up for higher term deposits and focus marketing efforts on those customers.

**2. Terminology explaination:**

- Term Deposit: A type of bank account where you deposit your money for a fixed period (the term) in exchange for a higher interest rate than a regular savings account. You cannot withdraw your money until the term ends, or you might face penalties.
- Maturity Date: The date when your term deposit reaches the end of its term. On this date, you will get your principal amount (the money you deposited) back along with the accumulated interest.
- Data Analyst: Someone who analyzes data to identify trends and patterns and communicate these findings to others.
- Revenue: The income generated by a business through the sale of its goods or services.
- Marketing Efforts: Activities undertaken by a company to promote its products or services to potential customers.

**3. Addtional information:**
Banks use the money deposited in term deposits to invest in various financial products like loans, bonds, and stocks. These investments typically offer a higher return on investment than the interest paid on term deposits. This allows banks to make a profit.
Persuading customers to open term deposits is a strategy that banks use to increase their revenue and profitability. They achieve this by offering attractive interest rates on term deposits compared to regular savings accounts.

**4. Data dictionary:** 
https://docs.google.com/spreadsheets/d/1emKaAfifvI30_Ef2oPLuc7rdoRz5AP2jXrsVLE8k6Cc/edit?usp=sharing

- age: Customer's age (Integer)
- job: Customer's occupation (Categorical)
- marital: Customer's marital status (Categorical)
- education: Customer's education level (Categorical)
- default: Indicates credit risk (Yes/No or Binary)
- balance: Balance in customer's account (Numeric)
- housing: Indicates housing loan (Yes/No or Binary)
- loan: Indicates personal loan (Yes/No or Binary)
- contact: Type of contact made (Categorical)
- day: Day of the contact (Integer)
- month: Month of the contact (Categorical)
- duration: Duration of the last contact (seconds) (Numeric)
- campaign: Number of contacts in this campaign for this customer (Integer)
- pdays: Days since last contact in previous campaign (Integer)
- previous: Number of contacts before this campaign (Integer)
- poutcome: Outcome of the previous marketing campaign (Categorical)
- deposit: Whether the customer agreed to a deposit (Yes/No or Binary)

**5. Analytics requests:**
- Visualize marketing effectiveness with charts like line graphs, bar charts, etc.
- Analyze marketing effectiveness from various perspectives, for example: age, marital status, job, etc.
- Advanced: Perform clustering using the Random Forest algorithm.

**6. Appendix:**
**Random Forest** is one of the most popular and well-known algorithms in Machine Learning. 
It is a Supervised Learning algorithm and is a method that can solve Regression and Classification problems. 
The goal of this algorithm is to build many decision trees using the Decision Tree algorithm, however each decision tree will be different (with a random factor). The predicted result is then synthesized from the decision trees.
