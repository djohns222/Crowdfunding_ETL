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
We used QuickDBD to design an entity relationship diagram(ERD) referencing each of the four dataframes created above.
![image](https://github.com/user-attachments/assets/3ba919ab-ecc9-4393-add0-e1ee48a69818)




Project 2 Discussion Questions
1) What are the challenges associated with ETL?
   
-DATA INTEGRATION
Integrating data from diverse sources can bring about difficulties to the ETL process. These include importing CSV files, leveraging APIs, and extracting information from web services into a desired format.

For our project, we were fortunate to have consistent files we imported into our VS code beginning with two XLSX documents and later, importing four CSV files into Postgres SQL. The consistency of the file types and data formats made it simple and repetitive to access all our data.

-DATA TRANSFORMATION
During ETL, there are times when complex logic is needed to ensure data sets are cleaned correctly. Ensuring correct syntax can be time consuming to achieve desired outputs.
One of bigger challenges we had while transforming the data was changing the format of the original data set’s dates.  The original format was a UNIX timestamp consisting of the number of seconds elapsed from a prior date. We needed unique functions to ensure we converted these to the correct format. 

2) What are the benefits of ETL?
   
-IMPROVED DATA QUALITY - 
ETL processes include data cleansing and transformation steps that correct inaccuracies, remove duplicates, and standardize data formats. This enhances the overall quality and reliability of data.

Throughout our data cleaning, we added and dropped columns, merged data frames, and altered data types that improve our outputs compared to the original sets.

-EFFICIENCY
The reduction of manual and repetitive tasks is a big focal point of many companies. Reasons include the elimination of human error, reduced operational costs, and more employee satisfaction by directing focus to more value-added work.
Without ETL for this project, our group would have had to work through many tedious, repetitive tasks that would have consumed a lot of time. With our code, we were able to speed up and eliminate the inefficiencies resulting in a more streamlined process.

3) How might ETL change when moving to the cloud?

-SCALABILITY AND PERFORMANCE
Cloud Environment: Cloud platforms offer dynamic scalability, allowing ETL processes to handle varying data volumes by automatically scaling resources up or down based on demand (Amazon Web Services, 2022).

Impact: ETL processes can be optimized for better performance without worrying about hardware limitations. 

-DATA STORAGE AND INTEGRATION
 Cloud Environment: Data storage in the cloud often utilizes services like Amazon S3, Google Cloud Storage, or Azure Blob Storage. These services provide virtually unlimited storage and seamless integration with cloud-based ETL tools (Microsoft Azure, 2022).

Impact: ETL processes can more easily integrate with diverse data sources, including cloud-native databases (e.g., Amazon Redshift, Google BigQuery) and on-premises systems, through APIs and connectors. Data lakes can also be leveraged for staging and processing large data sets.

-TOOLS AND TECHNOLOGIES
Cloud Environment: Cloud-based ETL tools like AWS Glue, Azure Data Factory, Google Dataflow, and cloud-native services provide managed ETL environments, eliminating the need for maintaining on-premises ETL infrastructure.

Impact: Organizations can use cloud-native ETL tools that offer features like serverless computing, automated data transformation, and real-time processing. 


REFERENCES

Amazon Web Services. (2022). Scalability in the Cloud. Retrieved from https://aws.amazon.com/scalability/
Microsoft Azure. (2022). Data Storage Options. Retrieved from <https://docs.microsoft.com/en-us/azure/storage/common/storage-int

