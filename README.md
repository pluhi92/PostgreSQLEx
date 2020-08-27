Project of PostgreSQL-JAVA connection. This project shows how to edit a PostgreSQL database (using pgAdmin 4) using java methods. 
Important to download jdbc postgreSQL connector from: https://jdbc.postgresql.org/download.html

URL: "jdbc:postgresql://localhost:5432/postgres", 

USER: "postgres", 

PASSWORD: "........"

Example for creating a new table in pgAdmin: 

DROP TABLE IF EXISTS users;

CREATE TABLE users(id serial PRIMARY KEY, fname VARCHAR(255), lname VARCHAR(255), age integer);

INSERT INTO users(fname, lname, age) VALUES('Peter', 'Nagy', 19);
INSERT INTO users(fname, lname, age) VALUES('Bela', 'Toth', 29);
INSERT INTO users(fname, lname, age) VALUES('Cecilia', 'Varro', 28);
INSERT INTO users(fname, lname, age) VALUES('Sirena', 'Allah', 22);
