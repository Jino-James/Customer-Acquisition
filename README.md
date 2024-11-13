# Customer Cost Acquisition

## Introduction
Customer Acquisition Cost (CAC) Analysis is a critical metric for businesses to evaluate how much it costs to acquire a new customer. By calculating the total cost of sales and marketing efforts (including advertising, promotions, salaries, etc.) divided by the number of new customers acquired, businesses can assess the efficiency of their acquisition strategies.

A lower CAC indicates more efficient spending, while a higher CAC may signal the need for strategy adjustments. This analysis helps businesses allocate resources effectively, optimize marketing channels, and determine the profitability of acquiring new customers. Ultimately, it supports growth by ensuring that customer acquisition efforts align with the company's financial goals and long-term profitability.

# Objectives
The objective of this project is to analyze the cost-effectiveness of customer acquisition strategies by calculating and evaluating the Customer Acquisition Cost (CAC) for a business. The project aims to provide insights into the efficiency of marketing and sales efforts, identify opportunities for cost optimization, and suggest strategies for improving resource allocation

### Calculating the Customer Acquisition Cost

#### Code
``` python
df['CAC'] = df['Marketing_Spend']/df['New_Customers']

fig1 = px.bar(df, x='Marketing_Channel', y ='CAC', title = 'CAC by MArketing CHannel')
fig1.show()
```

#### Results
