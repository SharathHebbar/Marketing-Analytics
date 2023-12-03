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

- CAC = Sales and Marketing(Salary, Overhead, PaidAds, Tools) / No. of New Customers
- It does not include the cost of RnD, Churn, Customer Success.
- CAC is not Cost Per Acquisition (CPA).
- CAC is not Cost per Click (CPC).
- Note: For **Freemium** apps like DropBox we need to calculate the CAC say for 60 months then the new customers can be acquired (Assumption: [User uses the app for 60 days as a trail and then he/she subscribes]).

### Points
1. CAC are all commercial costs per customers.
2. CAC is not CPA or CPC.
3. We might have to make CAC work for us.

## Customer LifeTime Value (CLTV) / (CLV) / (LTV)
- Say for example 
    - 1st time the customer spends 5$
    - so for 200 times it would be 5$ * 200 => 1000$
- Average Customer Lifetime would be calculated by taking average of customers lifetime say one customer stays for 5 years and other for 15 years the average would be 10 years.

- CLTV = ARPU * Average Customer Lifetime
    - Example: CLTV = $120/yr * 10 yr => 1200$

- CLTV = ARPU / Churn 
    - Example: 120/yr / 10% => $1200

## Inverted Churn Rate

1. The Inverse of Churn Rate
- Example: 1M / 10M = 10%
    - 1 / 10% = 10 years (Average time someone is a customer)

### Points
1. The longer your customer stays, the higher the CLTV
2.  CLTV = CLV = LTV
3. Average lifetime via Inverted Churn Rate.
4. CLTV to justify cost

    - CLTV: CAC => 3:1

| By Product | Product A | Product B | Product C |
| ---------- | ----------| ----------| --------- |
| ARPU | $1000 | $4000 | $3000 |
| Churn | ```10.0%``` | *5.0%* | **8.0%** |
| CLTV | $10000 | $80000 | $37500 |
| CAC | $2000 | $50000 | $5000 | 
| CLTV:CAC | 5:1 | ```1.6 : 1``` | *7.5 : 1* |

- Indicators: ```Red```, **Orange**, *Yellow*, Green

### Points
- Ratio can be useful for
1. Sales: What cost can I justify to acquire a new customer.
2. Marketing: How much can I spend on a campaign ?
3. Customer Support: How much can I spend to retain a customer ?
4. Strategy: What products and industries should the sales team focus on ?

### Organization Chart

![Organization Chart](https://github.com/SharathHebbar/Customer-Analytics/blob/master/KPI%20Metrics/Assets/org_chart.png)

## Net Promoter Score (NPS)

- How likely would you recommend 
    - A. Organization
    - B. Product
    - C. Service

1. NPS = (No. of Promoters - No. of Detractors) / No. of Total Responses
    - (60 - 20) / 100 => 40%
    - (20 - 60) / 100 => -40%

- Good NPS Score
    - Above 30 High
    - 0-30 Medium
    - below 0 Worst

<table>

<tr>
<th>Relational</th>
<th>Transactional</th>
</tr>

<tr>
<td>Regular Basis</td>
<td>After Customer Interaction</td>
</tr>

<tr>
<td>Year on Year Benchmark</td>
<td>Specific Topic</td>
</tr>

<tr>
<td></td>
<td>Best to use CAT</td>
</tr>

</table>

### Points
1. How likely would you recommend service to a friend.
2. Separate between Detractors, Passives and Promoters.
3. Detractors result in leaky bucket (```Churn```).
4. Promoters are free marketers.
5. 30% + is considered a high NPS.
6. Survey can be relational or transactional.
7. For transactional surveys use CSAT.

## CSAT: Customer Satisfaction Score

1. Straightforward and flexible.
2. Measures customer satisfaction with a 
    - Business
    - Purchase
    - Interaction such as 
        - Customer onboarding
        - Training
        - Event
3. CAT Score (%) = (Sum of all scores / Sum maximum possible score) * 100

### Points

1. Most straightforward customer KPI.
2. Measure satisfaction for business purchases or interactions.
3. Helps to pinpoint problems.
4. Combine with close-ended and open-ended questions.
5. Flexible Scale: 0-5, 1-10, unsatisfied-satisfied.
6. Pulse check overtime.
7. Dashboard for multiple topics and combine with ```NPS```.
8. Act upon it.

## Customer Effort Score (CES)

1. How easy it was for a customer to interact with your business.
- For example:
    1. After customer support.
    2. After purchase.
    3. After interaction with the product.

2. How to calculate CES
- CES Score(%) = ((Sum of all scores) / (Sum max possible score)) * 100
    - => (740 / 1000) * 100 => 74%

### How do I Compare ?
1. No Industry Wide standard.
2. Companies use different scales.
3. Regardless the higher the better.

### Points
1. Effort involved to interact with support, purchase, product.
2. The company made it easy for me.
3. Find the root cause with follow up questions ?
4. Transactional not relational.

## NPS vs CSAT vs CES

1. NPS (Net Promoter Score): How likely is a customer to recommend your product / services.
2. Customer Satisfaction Score (CSAT): How satisfied is a customer with an interaction / product / service.
3. Customer Effort Score (CES):  How much effort for a customer to interact with your service / product.

## Comparison

<table>

<tr>
<th>NPS</th>
<th>CSAT</th>
<th>CES</th>
</tr>

<tr>
<td>Overall Loyalty</td>
<td>Satisfcation</td>
<td>Effort Level</td>
</tr>

<tr>
<th>Advantages</th>
<th>Advantages</th>
<th>Advantages</th>
</tr>

<tr>
<td>

1. Proper Segmentation.
2. Less event Specific.
3. Unbiased
4. Meaningful
5. Long-Term
6. More Responses

</td>
<td>Very Detailed and flexible.</td>
<td>

1. How likely to refer
2. Actionable Data
</td>
</tr>

<tr>
<th>Disadvantages</th>
<th>Disadvantages</th>
<th>Disadvantages</th>
</tr>


<tr>
<td>

1. Require follow-ups
2. Tunnel-vision effect

</td>
<td>

1. Less likely to respond if unhappy.
2. Fear of admission.
3. Short Term.
4. Happy but not loyal

</td>
<td>

1. Usually no deal breaker.
2. Relevance.
3. No Segmentation.

</td>
</tr>

</table>

### Factors

1. NPS -> Overall Loyalty -> 5/5
2. CSAT -> Satisfaction -> 4/5
3. CES -> Effort Level -> 3/5