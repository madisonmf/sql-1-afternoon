// Tables - Artist

INSERT INTO Artist
(Name)
VALUES 
('Bad Gyal'),
('Chance the Rapper');

-- SELECT * FROM Artist
-- ORDER BY Name DESC
-- LIMIT 10;

SELECT * FROM Artist
ORDER BY Name ASC
LIMIT 5;

SELECT * FROM Artist
WHERE Name LIKE 'Black%';

SELECT * FROM Artist
WHERE Name LIKE '%black%';