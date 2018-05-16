// Tables - Invoice

SELECT count(*) FROM Invoice
WHERE BillingCountry = 'USA';

SELECT Max(Total) FROM Invoice;

SELECT Min(Total) FROM Invoice;

SELECT * FROM Invoice
WHERE Total > 5;

SELECT count(*) FROM Invoice
WHERE Total < 5;

SELECT count(*) FROM Invoice
WHERE BillingState IN ('CA', 'TX', 'AZ');

SELECT avg(Total) FROM Invoice;

SELECT sum(Total) FROM Invoice;