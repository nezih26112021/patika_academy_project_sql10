# patika_academy_project_sql10
query scenarios

Perform the following query scenarios on the "dvdrental" sample database.

1. Write the LEFT JOIN query where we can see the city and country names in the city table and the country table together:

SELECT city,country FROM city

LEFT JOIN country ON city.country_id=country.country_id;

2. Write the RIGHT JOIN query where we can see the names of "payment_id" in the customer table and the payment table and "first_name and last_name" in the customer table together:

SELECT first_name,last_name,payment_id FROM customer

RIGHT JOIN payment ON customer.customer_id=payment.customer_id;

3. Write the FULL JOIN query where we can see the names of "rental_id" in the customer table and the rental table, and the names "first_name" and "last_name" in the customer table together:

SELECT first_name,last_name,rental_id FROM customer

FULL JOIN rental ON customer.customer_id=rental.customer_id;
