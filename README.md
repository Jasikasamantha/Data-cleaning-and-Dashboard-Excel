Data cleaning process and Dashboard creation in Excel.

1st step cleaning the data

1.	Removal of duplicate data (if any)
Select all > Data > Remove duplicate
2.	Proper naming convention of data. 
For example- replace “M” from the column of marital status by “Married” to distinguish “M” from the column of gender.
3.	Create one column to show age brackets with below logic-
=IF(L2>55,"Old",IF(L2>=31,"Middle age",IF(L2<31,"Adolescent","invalid")))

2nd Step build pivot table
1.	Create a pivot table to analyze Average Income of male and female who bought bike or not.
2.	Create a pivot table to analyze count of purchase bike against commute distance.
3.	Create a pivot table to analyze count of purchase bike against age.

3rd Step Build Dashboard

1.	This is for visualization based on 03 pivot tables created.  
2.	Bike Sales Dashboard with Slicer gave easy interactive visualization.

Referrence: 
https://youtu.be/opJgMj1IUrc?si=vhiNqKBGtouGyWpe
