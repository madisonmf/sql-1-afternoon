// Table - People

DROP TABLE IF EXISTS person;

CREATE TABLE person (
  id INTEGER PRIMARY KEY AUTOINCREMENT,
  name VARCHAR,
  age INTEGER,
  height INTEGER,
  city VARCHAR,
  favorite_color VARCHAR
);

INSERT INTO person
(name, age, height, city, favorite_color)
VALUES
('LT', 27, 65, 'Richmond', 'red'),
('Omar', 30, 70, 'San Diego', 'blue'),
('McAuley', 27, 72, 'Davis', 'yellow'),
('Robyn', 24, 64, 'Boston', 'pink'),
('Mads', 30, 52, 'Lake Forest', 'orange');

-- SELECT * FROM person
-- ORDER BY height DESC;

-- SELECT * FROM person
-- ORDER BY height ASC;

-- SELECT * FROM person
-- ORDER BY age DESC;

-- SELECT * FROM person
-- WHERE age > 20;

-- SELECT * FROM person
-- WHERE age = 18;

-- SELECT * FROM person
-- WHERE age < 20 AND age > 30;

-- SELECT * FROM person
-- WHERE age <> 27;

-- SELECT * FROM person
-- WHERE age != 27;

-- SELECT * FROM person
-- WHERE favorite_color != 'red';

-- SELECT * FROM person
-- WHERE favorite_color != 'red' AND favorite_color <> 'blue';

-- SELECT * FROM person
-- WHERE favorite_color = 'orange' OR favorite_color = 'green';

-- SELECT * FROM person
-- WHERE favorite_color IN ('orange', 'green', 'blue');

-- SELECT * FROM person
-- WHERE favorite_color IN ('yellow', 'purple');