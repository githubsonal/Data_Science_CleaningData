# Data_Science_CleaningData
Process of cleaning dataset

Problem Statement : This dataset contains information about books from British Library. It has information about published books such as Date,place of publication , author. There are many inconsistancies in data so we need to clean it properly.

Files - 
Dataset : BL-Flickr-Images-Book.csv
Code File : BooksInformation_DataCleaning

- To clean data we checked for missing values in columns , we checked how much percentage is of missing values.
- Date fileds had extra date and other values so we removed extra text and dates which were inconsistent we replaced them with numpys NAN value
- To clean place of publication we used numpy's where condition to get proper place name and to get clean text.

