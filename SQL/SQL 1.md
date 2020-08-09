# SQL COMMANDS/QUERIES:
## SQL stands for Structured query language.

#### Note: To end the commands use (;) at last.

#### 1. SELECT columns(1,2,3).
#### 2.FROM tableName
#### 3.SELECT *    => to select all columns.

## To select all rows of a column:

#### SELECT *
#### FROM tableName
#### WHERE colName = "desire";

## DATA TYPE
#### number -10
#### text - john
#### date - 2018-8-18
#### Note: date is written between "2018-8-18" as string


#### ex: We compare or put condition using WHERE to rows data by
####     WHERE colName >= "2018-8-8";


## LIKE OPERATOR
### If we want any particular data from table:
#### SELECT *
#### FROM tabName
#### WHERE colName LIKE "%happy%";
#### Here happy word is been searched and Strings containing happy.

## Putting % at last of String means to check whether string is starting from that word.
#### ex: WHERE colName LIKE "%happy";
#### =>    ishappy is searched.

#### ex:WHERE colName LIKE "happy%";
#### => happybd is searched.

## NOT operator
#### To get rows which dont statisfy condition.
#### ex: WHERE  NOT colName >10;              (not morethan 10)
#### ex: WHERE NOT colName = "happy";     (not happy string)
#### ex: WHERE NOT colName LIKE "%happy%";    (not string which contains happy)

## IS NULL
#### To get NULL rows in colName.
#### ex: WHERE colName IS NULL;
#### ex: WHERE colName IS NOT NULL;

## CONDITIONS (AND ,OR)
#### ex: WHERE colName = "happy"
   ####  AND colName2 = "birthday";
#### If both are true then it will show row which contains happy and birthday both.

## ORDER BY:
#### ex: ORDERBY colName1 colName2;

#### ASC - ascending
#### DESC - descending

#### ex: ORDERBY colName DSEC;
#### ex: FROM colName = "cool"
   #### ORDERBY colName ASC;
     
## LIMIT  no_of_rows ;
#### ex: LIMIT 2 
#### it limits the printing of 2 rows.

*******************************************************************************************************************************************************************************
