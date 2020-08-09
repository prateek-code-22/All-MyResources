# SQL COMMANDS/QUERIES:

## DISTINCT - To exclude the duplicate column from table.
#### ex: SELECT DISTINCT (colName)
####     FROM tabName;

## ARTHMATIC operators

#### SELECT colName * 1.02
#### FROM tablName;

## SUM of colName
#### ex: SELECT SUM(colName)
####     FROM tabName;

## Average of colName
#### ex: SELECT AVG(colName)
####     FROM tabName;


## COUNT no.of rows
#### ex: COUNT (colName)
#### =>  To count all use: COUNT(*)

## MAX max. value in that column.
#### ex: MAX(colName)

## MIN min. value in that column.
#### ex: MIN (colName)


## GROUP BY 
#### syntax: GROUP BY(colName)

#### ex: SELECT SUM(colName),colName2
####     FROM table
####     GROUP BY colName2;
      

## WORKFLOW:

#### search  =>   WHERE
#### grouping=>   GROUP BY
#### function=>   COUNT,MAX,MIN,AVG
#### having =>     HAVING
  

## HAVING
#### searches for groups created by GROUP BY.
#### Note: WHERE searches for whole table before grouping.


## AS LABEL

#### It is used to give new names to colName int table.
#### Syntax: colName AS newName;
#### ex: john AS jones;


## TABLES:
#### Primary Key => id or serial order (atleast one),slows the insertion process.
#### Foreign Key => not unique.

## JOIN Tables
#### ex: SELECT *
   ####   FROM tableA
   ####   JOIN tableB
   ####   ON condition

#### ON condition => ON tableA.colName1 = tableB.colName2
####     		  FOREIGN KEY   =  PRIMARY KEY

####     => to select colName from tableA
####     => SELECT tableA.colName1 , tableB.colName2
    
    
## Including NULL rows
#### JOIN will not include NULL rows and do not display it.
#### LEFT JOIN shows NULL ROWS.


## INSERT 
#### To insert a new record or row into table.
#### Syntax: INSERT INTO  tablName(col1,col2,col3)
####         VALUES(4,"sql","java");
#### Note: col1 can be excluded bcz it is auto correction(id no. 1,2,3,...).


## UPDATE
#### To update the row data.
#### Syntax: UPDATE tabName
   ####      SET col1 = "food" , col2="water"
   ####      WHERE id = 6;

#### Note: 1. If we dont give WHERE then it will update whole rows data.
   ####    2. Never forget to use SELECT before UPDATE.

## DELETE
#### To delete the useless data.
#### Syntax: DELETE FROM tabName
   ####    : WHERE id = 5;
#### Note: if we dont give WHERE then it will delete whole data.

## DROP
#### To delete table.
#### Syntax : drop table TableName


## Created by Prateek.
**********************************************************************************************************************************************************************
