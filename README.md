# psql-cheat-sheet

to start the postgres server
  - $ postgres -D /usr/local/var/postgres

to start the psql cli
  - $ psql

Input “help” to get help

Useful sql commands (remember those semi-colons;):

(NOTE: All of the sql commands can be lower case)

View current database:
  - # SELECT CURRENT_DATABASE();

List all databases:
  - # \l

Create a new database:
  - # CREATE DATABASE MYDB;

Use a database:
  - # \connect MYDB;

Run database schema:
  - # \i filepath.txt;

List tables and sequences in your current db:
  - # \d

Delete database:
  - # DROP DATABASE MYDB

Quit the cli:
  - # \q
