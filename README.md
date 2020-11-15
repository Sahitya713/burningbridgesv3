## SQL database implementation

The sql database can be imported using the following steps:

1. Download final_sql_db.sql
2. Open Mysql workbench and click on server then Data Import
2. Select the import from Self-Contained File option and select file path of final_sql_db.sql
4. Select Start Import
5. Once imported successfully, make the covid_word schema teh default schema before running the queries found in final_sql_script.sql


## NoSQL database implementation

The mongoDB database can be imported using the following steps:

1. Download the following json files:
  1.owid2.json
  2.mobility_report.json
  3. measures.json
2. Open MongoDB Compass Community
3. Select Create Database and enter the following details:
  1. Database Name: covid_world
  2. Collection Name: owid2
4. click on the owid2 collection and then select add file followed by Import File.
5. Select the file path of the owid2.json file under Select File and select JSON. Click Import.
6. Once the collection is successfully loaded, click on Create Collection in the same database and input the collection name as "mobility_report".
7. Import the mobility_report.json file as explain above in the mobility_report collection.
8. Repeat the same for measures. Create a collection with the name "measures" and import measures.json in the collection

