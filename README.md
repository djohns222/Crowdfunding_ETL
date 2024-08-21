Project_2 - Drew Johnson & Titus Muchiri

The project involves building an ETL data pipeline using Python, Pandas and Jupyter Notebooks.
The raw data is provided in Excel format and is extracted and transformed then staged as CSV files.
The CSV files are subsequently used to create an ERD and table schema before finally being uploaded into a Postgres database. 
Within the resources folder in our REPO, there are the two xlsx files we were originally provided in addition to the four csv's exported as required.

This mini project has the following four subsections.
1. Creation of two DataFrames: Category and Subcategory
2. Creation of a Campaign DataFrame
3. Creation of a Contacts DataFrame
4. Creation of the Crowdfunding Database

Creation of Category and Subcategory DataFrames 
1. Category DataFrame - 
It is created by the extraction and transformation of data from an Excel file (crowdfunding.xlsx).
Below is an image extract from the DataFrame

![image](https://github.com/user-attachments/assets/5da42603-17ad-48b7-ae09-818c814df34e)


Subcategory DataFrame - 
This DataFrame is created by the extraction and transformation of data from the Excel file. Below is an extract of the resulting DataFrame.

![image](https://github.com/user-attachments/assets/980fda8f-35b8-4136-bccf-0a19b6bb440a)



2. Campaign DataFrame - 
After extraction and transformation of data from the Excel file, the following extract shows the resulting DataFrame.
![image](https://github.com/user-attachments/assets/56d000b9-2a44-4881-a0c1-48aa8b62da9c)


3. Contacts DataFrame - 
We used Python dictionary methods as one way to extract and transform the data.
Below ia an extract of the DataFrame.

![image](https://github.com/user-attachments/assets/9b20a817-14f1-4b53-8efe-86a21ad68caf)



4. Creation of the Crowdfunding Database - 
We used QuickDBD to design an entity relationship diagram(ERD)
![image](https://github.com/user-attachments/assets/3ba919ab-ecc9-4393-add0-e1ee48a69818)

