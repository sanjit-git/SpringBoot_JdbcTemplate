# SpringBoot_JdbcTemplate
Springboot api using multiple database and jdbcTemplate, i have used mysql and postgres database
url for execution
-------------------------
http://localhost:8080/api/data/matchingData

postgres query for create table address and insert Query data
-------------------------------------------------------------
CREATE TABLE address (
    id SERIAL PRIMARY KEY,
    city TEXT NOT NULL
);

INSERT INTO address (id, city) VALUES 
    (1, 'New York'),
    (2, 'London'),
    (3, 'Paris');

mysql query for create table employee and insert Query data  
----------------------------------------------------------
CREATE TABLE employees (
    id INT PRIMARY KEY,
    name VARCHAR(50),
    place VARCHAR(50)
);
INSERT INTO employees (name, place) VALUES 
    (1,'Alice', 'New York'),
    (5,'Bob', 'London'),
    (3,'Charlie', 'Paris');

