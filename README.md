# Introduction to Data Concepts and Working with Spreadsheets

 This session is designed for students who are new to data science and eager to learn foundational concepts and practical skills in excels. This README will provide description of some of the basic concepts covered during the event. 

**Prerequisites**:
- Basic familiarity with computers


## Spreadsheets 
Spreadsheets are used to store and represent data in tabular form, Microsoft launched their spreadsheet editor excel in 1985, it is one of the most widely used tools for data entry and basic data analysis since in financial institutions, entries and government 

### BASIC EXCEL FUNCTIONS 
![formula-representation](images\image.png)

Begin your formula by typing an equals sign (=) in the cell where you want the result to appear. This tells Excel that you are entering a formula.
To perform calculations, you need to reference the cells that contain the data. For example, if you want to add the values from cells A1 and B1, you would type =A1+B1 into the cell where you want the result.
Basic Opertions like Addition, Subtraction Multiplication & Divison as well as In-Built Functions (Mathematical, TEXT and LOGICAL) Can be performed on refrenced values. 

Some Basic Mathematical functions in excel : 

- **SUM** – Sum multiple values in Excel
- **MAX** – find the maximum value in a range
- **MIN** – find the minimum value in a range
- **COUNT** – Count numeric values in a range
- **COUNTA** – Count numeric and textual values that are non    empty 
- **AVERAGE** – Calculate average of a range

### Intermediate Concepts
- **IF CONDITIONAL** 

Syntax  :      *=IF(logical test,  [value if true]  ,  [value if false]  )*

- **COUNTIF** :

Syntax : *=COUNTIF(range,criteria)*
The COUNTIF function uses two arguments:

i) range – what is the range of cells in which we’d like to count cells which meet a certain criteria?

ii) criteria – what is the criteria we’d like to check?

- **COUNTIFS** : COUNTIFS function allows us to check multiple criteria within multiple columns, and to count the number of occurrences where all criteria were met.

- **UNIQUE** : UNIQUE returns unique values from a range.

Syntax : *=UNIQUE(array,[by_col],[exactly_once])*

- **VLOOKUPS** : VLOOKUP helps us lookup a value in table, and return a corresponding value.
A good example for VLOOKUP in real life is our “Contacts” app on the phone. We lookup for a friend’s name, and the app returns its number. 

Syntax : =VLOOKUP(lookup_value,table_array,col_index_num,[range_lookup]

- lookup_value – what we are looking for – this could be a text, number, or a single cell reference
- table_array – the range in which we will lookup for our value and its corresponding result. Please note that the range must start from the column which contains the value, and should contain the column in which we have our result.
-  col_index_num – What is the column number from which we want to return the result? The number should be relative to the first column in the selected range in table_array.
- [range_lookup] – Which range lookup method should be used. 0 is the default, so you should always type 0 (or FALSE), which means “Exact Match
 
 - **Pivot Tables** : tool for summarizing and analyzing data in Excel.
To create a new Pivot Table, we first need to select the data range which we would like to analyze, then click on one of the desired cells in our data range, then click Insert tab, then Pivot Table.

### Power Queries in excel 

Power Query is a data connectivity and transformation tool integrated into Excel (and other Microsoft products) that allows users to import, clean, and reshape data from various sources. It provides a user-friendly interface for performing data transformations without needing advanced programming skills. Power Query supports a wide range of data sources, including databases, web services, Excel files, and more.

1) Download the odbc connector 
odbc connector - https://dev.mysql.com/downloads/connector/odbc/
2) Windows + R and type  type odbcad32 
3) Configure the connection by entering details such as server address, port, username (root), password (1234), and the database name.
4) Open Excel and go to the Data tab.
5) Click on Get Data > From Other Sources > From ODBC
6) Select your configured DSN or import data from MySQL 



### 1. Basic Data Concepts you should know by now 
- **What is Data?**
- **Types of Data**
- **Data Formats**
- **Information and Data**
- **Need for Data Science**
- **Basic Components of Data Science**









