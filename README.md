# RFM-Analysis (Python)
## I. Introduction
### Why RFM?
- RFM stands for Recency, Frequency, and Monetary Value. It's a marketing analysis technique used to understand customer behavior.

  - **Recency**: How recently a customer made a purchase.
  - **Frequency**: How often a customer makes purchases.
  - **Monetary Value**: How much money a customer has spent.
- RFM helps identify and categorize customers based on their buying habits and spending.


### How?
- Customers are scored based on those three factors (Recency, Frequency, Monetary), and then labeled according to their RFM scores.
### Reference
- [RFM Analysis For Successful Customer Segmentation](https://www.putler.com/rfm-analysis)

### This dataset includes all transactions from 01/12/2010 to 09/12/2011 for a UK-based online retail store that sells unique all-occasion gifts. Most customers are wholesalers.


- **InvoiceNo**:  A 6-digit number unique to each transaction. If it starts with 'C', it's a cancellation.
- **StockCode**: A unique 5-digit code for each product.
- **Description**: The name of the product.
- **Quantity**: Number of products per transaction.
- **InvoiceDate**: The date and time when the transaction happened.
- **UnitPrice**: Price per unit in sterling.
- **CustomerID**: A 5-digit number unique to each customer.
- **Country**: The country where the customer lives.

### Business Questions:
- The Marketing Department needs to classify customer segments to tailor each marketing program to the right group.

- The Marketing Director suggests using the RFM model in Python to segment customers. This will help launch marketing campaigns to thank current customers and turn potential ones into loyal customers.

- For the Marketing and Sales team: with our retail model, which of the three indicators—Recency, Frequency, and Monetary—should we focus on the most?

## II. Data Visualization with Python
* Distribution of Recency
![image](https://github.com/user-attachments/assets/052433e6-a109-4d1d-af83-f3ae41de6584)
* Distribution of Frequency
![image](https://github.com/user-attachments/assets/84704d8f-fef2-4450-bc5a-b9c4f87b77bc)
* Distribution of Monetary
![image](https://github.com/user-attachments/assets/f6644b1e-6ad0-4488-805f-9d9eb7f4f03e)
* RFM Segments of Customer Count
![image](https://github.com/user-attachments/assets/603fc638-dcf6-47bd-9bef-1207b6daa2eb)
* RFM Segments of Total Sales
![image](https://github.com/user-attachments/assets/6b423a20-6b86-4e93-8422-7dd3927a5a65)


## III. Insights
- Customer Behavior Insights:
  -  The key metrics for SuperStore are Frequency (F) and Recency (R). Most customers make only one or two purchases, and few become long-term buyers (8-9 times or more). This indicates a need to improve customer retention.
- Customer Segmentation:
  - The company primarily deals with “New Customers,” followed by “Hibernating Customers” and “Lost Customers.” This highlights the importance of the Frequency (F) metric.
- Revenue and Profit:
  - The highest profit and rev come from “New Customers.”
- Regional Analysis:
  - The East region has the lowest revenue compared to the other three regions.
- Top States:
  - California, Texas, and Illinois have the highest order volumes, while Florida trails behind.
- Customer Types:
  - Consumers make up 52%, Corporate customers account for 30%, and Home Office customers cover the rest.
- Popular Categories:
  - “Office Supplies” dominate with 60% of orders, followed by “Furniture.”
- Key Subcategories:
  - The main subcategories are Art (9%), Paper (14%), Binders (15%), and Phones and Storage (8%).
## IV. Recommendations
To put these insights into action, here are some strategies for SuperStore:



- Retaining New Customers:
  - Send personalized welcome emails after their first purchase.


  - Use targeted email marketing to encourage one-time buyers to make a second purchase.
  - Offer special discounts or promotions to bring them back.
  - For high-value customers, show gratitude and introduce a loyalty program.
- Promoting Hibernating Customers:
  - Send win-back emails or personalized offers to those who haven't shopped in a while.
  - Tailor discounts based on their previous purchases.
  - Keep multiple-purchase customers engaged with email campaigns that showcase new products.
  - Highlight new offerings to high-value customers who haven’t purchased recently.
- Targeted Marketing:
  - Develop a marketing strategy focused on the “Consumer” segment, particularly in states like California, Texas, and Illinois, compared to Florida.
