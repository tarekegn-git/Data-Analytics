About Dataset:  
This dataset contains a collection of fictional e-commerce transaction data created for data analysis, machine learning, and predictive modeling. It includes various e-commerce transaction attributes such as product categories, prices, discounts, payment methods, and purchase dates.

Context and Inspiration:  
The data was generated to provide a realistic representation of common e-commerce transaction patterns, making it ideal for practicing data science techniques such as regression, classification, and time-series forecasting. It is not based on real-world transactions but aims to simulate typical e-commerce behavior, offering valuable insights into pricing trends, payment method distributions, and customer purchase patterns.  
  
![Data Schema - Copy](https://github.com/user-attachments/assets/336f9a87-3e4f-4dfe-af9d-248911128c65)
  
The file ecommerce_dataset.csv contains a synthetic e-commerce transactions dataset designed to simulate typical online shopping activities. The data is organized into 8 columns, each representing key attributes of e-commerce transactions. This dataset can be used for various machine learning and data analysis tasks such as trend analysis, price prediction, payment method analysis, and discount impact studies.

File Content:  

User_ID: A unique identifier for each user (e.g., a shortened version of a UUID)
Product_ID: A unique identifier for each product (e.g., a shortened version of a UUID)
Category: The product category (e.g., Electronics, Clothing, Sports, etc.)
Price: The original price of the product before any discount is applied
Discount (%): The discount percentage applied to the product
Final_Price: The final price of the product after applying the discount
Payment_Method: The method used for payment (e.g., Credit Card, UPI, Net Banking)
Purchase_Date: The date when the transaction occurred, formatted as MM-DD-YYYY
File Format:  

Format: CSV (Comma Separated Values)
Number of Rows: 3660
Number of Columns: 8
  
  ![Dataset Organization](https://github.com/user-attachments/assets/6efd16e6-f5a2-4af9-96bb-7e072416c71d)

  1. Average Price per Product Category:  
     There are seven categories of goods sold in this case of e-commerce business. These are books, clothing, sports, beauty, electronics, home and kitchen, and toys. In this section, we will look into which product category has the highest average price and which one is the cheapest product by using Tableau charts. As shown in the figure below, Clothing items have the highest average price range compared to other categories where as Toys sell for relatively low price ranges in this particular e-commerce shop.  
     
    
![Category Average price](https://github.com/user-attachments/assets/33e22f93-51d2-49f5-b300-a8aac60d8a3c)

  In addition to the above bar chart, we can use the Tableau Chart summary feature to make a closer look into the exact average price range for each category as shown below.   
  
   ![Category Average price summary](https://github.com/user-attachments/assets/fad0ca63-00ba-4a98-960a-cab0d84b0a4a)

  Next, we evaluate if all products offer big discount as shown below  
![Category Dicount Pattern](https://github.com/user-attachments/assets/3a8245a7-6aeb-42be-87da-0f613431ff53)

    
