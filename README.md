# Data Cleaning in Excel (Bike Sales Data)

## Process
### Removing Duplicates.
   
   Duplicates are removed to make visualizations more clear and accurate.
   
### Find and replace.
- Change income column to currency
- Created a new column called Age bracket and use nested if to group different age group
  
   =IF(L2>54,"Old",IF(L2>=31,"Middle Age",IF(L2<31,"Adolescent","Invalid")))
### Add a pivot table 
1) Avg Income per purchase
![Avg Income per purchase](https://github.com/alnmrts02/Data-Cleaning-in-Excel/blob/main/Avg%20income%20per%20purchase.png)

2) Customer Commute
![Customer Commute](https://github.com/alnmrts02/Data-Cleaning-in-Excel/blob/main/Customer%20commute.png)

3) Customer Age Bracket
![Customer Age Bracket](https://github.com/alnmrts02/Data-Cleaning-in-Excel/blob/main/Customer%20age%20bracket.png)

### Create Dashboard
Using the charts derived from the pivot tables, a dashboard is created. [open](https://github.com/alnmrts02/Data-Cleaning-in-Excel/blob/main/Bike%20Sales%20Dashboard.xlsx)
