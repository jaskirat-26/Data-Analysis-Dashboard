# Data-Analysis-Dashboard
Using my undersstanding of MySql and PowerBI I ventured into making my first solo project.

I took the following steps to complete this minor project:
  1. I downloaded a dump sql file which contained the information on sales of a dummy enterprise.
  2. Using the data import functionality of MySql I imported the data onto a database.
  3. After making sure that my sql server is online I went and installed Power BI
  4. Subsequently I imported the data into Power BI. I then performed the following ETL(Extract|Transform|Load) operations:
     4a. I deleted the duplicate records.
     4b. Then I went ahead and converted USD to INR without using any currency table and formed a new attribute called normalised currency.
  5. I then proceeded towards making a dashboard in which I included the following functionalities:
     5a. Sales quantity and Revenue Records.
     5b. Line Chart plotting the revenue as a function of time
     5c. Bar Graphs represting Revenue by Markets_Name, Revenue by Customer_name, Sales_Qty by Product_code
     5d. Pie Chart visualising Revenue earned by top 5 Products.
