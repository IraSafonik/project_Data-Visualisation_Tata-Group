# Introduction
TATA Group is an Indian multinational conglomerate headquartered in Mumbai. Established in 1868, it is India’s largest conglomerate conglomerate which operates in more than 100 countries across six continents, with a mission ‘To improve the quality of life of the communities they serve globally, through long-term stakeholder value creation based on Leadership with Trust’. With a revenue of $128 billion (INR 9.6 trillion) in 2021–22, the companies collectively employ over 935,000 people. There are 29 publicly listed TATA enterprises — many being market leaders in their industries.

This virtual experience program is with one of their companies, TATA Insights and Quants or TATA iQ. You will gain insight into how our passionate multi-disciplinary experts solve some of the most complex business problems using data visualization solutions, such as Tableau and Power BI and create amazing stories which are hidden under the mountains of data generated.

The program gives an idea of what kind of problems are solved at TATA Insights and Quants on a day-to-day basis and will attempt to emulate the possible challenges to be faced.

## Task

### Question 1
The CEO of the retail store is interested to view the time series of the revenue data for the year 2011 only. He would like to view granular data by looking into revenue for each month. The CEO is interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year.

### Question 2
The CMO is interested in viewing the top 10 countries which are generating the highest revenue. Additionally, the CMO is also interested in viewing the quantity sold along with the revenue generated. The CMO does not want to have the United Kingdom in this visual.

### Question 3
The CMO of the online retail store wants to view the information on the top 10 customers by revenue. He is interested in a visual that shows the greatest revenue generating customer at the start and gradually declines to the lower revenue generating customers. The CMO wants to target the higher revenue generating customers and ensure that they remain satisfied with their products.

### Question 4
The CEO is looking to gain insights on the demand for their products. He wants to look at all countries and see which regions have the greatest demand for their products. Once the CEO gets an idea of the regions that have high demand, he will initiate an expansion strategy which will allow the company to target these areas and generate more business from these regions. He wants to view the entire data on a single view without the need to scroll or hover over the data points to identify the demand. There is no need to show data for the United Kingdom as the CEO is more interested in viewing the countries that have expansion opportunities.

## The Dataset
The data was gotten from Forage website which I downloaded and imported to Tableau Public.

### Raw Dataset
The dataset had 541909 entries and 8 columns;
Invoice No: Used to track payments
Stock Code: Product code
Description: Product details
Quantity: Number of purchases per product
Invoice Date: Date the product was purchased
Unit Price: Cost of product
Customer ID: A unique identifier assigned to customers
Country: Location the product was sold

## Data cleanup
Before starting any analysis, it is ideal to make sure that the data is cleaned properly. I noticed that the data contains some returns to the store which are provided in negative quantities and there are unit prices which were input in error. I was required to perform the following steps to cleaning this data.
Import and read data into Tableau Public.
Added filter for row values where the quantity is below 1 unit. (data includes values greater than or equel to 1)
Added filter for row values where the Unit price is below $0. (data includes values greater than or equel to 0)
*Additional I have created calculated field for Revenue value ([UnitPrice]* [Quantity])
The data cleaning and analysis were done using Tableau Public.



## Data Visualization
The data visualization was done with Tableau which I used to create charts, map and the Dashboard.

Data importation
The total quantity sold between 2010 and 2011 was 908,912 units

Total quantity sold
2. The total Revenue between 2010 and 2011 is $1.6M

Total Revenue
3. The Cost of Goods sold is $188.8K

Cost of Goods sold
4. The total profit made is $1.4M

Total Profit
5. Total number of Countries in the dataset is 35(excluding UK)

Total number of Countries(excluding UK)
6. The Country in which the most quantity was sold is the Netherlands, which sold a total of 200,361 units.

Quantity by Country
7. The customer with the highest revenue is the Customer with ID 14646, giving a total of $280,206.

Top 10 customer by revenue
8. The country that produced the highest Revenue and Quantity bought is Netherlands, giving a total of $285K and 200,361 respectively.

Revenue and quantity by Country
9. Map showing Quantity sold by Location

Quantity by Location
Final Dashboard

The Dashboard
Click HERE to interact with the dashboard.

# Conclusion and Recommendation
- Plans for more Stores to be opened in Netherlands should be initiated in order to generate more business and revenue for the company by meeting up the increasing demand coming from that location.
- There should be more awareness, campaigns, advertisements and promotions carried out in Japan and Sweden in order to boost sales and generate more revenue for the company.
- The Customer with the ID 14646 seems to be our most valuable customer, we’d need to maintain and improve the relationship, and provide them with exceptional service, support, and offer incentives such as discounts, exclusive offers, or rewards programs.
- Based on the data provided, February and April usually have the lowest sales. This should be further investigated to identity the causes and make proper amendments where necessary to enable improvements.

## What I learned from this program
- Framing the Business Scenario: How to frame and anticipate the questions your business leaders will need answers to.
- Choosing the Right Visuals: Which visuals are most effective in a given scenario.
- Creating Effective Visuals: Apply your under and create visuals based on business scenarios.
- Communicating Insights and Analysis: Effectively communicate your findings and explain how it relates to each scenario.

Thanks for reading.


