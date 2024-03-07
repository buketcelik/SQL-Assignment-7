# SQL-Assignment-7
1.	SELECT rating FROM film 
GROUP BY rating;

2.	SELECT replacement_cost, COUNT(*) FROM film
GROUP BY replacement_cost
HAVING COUNT(*) > 50;

3.	SELECT store_id, COUNT(*) FROM customer
GROUP BY store_id;

4.	SELECT country_id, city FROM city
GROUP BY country_id, city
ORDER BY country_id DESC 
LIMIT 1;
