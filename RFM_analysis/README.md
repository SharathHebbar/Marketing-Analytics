# RFM Analysis

Often times a customer might have bought a high valued/priced items and then after that he might have not purchased anything and he might become highest sales valued customer.

RFM Analysis solves this issue by taking multiple factors into considerations

Definition: RFM (Recency, Frequency, and Monetary) analysis is most simple and proven techniques used by marketing people for customer segmentation.
- How recently (Recency).
- How oftenly (Frequency).
- How much did they buy (Monetary).

Procedure:
- Step 1: Understanding Data
    1. Example: We have data of 9 customers with date of purchase, frequency of purchase and sales value of each purchase.

- Step 2: Assigning recency score
    1. Arrange data in descending order basis according to last purchase data (say you are going with 3 bins)
    2. Assign 3 score to top 33% customers, 2 score to next 33% and 1 score to the bottom ones.

- Step 3: Assigning Frequency Score
    1. Arrange data in descending order basis according to the number of purchase.
    2. Assign 3 score to top 33% customers, 2 score to next 33% and 1 score to the bottom ones.

- Step 4: Assigning Monetary Score
    1. Arrange data in descending order basis according to total sales value(money)
    2. Assign 3 score to top 33% customers, 2 score to next 33% and 1 score to the bottom ones.

- Step 5: RFM score Calculation
    1. For Recency say weightage w1 - 100
    2. For Frequency say weightage w2 - 10
    3. For Monetary say weightage w3 - 1
    4. The formula would be R * W1 + F * W2 + M * W3
    5. Based on the formula calculate the RFM for each rows

- Step 6: Customer Classification basis on RFM Score
    1. You can create different types of customer segments with RFM Analysis, commonly used 6 segments are

<table>
<tr>
<th>Segments</th>
<th>Scores</th>
<th>Descriptions</th>
</tr>

<tr>
<td>Best Customer</td>
<td>R-3 F-3 M-3</td>
<td>These are the customers that bought recently, buys often and spends a lot. It's likely that they will continue to do so. Can market them without price incentive to preserve your profit margins.</td>
</tr>

<tr>
<td>Loyal Customers</td>
<td>F-3</td>
<td>Anyone with a high frequency should be considered loyal. This doesn't mean they have necessarily bought recently or that they spend a lot.</td>
</tr>

<tr>
<td>Big Spenders</td>
<td>M-3</td>
<td>They have spent a lot of money over their lifetime as a customer</td>
</tr>

<tr>
<td>New Spenders</td>
<td>212 or 313 or 321</td>
<td>They are new customers that spend a lot of money on their first order this is the kind of customer you need to invest into.</td>
</tr>

<tr>
<td>Lost Customer</td>
<td>121 or 131</td>
<td>Lost customers used to buy frequently at one point and spend a lot but they have stopped now. These are the customers companies/business needs to focus to bring them back</td>
</tr>

<tr>
<td>DeadBeats</td>
<td>111</td>
<td>These customers spent very little bought very few times and last ordered quite a while ago. They are unlikely to be worth much time.</td>
</tr>

</table>

- Step 7: Applications of RFM Analysis
    1. To improve customer lifetime values
        - Example: Reducing Churn, Cross selling (marketing, word of mouth), and selling high ticket items.
    2. For new product launches
        - Example: They can provide/give greater insights, refer a new customers.
    3. To minimize marketing costs and improve sales
        - Examples
            - Small segments of customers
            - Reduces Costs
            - Make decisions based on data