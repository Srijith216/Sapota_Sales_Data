# Sapota_Sales_Data
### All things Sapota 🫒

Meet Ram, the manager of Sapota Yield Agriculture Private Limited (SYA for short) at their Sai Bala Colony branch. SYA is an intermediary that procures Sapota from large Farm Businesses and sells it to retailers.

One way to understand that: SYA gets Sapota from a plant in Ooty and sells it to Big Bazaar in Erode. 

The amount they pay to the farmer is called Cost (buying price) and the amount they sell to Big Bazaar is called Price (selling price). They make money (their business model) by selling sapota for more than what they buy for. 

They procure from many farms and sell to many retailers. They have branches in 20 cities in Tamil  Nadu.

Our protagonist Ram manages their largest centre in Tamil Nadu -  located at Sai Baba Colony.

Their last week sales are given in the attached csv

[sales_data_1.csv](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/aa7904fd-b187-4627-9c7a-cfd065b66d64/sales_data_1.csv)

You are hired as a data scientist to help them optimize their business. Can you answer the following questions for them: (2 marks for each of the following questions)

1. What is their overall gross margin for their business?
2. Which vendor is the most profitable?
3. Which customer is the least profitable?
4. Which day of the week was most profitable for them?
5. Which day of the week was the least profitable for them?

Once you’ve answered these, they now share the quantity information. See the attached spreadsheet

[sales_data_2.csv](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3d260978-b9bd-496f-a95e-6470a4a686c4/sales_data_2.csv)

Ram is interested in understanding the short-term fluctuations and trends in their gross profit margins to better manage their inventory and cash flow. (5 marks for each of the following questions)

6. Can you calculate a 3-day average of the daily gross profit from the sales_data_2.csv? 
7. Additionally, provide insights into how this 3-day trend changes over the time period covered in the dataset.
8. Can you optimize the sales process to ensure gross margin is maximized?
    1. Would you fire any vendor?
    2. Would you let go of any customer? 
9. To ensure competitive pricing, Ram wants to benchmark their buying and selling prices against the market. Could you calculate the 25th, 50th (median), and 75th percentiles for both buying and selling prices? 
10. Additionally, analyze how often the Sapota’s prices fall below the 25th percentile or above the 75th percentile, potentially indicating they are buying at a high price or selling at a low price relative to their own transaction history.

Ram’s manager, Bharath comes in. 

11. Bharath says that Vendor 4 has to be honored.  What impact does it have on your optimal gross margin? 
12. Which vendor should we have a strategic tie up so that we source only from them (the goal here is to have the highest gross margin)
    - What’s the theoretical max margin the firm could have from that branch?
13. Given this is the ground truth, what is the price elasticity of Sapota for that branch? (If you increase by Rs.1, how much sales will go up/down and if you decrease price by Rs. 1, how much sales will go up/down)
