# Analysis of Sports Clothing Industry Data  
This analysis explores data related to the sports clothing and athleisure attire industry, which is worth approximately $193 billion in 2021 with a strong growth forecast over the next decade. The goal is to help an online sports clothing company improve its revenue by diving into product data such as pricing, reviews, descriptions, and ratings, as well as revenue and website traffic. 

#### Data  
The database provided to us, sports, contains five tables, with product_id being the primary key for all of them:  

products: contains product information such as product name, description, and price.  
reviews: contains customer reviews for each product.  
orders: contains order information such as order date and revenue.  
order_items: contains information about the items in each order.  
web_events: contains information about website events such as page views and clicks.  

#### Skills  
- table aggregation  
- cleaning  
- labeling  
- Common Table Expressions(CTE)  
- correlation to produce recommendations on how the company can maximize revenue.  

#### Key Findings  

- **Adidas generates the most revenue**: Grouping products by brand and price range allows us to see that Adidas items generate more total revenue regardless of price category. Specifically, "Elite" Adidas products priced $129, so the company can potentially increase revenue by shifting their stock to have a larger proportion of these products.  

- **No discount is offered on Nike products**: In comparison, not only do Adidas products generate the most revenue, but these products are also heavily discounted. To improve revenue further, the company could try to reduce the amount of discount offered on Adidas products, and monitor sales volume to see if it remains stable. Alternatively, it could try offering a small discount on Nike products.  

- **Product reviews have a significant impact on revenue**: There is a strong positive correlation between revenue and reviews. The company should focus on encouraging customers to leave reviews, especially during the second, third, and fourth quarters of the year when review volume is lower. Running promotions or incentivizing customers to leave reviews during these periods could be effective.  

- **Website traffic has a strong correlation with revenue**: Higher website traffic generally leads to higher revenue. The company should invest in marketing and advertising to drive more traffic to its website.  

- **Seasonality affects revenue**: Revenue tends to be higher in the summer months and lower in the winter months. The company should adjust its inventory and marketing strategies to reflect this seasonality.  
