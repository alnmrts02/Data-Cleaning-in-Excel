# Data Cleaning in Excel (Bike Sales Data)

## Process
### Removing Duplicates.
   
   Duplicates are removed to make visualizations more clear and accurate.
   
   DATA `→` REMOVE DUPLICATES
  
### Find and replace.
- Change income column to currency
- Created a new column called Age bracket and use nested if to group different age group
  
   =IF(L2>54,"Old",IF(L2>=31,"Middle Age",IF(L2<31,"Adolescent","Invalid")))
### Add a pivot table 
1) Avg Income per purchase
2) Customer Commute
3) Customer Age Bracket
- Create Dashboard
