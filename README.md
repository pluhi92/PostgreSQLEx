Project of PostgreSQL-JAVA connection with JFrame. This application shows how can you easy edit a PostgreSQL database (using pgAdmin 4) using java methods. 
Download **jdbc postgreSQL connector** from: https://jdbc.postgresql.org/download.html

URL: "jdbc:postgresql://localhost:5432/postgres", 

USER: "postgres", 

PASSWORD: "........"

Example for creating a new table in pgAdmin: 


DROP TABLE IF EXISTS users;

CREATE TABLE users(id serial PRIMARY KEY, fname VARCHAR(255), lname VARCHAR(255), nationality VARCHAR(255), age integer);


INSERT INTO users(fname, lname, nationality, age) VALUES('Peter', 'Nagy', 'Hungarian', 19);

INSERT INTO users(fname, lname, nationality, age) VALUES('Frantisek', 'Studeny', 'Slovak', 29);

INSERT INTO users(fname, lname, nationality, age) VALUES('Tiffany', 'Bullock', 'American', 28);

INSERT INTO users(fname, lname, nationality, age) VALUES('Sirena', 'Abdul', 'Turkish', 22);
