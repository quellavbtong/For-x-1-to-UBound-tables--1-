# For-x-1-to-UBound-tables--1-
For $x = 1 to UBound($tables)-1   ;Display Table Columns     _ArrayDisplay($tables[$x][1],"Table Name: " &amp; $tables[$x][0]) Next  ;Add Column to Table _AddColumn("TestTable","Field2","VARCHAR(10)")  ;Drop Column from Table _DropColumn("TestTable","Field2")  ;Drop Table _DropTable("TestTable")  ;Drop Database _DropDatabase()   ;Closes ADO Connection first if us
