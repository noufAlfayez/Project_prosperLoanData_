## Loan Data Exploration

### Dataset:
The dataset contains 113,937 loans with 81 features including (EmploymentStatus, LoanStatus, BorrowerAPR, IncomeRange, CreditGrade, Investors and many others features)
URL of Dataset:<a> https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv </a>


### Summary of Findings
In the exploration,The distribution of Investors looks a right-skewed : A large peak centered at 0 - 200.  Only very few loans have Investors greater than 600.
at different investor sizes, the APR has a large range, but the APR range decreases as investors increase. In general, the borrower's APR is negatively correlated with the investors, that is the more the Investors, the lower the APR.

Interestingly, the relationship between a borrower's APR, CreditGrade and employee status increases if the employee is retired and is HR or E, and if the employee is AA or A, the borrower's APR decreases for all employee status categories.

I also noticed that people with high average incomes who are full-time employees represent the vast majority of investors as opposed to employed or part-time employees.

### Key Insights for Presentation
For the presentation, I  focused on features that could affect the Investors, I started by showing the distribution of Investors and BorrowerAPR. Then, I showed the relationship between APR vs. Investors. 
I also investigated the effect of CreditGrade on ralationship between APR and EmploymentStatus as well as the effect of EmploymentStatus on relation ship between IncomeRange and Investors.

#### Prepare By: Nouf AL-Fayez


```python

```
