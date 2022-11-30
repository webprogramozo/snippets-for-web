# Snippets for web

:tada: A collection of self-contained scripts in a world where dependencies mean everything. :tada:

## MySQL

:memo: [mysql/copy-structure-with-auto-increment.sql](mysql/copy-structure-with-auto-increment.sql)
> Copy table structure keeping the value of auto_increment

With this script, you can copy the structure of the table specified in the parameter to another new table with the auto increment value. The script uses prepared statements to use the source and target tables specified in the parameter. The script uses the current database at runtime. This can be useful when creating backups.
