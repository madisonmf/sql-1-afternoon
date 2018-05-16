// Table - Orders

DROP TABLE IF EXISTS orders;

CREATE TABLE orders (
person_id INTEGER,
product_name TEXT,
product_price DECIMAL,
quantity INTEGER
);

INSERT INTO orders 
(person_id, product_name, product_price, quantity)
VALUES
(1, 'lipstick', 15.95, 2),
(2, 'hairspray', 20, 1),
(3, 'lipstick', 15.95, 5),
(1, 'mascara', 21.99, 50),
(2, 'eyeshadow', 14, 5);


SELECT * FROM orders;

SELECT SUM(quantity) FROM orders;

SELECT SUM(product_price * quantity) FROM orders;

SELECT SUM(product_price * quantity) FROM orders
WHERE person_id = 1;