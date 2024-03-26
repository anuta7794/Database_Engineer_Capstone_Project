# **Database_Engineer_Capstone_Project**

This work is a part of Capstone project for Meta Database Engineer Certificate. I demonstrate my new data visualization skills by helping Little Lemon restaurant complete a series of database related tasks. These tasks include setting up a database in MySQL workbench using a MySQL instance server, creating an Entity Relationship Diagram and implementing it in MySQL workbench, and finally generating data insights using data analytics.

## **Task 1.**

•	Set up a MySQL instance server in MySQL Workbench.

•	Create and implement an ER diagram data model.

### _*Scenario:*_

Little Lemon needs to build a robust relational database system in MySQL in which they can store large amounts of data. They then need to easily manage and find this data as required. This database system should maintain information about the following aspects of the business: 
	Bookings.
	Orders.
	Order delivery status.
	Menu.
	Customer details.
	and Staff information.

In the first task, I built a relational database system for Little Lemon Restaurant by designing a well-structured entity model or Diagram that conforms to the three fundamental normal forms. I designed the Diagram using MySQL workbench, a unified visual tool used for database modeling and management. Forward Engineering was applied to create a database from this relational model.

![image](https://github.com/anuta7794/Database_Engineer_Capstone_Project/assets/153844737/4c538579-395b-4c6e-ba21-5d0360465128)


 

Task 2.

•	Work with Tableau to create interactive dashboards.

In the next task, I helped Little Lemon use their data to generate business insights. I carried out this task using Tableau, the data visualization tool. I used LittleLemonDB Excel file as my data source. You'll first connect your data sources to tableau. I then prepared my data for analysis and focused on the most relevant data. The next step was to create a visualization of my data using its UI elements. Finally, I used Tableau to produce interactive real time data visualizations in the form of dashboards.

Scenario:

Little Lemon has an Excel sheet file with thousands of records of data on orders made between 2019 and 2023. Little Lemon needs to filter the data, analyze it and create visual charts in the form of an interactive dashboard to help them understand their business performance, so they can increase their sales and profits.

Prerequisites:

LittleLemonDB Excel.xlsx

Steps:

1)	I connected to Little Lemon data stored in the Excel Sheet called LittleLemonDB. Then I filtered data in the data source page and selected the United States as the country.
2)	I created a new data field that stores the profits for each sale.
3)	I created a bar chart “Customers Sales” that shows customers sales and filtered data based on sales with at least $70.
4)	I created a line “Profit Chart” to show the sales trend from 2019 to 2022.
5)	I created a “Sales Bubble Chart” for all customers. Once you roll over a bubble, the chart shows the name, profit and sale.
6)	Then, I needed to compare the sales of the three different cuisines sold at Little Lemon. I created a “Cuisine Sales and Profits” bar chart that shows the sales of the Turkish, Italian and Greek cuisines. Then, I displayed sales data for 2020, 2021, and 2022 only. Each bar displays the profit of each cuisine. 
7)	In this final task, I needed to create an interactive dashboard that combines the Bar chart called Customers sales and the Sales Bubble Chart. Once you click a bar, and roll over the related bubble, the name, sales and profit figures should be displayed in the Bubble chart as shown below.

Link to the viz/final dashboard in Tableau Public:

[Tableau Public "Little Lemon Sales Report"](https://github.com/anuta7794/Database_Engineer_Capstone_Project/blob/bad50d355f6683624ad1b73ed38c5a7059fb0587/Tableau_Sales_Report/Tableau)
