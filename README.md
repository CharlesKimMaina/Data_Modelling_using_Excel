# Data_Modelling_using_Excel, replacing VLOOK-Ups
#Import (GET DATA) the first main data into excel, click transform to send it to power query just incase you need to clean it or reformat it or add extra columns.
#On power query on the right-most corner, click SOURCE, then file and get excel importing the 2nd file n when the 2nd data excel is loaded, click OK. Now yout have 2 files in the power query.
After the 2files are loaded, click CLOSE and LOAD TO and load it in POWERPIVOT and tick✅ add this data to Data model (so that we can do the relationship) and click OK. 
Now go to DATAMODEL, by clicking DATA, then the GREENHOUSE-ICON, click it and enable, and it now opens POWERPIVOT for us, 
On POWERPIVOT, click DIAGRAM VIEW on the3rd right-most icon, called "Diagram-view".
Connect both Data by using common column which is in both datas eg ID etc by dragging primary key to foreign key. Click DATAVIEW on top beside Diagram-view n check if the data is still okey.
Now minimise POWERPIVOT for now, go back back to EXCEL window and click INSERT and insert PIVOT TABLE. 
Insert, select PIVOT TABLE from DATA-MODEL (with GREENHOUSE-ICON)and choose where your pivot table will be be it in new sheet or existing sheet n OK.
Now you can see the 2 data we loaded before on PIVOTTABLE FIELDS, The datas loaded from DATAMODEL has DB-ICON on them resembling a drum (pipa)
You can now start dragging different columns to diffrent fields eg ROWS, COLUMNS, FILTERS, VALUE etc 
Now you can create different pivot tables of your liking and analyse your data. 
Now in your pivot table, right click it and select "Pivot Table Options", click display and tick✅"Classic Pivottable layout- enables dragging of the fields in the grid" n OK. 
On your PIVOT TABLE, you can expand or collapse it if you like. Collapse to see all table, expand to see hierarchies in the table structure. 
You can add a filter eg with 1 column , it acts as a slicer eg citizenship-column where you can select-Filter(Yes/no ) EU and non-EU students.
