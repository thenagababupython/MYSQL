# MYSQL
MYSQL
===============================================================================================================
 
DJANGO WITH MYSQL CONNECTION (MYSQL COMMANDS DATABASE):
 ==========================================================================================================================================
 1.create datbase 'databasename';
 2.use 'databasename';
 3.show databases;
 4.show tables;
 5.select * from 'table name';
 6.truncate table 'tablename';
 7.drop database 'databasename'
  
   ====>verfiy connection with settings.py file database connection by using 'cursor()' function in python shell:
       ---------------------------------------------------------------------------------------------------------
       1.python manage.py shell
       2.from django.db import connection
       3.x=connection.cursor()
       
   ====>After migration file:
       ----------------------
       modelname-------->table name
       Field Name ------>coloum name
       Field Type------->data types
       
      1.sql migrate appname 0001-----sql code shows
      
