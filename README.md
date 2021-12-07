# ETL-Project-2

December 1, 2021
Emerson College Bootcamp, Data Analytics
Stephanie Thurstone 
Project II: Airbnb Market Statistics, Boston vs. New York City
Purpose: Generate a database of information re: Boston and NYC Airbnb statistics in an effort to assess which is the better investment to purchase rental property.  

Data Utilized: 
	https://www.kaggle.com/airbnb/boston
	https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data

Procedures (extract, transform & load):
I)	Extract: 
a.	Generate a new folder for Project II to hold all pertinent documents
b.	Conducted research of Airbnb Data sources via Kaggle, etc.
c.	Download CSV files to Project II folder
II)	Transform:
a.	 Analyze the extracted data to determine the transformation processes required (clean, join, filter, aggregate, etc.)
b.	Generate a Notebook that will read the CSV files for transformation processes
•	Clean Data – rename column headers
•	Filter – remove unnecessary columns
•	Merge – merge data frames into a single dataset
III)	Load: 
a.	Connect Notebook to local host database - pgAdmin 
b.	Create a new Database in pgAdmin 
c.	Prepare schema and create tables 
d.	Run Notebook to populate data into the DB Tables  
