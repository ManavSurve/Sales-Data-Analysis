# Sale Data Analysis

### Dashboard Link : https://app.powerbi.com/groups/me/reports/384d017e-e935-44dc-9e7d-1626c1a36de1/ReportSection

## Problem Statement

 Retail managers currently lack a centralized, real-time view of sales performance across diverse geographic regions in India. Without clear visibility into Top 5 and Bottom 5 products by both revenue and quantity, the business struggles to optimize inventory levels, leading to stockouts of high-demand items like the Apple iPhone 14 and capital being tied up in low-performing products like Colgate Toothpaste.
 
 The company executes multiple promotional campaigns (e.g., Weekend Flash, Summer Sale, Festive Diwali), but there is no clear data on whether these discounts are translating into significant net sales or merely eroding profit margins. By analyzing the Average Discount by Promotion Category alongside a Profit vs. Net Sales correlation, the business needs to identify which promotions are truly effective and which are underperforming.
 
Fluctuating sales trends and seasonal demand make it difficult for stakeholders to forecast revenue and plan logistics. Current reporting methods are static and do not allow for period-over-period comparisons of Total Sales, Profit, and Quantity Sold. This dashboard aims to solve this by providing interactive filtering and trend analysis to identify growth patterns from 2020 to 2024.

​Geographic Insights: Identify high-performing cities (like Delhi, Mumbai, and Bangalore) to focus marketing efforts.

​Product Rationalization: Pinpoint the "Bottom 5" products to decide on potential discontinuation or rebranding.

​Correlation Analysis: Use the Scatter Plot (Profit vs. Net Sales) to detect outliers where high sales are not yielding expected profits.
​Would you like me to help you draft


### Steps followed 

- Step 1 : Business Requirements.
- Step 2 : Loading Data to PBI Desktop.
- Step 3 : Data Profiling & Data Transformations.
- Step 4 : Primary & Foreign Key.
- Step 5 : Cardinality
- Step 6 : Star Schema.
- Step 7 : Data Model Overview. 
- Step 8 : A Bar Chart was used to represent Average discount  by Promotion Categories.

 ![Image](https://github.com/user-attachments/assets/eb1a4839-acaa-4237-879e-b20cf6fe456d) 

  
- Step 9 : A Line Chart was used to represent Sales Trends By period.

  ![Image](https://github.com/user-attachments/assets/e0927fca-de6e-41da-9acd-4aaf08e43d52)
  
  
- Step 10 : A Map Chart was used to represent Sales By City.

 ![Image](https://github.com/user-attachments/assets/2076b72a-9965-4e5e-b848-973339db833c) 

  
- Step 11 : A Scatter Chart was used to represent profit V/S Net sales.

  ![Image](https://github.com/user-attachments/assets/0519cd64-288e-46fc-bca4-cc2dc7215b25)

 
- Step 12 : A Card visual was used to represent Numbers of Orders.

![Image](https://github.com/user-attachments/assets/a159b09c-ef81-4f7c-9a40-65238ddaf166)


- Step 13 : Different Types of Filters in Filters Pane

  
- Step 14 : Top Bottom 5 Products By Sales, Quantity and Profit.

          
- Step 15 : A Bar Chart was used to represent top 5 products by sale.

  ![Image](https://github.com/user-attachments/assets/53f06b31-a179-4045-983d-25dd18f16d23)


 - Step 16 : A Bar Chart was used to represent Bottom 5 products by sale.

   ![Image](https://github.com/user-attachments/assets/ea2abd65-77d2-41bd-940e-f5f4a0ed47d0)

 
 - Step 17 : A Bar Chart was used to represent Top 5 products by Quantity.

   ![Image](https://github.com/user-attachments/assets/fb9c616c-13d7-4305-9b39-b465a7d17317)

 
 - Step 18 : A Bar Chart was used to represent Bottom 5 products by Quantity.

 ![Image](https://github.com/user-attachments/assets/ea8ee0ce-e1a9-4eb0-a113-784080b37b98)
 
- Step 19 : A Bar Chart was used to represent Top 5 products by Profit.

  ![Image](https://github.com/user-attachments/assets/038ef703-070c-4ba2-8c5c-5b558cfac1ef)

- Step 20 : A Bar Chart was used to represent Bottom 5 products by Profit.

  ![Image](https://github.com/user-attachments/assets/71ac6d7e-bac4-4cb0-ab40-127aef357e11)

# Snapshot of Dashboard (Power BI Service)

![dashboard_snapo](https://user-images.githubusercontent.com/102996550/174096257-11f1aae5-203d-44fc-bfca-25d37faf3237.jpg)

 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](https://user-images.githubusercontent.com/102996550/174074051-4f08287a-0568-4fdf-8ac9-6762e0d8fa94.jpg)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Customers = 129880

   Number of satisfied Customers (Male) = 28159 (21.68 %)

   Number of satisfied Customers (Female) = 28269 (21.76 %)

   Number of neutral/unsatisfied customers (Male) = 35822 (27.58 %)

   Number of neutral/unsatisfied customers (Female) = 37630 (28.97 %)


           thus, higher number of customers are neutral/unsatisfied.
           
### [2] Average Ratings

    a) Baggage Handling - 3.63/5
    b) Check-in Service - 3.31/5
    c) Cleanliness - 3.29/5
    d) Ease of online booking - 2.88/5
    e) Food & Drink - 3.21/5
    f) In-flight Entertainment - 3.36/5
    g) In-flight service - 3.64/5
    h) In-flight Wifi service - 2.81/5
    i) Leg room service - 3.37/5
    j) On-board service - 3.38/5
    k) Online boarding - 3.33/5
    l) Seat comfort - 3.44/5
    m) Departure & arrival convenience - 3.22/5
  
  while calculating average rating, null values have been ignored as they were not relevant for some customers. 
  
  These ratings will change if different visual filters will be applied.  
  
  ### [3] Average Delay 
  
      a) Average delay in arrival(minutes) - 15.09
      b) Average delay in departure(minutes) - 14.71
Average delay will change if different visual filters will be applied.

 ### [4] Some other insights
 
 ### Class
 
 1.1) 47.87 % customers travelled by Business class.
 
 1.2) 44.89 % customers travelled by Economy class.
 
 1.3) 7.25 % customers travelled by Economy plus class.
 
         thus, maximum customers travelled by Business class.
 
 ### Age Group
 
 2.1)  21.69 % customers belong to '0-25' age group.
 
 2.2)  52.44 % customers belong to '25-50' age group.
 
 2.3)  25.57 % customers belong to '50-75' age group.
 
 2.4)  0.31 % customers belong to '75-100' age group.
 
         thus, maximum customers belong to '25-50' age group.
         
### Customer Type

3.1) 18.31 % customers have customer type 'First time'.

3.2) 81.69 % customers have customer type 'returning'.
       
       thus, more customers have customer type 'returning'.

### Type of travel

4.1) 69.06 % customers have travel type 'Business'.

4.2) 30.94 % customers have travel type 'Personal'.

        thus, more customers have travel type 'Business'.
