# homework7
Ödev 7 group by &amp; having 

--- SORU 1
SELECT rating, COUNT(*) from film
GROUP BY rating

--SORU 2
SELECT replacement_cost, COUNT(*) FROM film
GROUP BY replacement_cost
HAVING COUNT(*)>50

-- SORU 3
SELECT store_id, COUNT(*) FROM customer
GROUP BY store_id

-- SORU 4
SELECT country_id, COUNT(*) FROM city
GROUP BY country_id
ORDER BY country_id DESC
LIMIT 1

--

