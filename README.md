# CommandPostgres


1.sudo apt install postgresql postgresql-contrib --> for install postgresql

2.sudo  psql --version --> for check version 

3.sudo -u postgres psql --> access the PostgreSQL shell

4.\q --> Exit out of the PostgreSQL prompt by typing

5.\l --> show all database 

6.\dt --> all table show 

7.\c database_name -->for use particular database 

8.\d table_name --> des table

9. create database database_name --> for creating database

10. drop databse database_name --> remove database

11. contstraint

    Not Null,Default,Unique,Check,Primary key, Foreign Key
   
     primary key -->when multiple columns are used as a primary key,they can calles composite key.
     Foreign key --> ensure referential integrity(accuray & integrity) of data
     
 12. copy data file to database
 
             \copy customer from 'Downloads/Data/copy.csv' Delimiter ',' csv header

