# Sales Analysis 2019/ 2020 #

## Project Overview ##
The project aimed to provide insights from the sales peroformance as at 2019/ 2020. 
The insight to be generated seek to identify the sales trend for the year under review which are needed 
for answering vital questions in the  company for Improvement.

![Sales Analysis Dashboard ](https://github.com/erebicraft/salesanalysis-meriskill/assets/137629549/8b11ab0e-69e6-48f6-8e00-9956d19b602f)

## Data Source ##
The Dataset used for this project is a [sales.csv files](https://github.com/erebicraft/salesanalysis-meriskill/blob/main/Sales%20Data.csv)
from Meriskill containing over 185,000 records and 10 fields. The Dataset is a semistructured and required some data cleaning.

 ## Tools Used  ##
 - Excel
 - MicroSoft Power BI
    - Data cleaning
    - Data Visulization
 ## Data Cleaning/ Preparation
   The data cleaning /praparation processes carried out are as follow:
   1. checked for duplicate using excel
   2. Data uploaded using the 'get data' option in power bi  and transformed the data
   3. changed of data types
   4. splitted the datetime into date and time stamp
## Exploratory Data Analysis ##
 EDA involved exploring the sales data to answer key questions, such as:
  1. What is the overall sales trend of the Company?
  2. which are the top five selling products by revenue?
  3. which are the top five selling products by count?
  4. Which are the top five cities by sales?
## Data Analysis ##
Some of Revenue metrics and New measures used to derived them

![KPI ](https://github.com/erebicraft/salesanalysis-meriskill/assets/137629549/1071bf99-769d-4535-9a65-8eddb8fbd96f)

```power bi
Total Sales = SUM('Sales Data'[Sales])
```
```power bi
Total Cost = SUM('Sales Data'[Price Each])
```
 ```power bi
 Profit Margin = (([Total Sales]-[Total Cost])/[Total Sales])*100
 ```
## Results / Findings ##
The analysis showed the following results:
1. ### The overall sales trend ###
There was an upward sales trend as showned in 2019 sales transaction, from  $1.8 million in the month of January to $4.6 milliom in the month of December as showed below ⬇️

![sales by month](https://github.com/erebicraft/salesanalysis-meriskill/assets/137629549/6c648646-3721-4eca-86ee-b7c129d514cb)

 However, a sharp fall in sales trend by year when the sales transaction of 2019 was compared to that made in 2020. It should be noted that the sales transaction of 2020 was only sales made in the month of January. 

![Sales by year trend](https://github.com/erebicraft/salesanalysis-meriskill/assets/137629549/89ba44bd-8cce-4661-ab72-2d63dee04091)

Further drilled into Sales of January 2019 and January 2020, showed a sharp fall from S1.8 million to $8.7k for 2019 and 2020 respectively.
This shows a fall of 99.5% from the previous year.

![Sales of January comparison](https://github.com/erebicraft/salesanalysis-meriskill/assets/137629549/034dcd24-e262-4ed2-9f91-872794b6fa72)

2. ### Five Top Selling Products by Revenue ###
   The top selling products by revenue are
    - AAA bateries (4-pack) with over $31k
    - AA bateries (4- pack) with over $28k,
    - USB -C Charging cable with over $24k,
    - Lighting charging cable with over $23k, and
    - Wired headphone with over $21k.

![top 5 selling products](https://github.com/erebicraft/salesanalysis-meriskill/assets/137629549/b35bbdc1-a7d0-4c6f-9986-30073a1f8bec)

3. ### Five Top Selling Products by Count ###

   Here are the top five products with the highest quantities sold:
   - Iphone with over 6.8k units sold,
   - 27in 4k Gaming cable with over 6.2k units sold,
   - Google phone with over 5.5k units sold,
   - Macbook pro laptop with over 4.7k units sold, and
   - Thinkpad laptop with over 4.1k units sold
     
![top products by sales count](https://github.com/erebicraft/salesanalysis-meriskill/assets/137629549/fc9c5452-3df2-4c23-aeb7-b8d5c8505b95)

4. ### Top Five Cities by Sales ###
 The top five cities where the sales revenue where generated were:
 - San Francisco with over $8.26 million,
 - Los Angelos with over $ 5.45 million,
 - New York with over $4.66 million,
 - Boston with over $3.66 million, and
 - Atlanta with over $2.70 million.
 
 ![Top 5 cities by sales](https://github.com/erebicraft/salesanalysis-meriskill/assets/137629549/8b7d2d26-ca8e-4787-a070-0247eebb8a13)

## Recommendations ##
Based on the analysis, we recommend the following:
1.  Invest in marketing and promotions during the peak sales session to maximise revenue.
2.  carrying out aggressive marketing in the second and third quarter will be vital to as to increase sales during the said peroid.
3.  Introduction of discount package to products with least quantity demand.
4.  Implementing  city segementation strategy to target cities with products highly demanded so as to increase revenue.
