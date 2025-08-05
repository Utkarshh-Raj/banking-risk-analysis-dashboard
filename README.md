# Banking Risk Analysis & Customer Insights Dashboard

## Project Overview
This end-to-end data analytics project was designed to uncover customer behavior patterns and perform risk analysis in a banking context. Using Python, MySQL, and Power BI, the project delivers key insights that help minimize loan default risk and optimize product targeting.

---

## Tools & Technologies
- **Python**: Pandas, Seaborn, Matplotlib
- **MySQL**: Database for customer and account data
- **Power BI**: Dashboarding and stakeholder visualization
- **MySQL Connector**: Used to connect Python and MySQL

---

## Project Workflow

1. **Data Collection & Storage**
   - Loaded structured customer data (~3,000 records, 25 features) into MySQL.
   
2. **Exploratory Data Analysis (EDA)**
   - Analyzed distributions, detected skewness in income and balances.
   - Created new features (e.g., `income_band`) using `pd.cut`.
   - Performed correlation and bivariate analysis.

3. **Business Insights**
   - Strong positive correlation between deposit-related accounts.
   - Males are more likely to hold multiple credit cards than females.
   - Credit card usage has low correlation with income or loans.

4. **Power BI Dashboard**
   - Created KPIs:  
     - `Total Loan = Bank Loan + Business Lending + Credit Card Balance`  
     - `Total Deposit = Bank Deposit + Savings + Checking + Forex Account`
   - Included dynamic filters: Gender, Banking Relationship, Joining Year.
   - Built interactive visualizations and summary views.

---

## Key Insights
- Over 66% of customers own only one credit card.
- Private banks are the most common banking relationship.
- Europeans dominate the customer base, followed by Asians and Americans.
- Credit card balance is not strongly influenced by income or loans.

---

## 📊 Dashboard Preview

### Home Page
![Home Dashboard](https://github.com/Utkarshh-Raj/banking-risk-analysis-dashboard/blob/main/Banking%20Analysis/Banking/DashBoard/HOME.png)

---

### Loan Analysis Page
![Summary Dashboard]([assets/summary_dashboard.png](https://github.com/Utkarshh-Raj/banking-risk-analysis-dashboard/blob/main/Banking%20Analysis/Banking/DashBoard/LOAN_ANALYSIS.png))

---

### Deposit Analysis Page
![Summary Dashboard]([assets/summary_dashboard.png](https://github.com/Utkarshh-Raj/banking-risk-analysis-dashboard/blob/main/Banking%20Analysis/Banking/DashBoard/DEPOSIT_ANALYSIS.png))

---

### Summary Page
![Summary Dashboard]([assets/summary_dashboard.png](https://github.com/Utkarshh-Raj/banking-risk-analysis-dashboard/blob/main/Banking%20Analysis/Banking/DashBoard/SUMMARY.png))

---

## Dependencies
```bash
pandas
matplotlib
seaborn
mysql-connector-python
