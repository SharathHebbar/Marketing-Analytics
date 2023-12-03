# KPI / SaaS Metrics

## Churn
1. Churn: The customers who are leaving is referred as Churn
- Churn Rate: The rate at which customers are churning away
    - ```Churned / Total Customers = Churn Rate```
- The ```Growth Rate``` should be greater than ```Churn Rate```

    - Example of Churn Rate with respect to Churn.
<table>

<tr>
<th>Churn</th>
<th>Customers</th>
<th>Churn Rate</th>
</tr>

<tr>
<td>2 M</td>
<td>10 M</td>
<td>20 %</td>
</tr>

<tr>
<td>4 M</td>
<td>40 M</td>
<td>10 %</td>

</tr>

</table>

**Note: We need to compare Churn Year-on-Year for seasonal data like games or waterpark activities in summer**

- Some indicators

| Revenue | Customer | Performance |
| ------------- | ------------- | ------------- |
| Revenue Churn Increases | Customer Churn Decreases | Not Good for the company |
| Revenure Churn Decreases | Customer Churn Increases | Good (Atleast Revenue is good) |

### Points
1. Churn Rate: Ratio of terminating Customers to existing customers.
2. Churn is like Leaky Bucket it always leaks(decreases).
3. Inverted Churn Rate = Average Customer Lifetime Value

## MRR and ARPU

1. MRR: Monthly Recurring Revenue
- Sum of Monthly fees by every customer
- MRR = ARPU * Customers 

2. ARPU: Average Revenue per user
- ARPU = Revenue (month / year) / Users (month / year)

3. ARPA: Average Revenue per Account
- ARPA = Revenue (month / year) / Account (month / year)

MRR = $100/month * 10 = $100

ARR = MRR * 12 (Annual Recurring Revenue)

### Notes
1. MRR and ARR shows direct growth of the company
2. Forecasting
3. Better budgeting for sales and marketing

### Avoid these
1. Including quarterly, semi-annual contracts at full value in a single month
2. Including one time payments like setup fees or non-recurring add-ons
3. Forgetting to use the discounted price

- MRR can be divided into 3 groups
1. New MRR: Additional MRR from new customers
2. Expansion MRR: Additional MRR from existing customers (aka "upgrades")
3. Churned MRR: MRR lost from cancellations or downgrades

=> Net New MRR (aka Growth MRR ) = New MRR + Expansion MRR - Churned MRR

- ```Net Negative Churn```: This is the revenue earned by additional addons, upgrades which might negates Churn
    - Net Negative Churn = (Churned MRR - Expansion MRR) / Total MRR
    - Example: Net Negative Churn = (10K - 15K) / 100K => -5 %

### Points
1. MRR is the main indicator of every SaaS business
2. We can  use ARPU to calculate MRR
3. ARR is MRR * 12
4. Net New MRR aka Growth MRR
5. Net Negative Churn
6. Forecast

## CAC: Customer Acquistion Cost

