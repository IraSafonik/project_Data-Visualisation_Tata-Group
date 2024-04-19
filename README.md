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
- The dataset had 541909 entries and 8 columns;
- Invoice No: Used to track payments
- Stock Code: Product code
- Description: Product details
- Quantity: Number of purchases per product
- Invoice Date: Date the product was purchased
- Unit Price: Cost of product
- Customer ID: A unique identifier assigned to customers
- Country: Location the product was sold

## Data cleanup
Before starting any analysis, it is ideal to make sure that the data is cleaned properly. I noticed that the data contains some returns to the store which are provided in negative quantities and there are unit prices which were input in error. I was required to perform the following steps to cleaning this data.
- Import and read data into Tableau Public.
- Added filter for row values where the quantity is below 1 unit. (data includes values greater than or equel to 1)
- Added filter for row values where the Unit price is below $0. (data includes values greater than or equel to 0)
- *Additional I have created calculated field for Revenue value ([UnitPrice]* [Quantity])
- The data cleaning and analysis were done using Tableau Public.

<img width="1440" alt="Знімок екрана 2024-04-11 о 13 25 44" src="https://github.com/IraSafonik/project_Data-Visualisation_Tata-Group/assets/32171563/e60e33dc-d859-4a83-89a4-a72a7872dab2">

## Data Visualization
The data visualization was done with Tableau which I used to create charts, map and the Dashboard.

### Total quantity sold
1. The total quantity sold between 2010 and 2011 was 5,660,979 units

### Total Revenue
2. The total Revenue between 2010 and 2011 is $10.6M

### Cost of Goods sold
3. The Cost of Goods sold is $2.1M

### Total Profit
4. The total profit made is $8.6M

### Total number of Countries
5. Total number of Countries in the dataset is 38

### Revenue and quantity by Country
6. The country that produced the highest Revenue and Quantity bought is Netherlands, giving a total of $285K and 201K units respectively.
<img width="1440" alt="Знімок екрана 2024-04-11 о 16 15 11" src="https://github.com/IraSafonik/project_Data-Visualisation_Tata-Group/assets/32171563/e82b3d90-7b5e-42c1-83c8-7deed45ffc5d">

### Top 10 customer by revenue
7. The customer with the highest revenue is the Customer with ID 14646, giving a total of $280K.
<img width="1440" alt="Знімок екрана 2024-04-11 о 16 15 21" src="https://github.com/IraSafonik/project_Data-Visualisation_Tata-Group/assets/32171563/19408f05-c310-4763-9817-ef88501d76fd">

### Quantity by Location
8. Map showing Quantity sold by Location
<img width="1439" alt="Знімок екрана 2024-04-11 о 16 16 31" src="https://github.com/IraSafonik/project_Data-Visualisation_Tata-Group/assets/32171563/4eb42139-2f1d-434c-8064-0ae7a6361277">


## Final Dashboard
<img width="1181" alt="Знімок екрана 2024-04-11 о 16 17 30" src="https://github.com/IraSafonik/project_Data-Visualisation_Tata-Group/assets/32171563/6b16c11b-9649-4dee-b4da-767701a422a3">

[Tableau Public](https://public.tableau.com/views/TataRetailAnalysis_17128400337470/TATARETAILANALYSIS?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

# Conclusion 
- The analysis of the retail store's data from 2010 to 2011 reveals significant insights into its performance and customer behavior.
- Total revenue for the period was $10.6 million, with a total quantity sold of 5,660,979 units, resulting in a profit of $8.6 million after accounting for a cost of goods sold of $2.1 million.
- The dataset includes sales data from 38 countries, with the Netherlands leading in both revenue and quantity sold.

# Recommendation
- Expansion in Netherlands: Considering that the Netherlands emerged as the top-performing country in terms of revenue and quantity sold, it's prudent to initiate plans for opening more stores in the region. By capitalizing on the increasing demand observed in the Netherlands, the company can significantly boost its business and revenue.
- Marketing Focus on Japan and Sweden: Given the potential for growth in Japan and Sweden, it's essential to implement targeted marketing campaigns, advertisements, and promotions in these regions. Increasing awareness and visibility of the company's products can stimulate sales and generate additional revenue.
- Customer Relationship Management for ID 14646: Customer ID 14646 stands out as the most valuable customer, contributing a significant amount to the company's revenue. To maintain and enhance this valuable relationship, the company should prioritize providing exceptional service, personalized support, and exclusive incentives such as discounts or rewards programs.
- Addressing Low Sales Months: Analysis of the data indicates that February and April consistently exhibit lower sales compared to other months. Further investigation into the underlying causes of these trends is necessary to implement appropriate strategies for improvement. By identifying and addressing any potential issues or obstacles, the company can optimize sales performance throughout the year.

## What I learned from this program
- Understanding Business Scenarios: Gained insights into framing and predicting the questions that business leaders will require answers to.
- Selecting Appropriate Visuals: Learned to choose the most suitable visuals for specific scenarios to convey information effectively.
- Crafting Impactful Visuals: Utilized your understanding to create visuals that accurately represent business scenarios and insights.
- Articulating Insights and Analysis: Developed skills in effectively communicating findings and illustrating their relevance to each scenario.

Thanks for reading.


