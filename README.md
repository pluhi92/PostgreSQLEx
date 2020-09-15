Project of PostgreSQL-JAVA connection. This project shows how to edit a PostgreSQL database (using pgAdmin 4) using java methods. 
Important to download jdbc postgreSQL connector from: https://jdbc.postgresql.org/download.html

URL: "jdbc:postgresql://localhost:5432/postgres", 

USER: "postgres", 

PASSWORD: "........"

Example for creating a new table in pgAdmin: 


DROP TABLE IF EXISTS users;

CREATE TABLE users(id serial PRIMARY KEY, fname VARCHAR(255), lname VARCHAR(255), nationality VARCHAR(255), age integer);


INSERT INTO users(fname, lname, nationality, age) VALUES('Peter', 'Nagy', 'Hungarian', 19);

INSERT INTO users(fname, lname, nationality, age) VALUES('Bela', 'Toth', 'Slovak', 29);

INSERT INTO users(fname, lname, nationality, age) VALUES('Cecilia', 'Varro', 'American', 28);

INSERT INTO users(fname, lname, nationality, age) VALUES('Sirena', 'Allah', 'Turkish', 22);
