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
1. For Recency say weughtage w1 - 100
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
<td></td>
<td></td>
<td></td>
</tr>

<tr>
<td></td>
<td></td>
<td></td>
</tr>

<tr>
<td></td>
<td></td>
<td></td>
</tr>

<tr>
<td></td>
<td></td>
<td></td>
</tr>

<tr>
<td></td>
<td></td>
<td></td>
</tr>

</table>