# Global-Trade-Analysis
Global Trade analysis project using Tableau Visualization Software

# The objective of the project is to create innovative and interactive Tableau dashboards 
that focus on potential commodities, countries, year, trade amount and quantity. 
The client wanted to launch a new business unit, focusing on global trade and logistics,
majorly in the countries such as USA, Canada and Australia The dataset provided by the client contained 59090 observations of 10 variables.
The client insisted the data to be cleaned using Excel or R. 
The Dataset contained missing values and was cleaned using the R programming language. Tableau dashboards should be created from the cleaned dataset.

# 1. Trade Market Analysis
Action:
1. Select the flow of trade and set the range of the year.
Insight:
1. Australlia hasnt reexported commodity since the year 1998- 2016
2. USA doent make aany Re-export of commodity
3. In the year 2016, Canada started its own re-exporting
4. Canada dominated the re-exporting.
5. USA makes the higest humber of export commodity than any other country.
6. Canada statarted re-exporting from thr year 2006
![Trade Market Analysis](https://github.com/Strictly4data/Global-Trade-Analysis/blob/main/Trade%20Market%20Analysis.png)

# 2. Market Size
Action:
1, Use the filter to select the flow trade and set to your desire.
Insight:
1. From 1998 to 2016, USA has the higest number of exporters.
2. The USA has never make any reexporting
![Market Size](https://github.com/Strictly4data/Global-Trade-Analysis/blob/main/Market%20Size.png)

# 3. Total Trade Value
Map based on Longitude (generated) and Latitude (generated).  Color shows details about Country Or Area.  The marks are labeled by sum of Trade Usd and Country Or Area.  Details are shown for Country Or Area. The data is filtered on Flow and Year. The Flow filter keeps Re-Export. The Year filter ranges from 1990 to 2016. The view is filtered on Country Or Area, which keeps Canada.
Insight:
The Map displaces the Total Tade in USD based on the selected Flow (Export, Import, re-export and re-import)

![Total trade Value](https://github.com/Strictly4data/Global-Trade-Analysis/blob/main/Total%20Trade%20Value.png)

# 4.Top categories
Action: 
Select the  Filter snd chsnge the country to your desire. Set the flow yo export, import etc
Insight:
1. There are 12 categories in the given dataset. Each categories has kits list of commodity
2. The trade is vaued in Billoon of US Dollas and it has been labled by each of the categories.
3. Per the country of Flow, we can observe that ranking of Categories based on Demand i.E Quantity,
![Top categoris](https://github.com/Strictly4data/Global-Trade-Analysis/blob/main/Top%20Categories.png)

# 5. Trade Balance
Action:
Select the country and the Flow of Trade from the filter tab, Adjust the year to your desire.

Observation:
The trade balance has been cal by subtracting the sum of export from sum of import. It measures the country's net income earned on international trade.

Insight:
1. The trade balance has been positive for the three countries throughout the year 1988 - 2016 , indicating Trade surplus.

![Trade Balance](https://github.com/Strictly4data/Global-Trade-Analysis/blob/main/Trade%20Balance.png)

# 6. Trade Balance Analysis
Action:
Select the country and Adjust the range of year to observe the changes over the Trade Balance for the year.

Observation:
We observe that the ranking of Country by the trade balance.

Insight:
1. The ranking is in this order Australia -> USA -> canada for the year 1988-2016
2. The ranking is in order Australia -> Canada -> USA for the year 2012-2006
3. Trade surplus may nnot be suitable for import business as Canada tends to level higher import duty on commodities. This is done so that domestic goods are consumed more than foreign gooda by their people.
![Trdae balance analysis](https://github.com/Strictly4data/Global-Trade-Analysis/blob/main/Trade%20Balance%20Analysis.png)

# 7. Top commodities 
Sum of Quantity for each Commodity.  Color shows details about Country Or Area. The data is filtered on Flow and Year. The Flow filter keeps Export. The Year filter ranges from 1988 to 2016. The view is filtered on Commodity and Country Or Area. The Commodity filter keeps 10 of 441 members. The Country Or Area filter keeps USA.
![Top commodities](https://github.com/Strictly4data/Global-Trade-Analysis/blob/main/Top%20Commodity%20based%20on%20Quantity.png)

# 8. Unit Price of the Commodity Over the year (1988-2016)
Action:
All countries are selcted by default. Adjust the year by it range and use the flow to select your desire option. Commodity can be searched by regular expression.
Observation:
The Unit Price equals  Trade Value (USD) / Quantity. The chat shows the Unit price for each commodity during the set period of year.
Insight:
1. Information on unit price can be seen from the selected country, flow of trade and commodity. For example, if we are interested in knowing the unit price for the export commodity, we can select the commodity filter. The line chart is colour coded based on the country.
2. We can can use forcasting techniques to find out future Unit price of the commodity.

![Unit Price of the Commodity Over the year (1988-2016)](https://github.com/Strictly4data/Global-Trade-Analysis/blob/main/Unit%20Price.png)


![Global Trade Analysis dashboard 1 ](https://github.com/Strictly4data/Global-Trade-Analysis/blob/main/Trade%20Market%20Part%201.png)

![Global Trade Analysis dashboard 2](https://github.com/Strictly4data/Global-Trade-Analysis/blob/main/Trade%20Market%20Part%201%20(2).png)
