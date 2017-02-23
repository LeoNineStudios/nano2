# FOR REFERENCE ONLY

Tournament Database
Author: Adam Leonard
4/17/15

In any future development, please use the following database connection.
Database connection: psycopg2.connect("dbname=tournament")

This set of code is used to create tables in a database called tournament in PSQL. This uses Python classes to test and check sql functionality.

Navigate to the tournament directory:
"cd /vagrant/tournament"

To run tests, simply create a psql database via;
"create database tournament"

To connect to the database;
"\c tournament"

After entering psql (type "psql"), import the database.
"\i tournament.sql"

Then run;
"python tournament_test.py"

All tests should pass.


###Please note, there are planned improvements to make this usable across multiple tournaments. Because of this there are two tables (tournament and round) that are defined but not used.
