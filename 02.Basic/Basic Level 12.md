#### Basic Level 12 - High level SQL injection

You can try SQLi with the url parameter "id".  
This paper help me a lot: <http://www.theprohack.com/2010/04/sql-injection-learn-to-attack.html>  
Use union select, and then try it with information_schema. 
Notice that "where" clause seems not to work.
A very strange thing is that you can get table name and column name from a same table.
And there is only one number you can use.
