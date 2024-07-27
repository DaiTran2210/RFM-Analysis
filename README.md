# RFM-Analysis (Python)
## I. Introduction
### Why RFM?
- RFM is a marketing analysis technique that stands for Recency, Frequency, and Monetary Value.
  - **Recency**: measures how recently a customer has made a purchase.
  - **Frequency**: measures how often a customer has made purchases.
  - **Monetary Value**: measures the total amount of money a customer has spent on purchases.
- RFM is used to identify and categorize customers based on their purchasing behavior and how recently and frequently they have made purchases, as well as the monetary value of those purchases.
### How?
- In RFM analysis, customers are scored based on three factors (Recency - how recently, Frequency - how often, Monetary - how much), then labeled based on the combination of RFM scores
### Reference
- [RFM Analysis For Successful Customer Segmentation](https://www.putler.com/rfm-analysis)

### This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

- **InvoiceNo**: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'C', it indicates a cancellation.
- **StockCode**: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
- **Description**: Product (item) name. Nominal.
- **Quantity**: The quantities of each product (item) per transaction. Numeric.
- **InvoiceDate**: Invoice Date and time. Numeric, the day and time when each transaction was generated.
- **UnitPrice**: Unit price. Numeric, Product price per unit in sterling.
- **CustomerID**: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- **Country**: Country name. Nominal, the name of the country where each customer resides.

### Business Questions:
- The Marketing Department needs to classify the segments of each customer to deploy each marketing program suitable for each customer group.
- The Marketing Director also proposed a plan to use the RFM model in Python to segment customers, and then launch marketing campaigns to thank customers for supporting the company over the past time. As well as exploit potential customers to become loyal customers.
- Suggestions to the Marketing and Sales team with the company's retail model, which of the three indicators R, F, and M should be most interested in?

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
  -  The most critical indicators for SuperStore are Frequency (F) followed by Recency (R). Many customers make only one or two purchases, while very few become long-term buyers (8-9 times or more). This suggests that customer retention needs improvement.
- Customer Segmentation:
  - The company primarily deals with “New Customers,” followed by “Hibernating Customers” and “Lost Customers.” Again, emphasizing the importance of the Frequency (F) index.
- Revenue and Profit:
  - The highest revenue and profit come from “New Customers.”
- Regional Analysis:
  - The East region has the lowest revenue compared to the other three regions.
- Top States:
  - California, Texas, and Illinois have the highest order volumes compared to Florida.
- Customer Types:
  - Consumers account for 52%, Corporate customers for 30%, and Home Office customers for the remaining share.
- Popular Categories:
  - “Office Supplies” account for 60% of orders, followed by “Furniture.”
- Key Subcategories:
  - The main subcategories are Paper (14%), Binders (15%), Art (9%), and Phones and Storage (8%).
## IV. Recommendations
To address these insights, SuperStore should consider the following strategies:

- Retaining New Customers:
  - Send personalized welcome emails to new customers after their first purchase.
  - Encourage one-time buyers to make a second purchase through targeted email marketing.
  - Offer special discounts or promotions to incentivize return visits.
  - For high-value customers, express gratitude and introduce a loyalty program.
- Promoting Hibernating Customers:
  - Reach out to hibernating customers with win-back emails or personalized offers.
  - Tailor discounts based on their past purchases.
  - Engage multiple-purchase customers with email campaigns showcasing new products.
  - Highlight new offerings to high-value customers who haven’t purchased recently.
- Targeted Marketing:
  - Develop a marketing strategy focused on the “Consumer” segment, particularly in states like California, Texas, and Illinois, compared to Florida.
