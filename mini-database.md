## Mini Database

### Description

Your task is to create a small database. It is based on a single plain text file which should look like this:

    ===
    Table name 1
    ===
    Col1|Col2|Col3
    ---
    Row1|Row1|Row1
    ---
    Row2|Row2|Row2
    ===
    Table name 2
    ===
    Col1
    ---
    Row1

Table names are enclosed between two "===" lines. The next line contains a list of column names separated by pipe charachter "|". Then go any amount of values rows. Rows are separated with a '---' line, and values are separated just like column names, by a pipe charachter "|".
File may contain any amount of tables, table may contain any amount of rows and columns. All columns are text columns.

You should be able to do following actions:
 - Open an existing database file
 - Save modified database
 - List tables in a database
 - Create new tables
 - List rows in a table
 - Create new rows
