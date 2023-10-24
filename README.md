# SQL7
ödev



SELECT rating,COUNT(*) AS film_sayisi 
FROM film 
GROUP BY rating 
ORDER BY rating;

SELECT replacement_cost,COUNT(*) AS film_sayisi
FROM film 
GROUP BY replacement_cost
HAVING COUNT(*) >50 
ORDER BY film_sayisi DESC ;

SELECT country_id,COUNT(*) AS sehir_sayisi 
FROM city 
GROUP BY country_id
ORDER BY sehir_sayisi DESC 
LIMIT 1;


