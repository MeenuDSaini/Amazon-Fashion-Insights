# Amazon-Fashion-Insights
## Overview
This Power BI dashboard project analyzes sales and product data from Amazon, with a focus on the fashion category. It provides insights into sales trends, product performance, and inventory management.

## Aim and Objectives
### Aim:
The aim of this project is to provide comprehensive insights into Amazon's fashion segment to support data-driven decision-making.

### Objectives:
1. Visualize sales data to track performance and identify trends.
2. Analyze product-specific metrics to optimize inventory management and pricing strategies.
3. Enable users to filter and explore data dynamically for deeper insights.
4. Provide actionable insights to support sales and product management decisions.

## Description of Dataset
The dataset comprises two datasets downloaded from Kaggle: "Amazon" and "amazon-fashion- YT". 

### Amazon Dataset
The "Amazon" dataset serves to provide insights into sales and fulfillment activities on the Amazon platform. It captures information about products sold, orders placed, fulfillment details, and shipment information. 

**Description of Columns**:
1. **ASIN**: Amazon Standard Identification Number, a unique identifier assigned to each product on Amazon's platform.
2. **Category**: The category to which the product belongs, indicating its classification or type.
3. **Courier Status**: The status of the courier service responsible for delivering the order (e.g., in transit, delivered, pending).
4. **Date**: The date on which the transaction (sale or order placement) occurred.
5. **Fulfilled-by**:  indicates the entity responsible for fulfilling the order. This can include services such as Amazon's Fulfilled by Amazon (FBA), third-party logistics providers, or it may be left blank for orders not yet fulfilled. The presence of values such as "FBA" or third-party service names like "Easyship" denotes orders fulfilled by specific entities, while blank values may indicate pending fulfillment or orders awaiting processing.
6. **Fulfillment**: Describes the fulfillment method or process used for the order (e.g., Amazon or Merchant).
7. **Order ID**: A unique identifier for each order placed.
8. **Qty**: The quantity of the product purchased in the order.
9. **Sales Channel**: The channel through which the sale was made (e.g., Amazon website,Non-Amazon).
10. **Sales Price**: The price at which the product was sold.
11. **Ship City**: The city to which the order is being shipped.
12. **Ship Country**: The country to which the order is being shipped.
13. **Ship Postal Code**: The postal code or ZIP code of the shipping address.
14. **Ship Service Level**: The level of shipping service selected for the order (e.g., standard, expedited).
15. **Ship State**: The state or region to which the order is being shipped.
16. **Size**: The size of the product purchased (if applicable).
17. **SKU**: Stock Keeping Unit, a unique identifier assigned to each product variant.
18. **Status**: The status of the order (e.g., processing, shipped, delivered or pending).
19. **Style**: The style or variant of the product purchased (if applicable).

### amazon-fashion-YT Dataset
The "amazon-fashion- YT" dataset focuses on fashion products available on Amazon. It includes attributes related to product features, pricing, availability, and seller information.

**Description of Columns**:
1. **amazon_prime_y_or_n**: Indicates whether the product is eligible for Amazon Prime shipping (Yes/No).
2. **asin**: Amazon Standard Identification Number, a unique identifier assigned to each product on Amazon's platform.
3. **best_seller_tag_y_or_n**: Indicates whether the product has been tagged as a best seller (Yes/No).
4. **brand**: The brand or manufacturer of the product.
5. **category**: The category to which the product belongs, indicating its classification or type.
6. **colour**: The color or shade of the product.
7. **delivery_type**: Describes the type of delivery service available for the product (e.g., standard shipping, expedited shipping).
8.**description**: A brief description or summary of the product.
9. **discount_percentage**: The percentage of discount offered on the product.
10. **large.1**: Contains the url of images of products.
11. **left_in_stock**: The quantity of the product remaining in stock.
12. **no_of_reviews**: The number of customer reviews for the product.
13. **product_details**: Additional details about the product's features, materials, or specifications.
14. **product_name**: The name or title of the product.
15. **product_url**: The URL link to the product's page on Amazon's website.
16. **rating**: The average rating given by customers for the product.
17. **sales_price**: The price at which the product is being sold.
18. **seller ID**: The unique identifier of the seller offering the product.
19. **Seller_count**: The count of sellers offering the same product.
20. **seller_name**: The name of the seller offering the product.

## About Power BI Dashboard
## Overview Sheet
The Overview sheet presents key metrics and visualizations, including:

- Sales by city and state
- Courier status sales by month
- Total sale, total quantity, total sellers
- Slicers for filtering by product category, sales channel, size, style, and status.

## Products View Sheet
The Products View sheet offers detailed insights into product-specific metrics, including:

- Total sale, left in stock, total reviews, max rating, average discount percentage
- Average sales price by brand
- Slicers for filtering by product category, product name, brand, and category.

## Conclusion
In conclusion, the Amazon Fashion Insights project offers valuable insights into sales and product data on Amazon's platform. By visualizing key metrics and trends, this project aims to empower users to make informed decisions and drive business growth in the fashion category.

## Acknowledgments
I would like to express our gratitude to Kaggle for providing the datasets used in this project. 
