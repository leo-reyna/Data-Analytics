# About This Project

Maven Market is a multinational grocery chain with locations in Canada, Mexico, and the United States. Your task is to connect and transform the source data, build a relational data model, create calculated columns and measures, and design a report using various visualizations.

## Loading and Shaping the Data:

To start the project, I uploaded all the CSV files into Power BI and used the Power Query Editor to shape the data. I reviewed each data table to ensure the accuracy of all data types. In the Power Query Editor, I created new columns such as full name, birth year, has children (conditional column), discount price (calculated column), average retail price (using the Group By function), full address (calculated column using merge), area code, start of week, day name, start of month, month name, quarter, and year. I replaced all null values in the datasets with zeros and combined the 1997 and 1998 datasets through a connected folder. I updated all date fields to the MM/DD/YYYY format using the Modeling tab and formatted prices and costs as currency. Finally, I set all store fields as geographical locations.

## Data Model Creation

![My Picture](./Images/datamodelmaven.png)
