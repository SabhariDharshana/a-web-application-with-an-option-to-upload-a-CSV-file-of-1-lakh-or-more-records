# a-web-application-with-an-option-to-upload-a-CSV-file-of-1-lakh-or-more-records
A web application with an option to upload a CSV file of 1 lakh or more records, where the application should read the records, process it, and push to the database table. 
The CSV file have a header row that denotes the database table column names and rows which represent the values of the database table. 
After the upload of the CSV file, only the database table is created dynamically based on the header names of the CSV file and the insert of row values should be carried out later.
In case if any header named as “password”, the value will be encrypted dynamically and saved in the database.
