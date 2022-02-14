1)  SELECT * FROM city
JOIN country
ON city.country_id= country.country_id

2)  select py.payment_id, cr.first_name, cr.last_name from customer cr
 join payment py on cr.customer_id = py.customer_id
 
 
3)  select rn.rental_id, cr.first_name, cr.last_name from customer cr
 join rental rn on cr.customer_id = rn.customer_id