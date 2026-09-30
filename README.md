ecommerce-sales-powerbi-dashboard
An interactive Power BI dashboard that turns a year of e-commerce order data into clear answers: what sells, where it sells, how customers pay, and whether the business is actually making money.

About the Project
I built this dashboard to practice the full analytics workflow: cleaning and modelling raw data, writing DAX measures, and designing a report a business user could read in under a minute. It analyses 500 orders (1,500 line items) from 2018 across 19 Indian states, joining order details with customer and location data.

What the Dashboard Answers
- How much revenue and profit did the business generate, and how did that change month to month?
- Which states and product sub-categories drive sales and profit?
- How do customers prefer to pay?
- How do results shift across quarters? (interactive Quarter slicer)

Headline Numbers
Total Sales - ₹437,771 
Total Profit - ₹36,963 
Units Sold - 5,615 
Average Order Value - ₹876 

Key Insights
- Sales are concentrated in two states : Maharashtra (~₹102K) and Madhya Pradesh (~₹87K) together bring in over 40% of revenue.
- Clothing sells the most units, but not the most revenue : It makes up 63% of units sold, yet Electronics leads in sales value (38%), so Clothing is a high-volume, low-ticket category.
- Profit is uneven through the year : Strong in Q1 and in November, but May, July, September and December ended in a loss, which is worth investigating (discounting, low-margin products).
- Cash on Delivery dominates: COD accounts for the largest share of transactions (44%), followed by UPI (21%).
- A few big orders lift the average : The average order is ₹876, but the median is only ~₹422, so most orders are much smaller than the average suggests.

Tools & Skills
Power BI · Power Query · Data Modelling (Orders ↔ Details) · DAX · Dashboard Design

Dataset
- `Orders.csv`: order ID, date, customer, state, city
- `Details.csv`: amount, profit, quantity, category, sub-category, payment mode

How to Use
1. Download `SALES_DASHBOARD.pbix`
2. Open it in Power BI Desktop
3. Use the Quarter slicer to explore the data
