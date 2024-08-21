Project_2
The project involves building an ETL data pipeline using Python, Pandas and Jupyter Notebooks.
The raw data is provided in Excel format and is extracted and transformed then staged as CSV files.
The CSV files are subsequently used to create and ERD and table schema before finally being uploaded into a Postgre database. 

This mini project has the following four subsections.
1. Creation of two DataFrames: Category and Subcategory
2. Creation of a Campaign DataFrame
3. Creation of a Contacts DataFrame
4. Creation of the Crowdfunding Database

Creation of Category and Subcategory DataFrames 
1. Category DataFrame
It is created by the extraction and transformation of data from an Excel file (crowdfunding.xlsx).
Below is an image extract from the DataFrame
![image](https://github.com/user-attachments/assets/0f3c07b7-6a48-4ce3-91c4-30abc1406c16)

3. Subcategory DataFrame
This DataFrame is created by the extraction and transformation of data from the Excel file. Below is an extract of the resulting DataFrame.
![image](https://github.com/user-attachments/assets/ddf75a63-48bf-4f62-ab70-710573ccad46)


4. Campaign DataFrame
After extraction and transformation of data from the Excel file, the following extract shows the resulting DataFrame.
![image](https://github.com/user-attachments/assets/56d000b9-2a44-4881-a0c1-48aa8b62da9c)


5. Contacts DataFrame
We used Python dictionary methods as one way to extract and transform the data.
Below ia an extract of the DataFrame.

![image](https://github.com/user-attachments/assets/9b20a817-14f1-4b53-8efe-86a21ad68caf)




We also used regular expressions(Regex) as an alternative method for the ETL.
Below is a sample extract of the DataFrame
![image](https://github.com/user-attachments/assets/05b496bf-cc54-4e9b-a270-6c849ff297ae)


Creation of the Crowdfunding Database
We used QuickDBD to design an entity relationship diagram(ERD)
![image](https://github.com/user-attachments/assets/3ba919ab-ecc9-4393-add0-e1ee48a69818)

