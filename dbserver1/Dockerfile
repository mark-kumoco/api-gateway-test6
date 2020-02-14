# docker build -t dbimg .
# docker run --name dbcnt -d -p 5432:5432 dbimg
FROM postgres
#$ REMOVE '#$' chars to create and populate database - should be automated.
## Login to container
#$ su postgres
#$ psql
#$ create database test1;
#$ \c test1

#$ CREATE TABLE account(
#$   user_id serial PRIMARY KEY,
#$   username VARCHAR (50) UNIQUE NOT NULL,
#$   password VARCHAR (50) NOT NULL,
#$   email VARCHAR (355) UNIQUE NOT NULL,
#$   created_on TIMESTAMP NOT NULL
#$);

#$ \dt

#$ INSERT INTO account VALUES (1, 'lum', 'hellopw', 'lum@here.com', '2001-09-28 01:00:00');
#$ INSERT INTO account VALUES (2, 'gid', 'byepw', 'gid@here.com', '2020-02-14 08:55:08');

#$ SELECT * FROM account;

#$ To test postgres from local (or remote) machine with default install (no security):
#$ psql.exe -h localhost -p 5432 -U postgres