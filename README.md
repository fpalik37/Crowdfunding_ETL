Project 2 - README 

On an auspicious two days last week, an ambitious trio of GW Data Analytics Bootcamp students collaborated on a project to build a mini ETL pipeline.  The trio (Alexandrea de Roos, Emily R., and Francesca Palik) used Python, Pandas and Python dictionary methods to extract and transform crowdfunding source data.  Note, original source data was generously bestowed by their trusty leader, Alexandria Kalika, as prescribed by the GW Data Analytics Bootcamp curriculum. Here follows the list of the files included in this repository. This list serves as both table of contents as well as an outline of the group’s programmatic ETL processes.

 Jupyter Notebook program code for data extraction and transformation:

ETL_Mini_Project.ipynb

 Four CSV files composed of the ‘transformed’ data – the contents of which will ultimately become our Crowdfunding Database:
1) category.csv
2) subcategory.csv
3) campaign.csv
4) contacts.csv

  Repository subfolders and their contents:

ERD (2 files) --

crowdfunding_db_ERD.png

Crowdfunding_db_ERD.png shows the entity relationship diagram used to develop the crowdfunding database. Note, an entity relationship diagram (ERD) is an important piece of the overall data modeling.  It quite literally serves as a blueprint of the database architecture.  In other words, it provides a visual landscape of how data entities, and their respective entity types, relate to one another. We used the QuickDBD applications platform for our ERD construction.

crowdfunding_db_ERD_Schema.txt

The crowdfunding_db_ERD_Schema text file shows the table schema for each individual CSV file, specifying data types, primary/foreign keys and other constraints.

SQL (5 files) --

crowdfunding_db_schema.sql

The above sql file constitutes the actual code used to build our database table structures. The code shows a series of CREATE TABLE statements which define individual table columns and their respective datatypes, and constraints with primary & foreign key designations.   

pgAdmin4 (cute blue elephant head) screenshots:

1) Category_Screenshot.docx
2) Subcategory_Screenshot.docx
3) Campaign_Screenshot.docx
4) Contacts_Screenshot.docx

The above four screenshots serve to validate that the four database tables were populated with our skillfully transformed crowdfunding data :).

 Source_Data_(Excel) (2 files) --

And for further investigation, if your curiosity begs, I include the two Excel source files which mark the starting point of this journey (under subfolder Source_Data_(Excel)):
1) crowdfunding.xlsx
2) contracts.xlsx

It is from these two excel files that we extracted our initial data, and then began our ‘mad scientist’ transformation of it :o.
