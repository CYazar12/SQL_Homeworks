# SQL_Homeworks

# SQL Ödev 2 | BETWEEN ve IN

1-) film tablosunda bulunan tüm sütunlardaki verileri replacement cost değeri 12.99 dan büyük eşit ve 16.99 küçük olma koşuluyla sıralayınız ( BETWEEN - AND yapısını kullanınız.)

SELECT * FROM film 
WHERE replacement_cost BETWEEN 12.99 AND 16.99;

![image](https://github.com/CYazar12/SQL_Homeworks/assets/109551508/68c49b86-6138-4092-8616-609f7e085f0c)

2-) .actor tablosunda bulunan first_name ve last_name sütunlardaki verileri first_name 'Penelope' veya 'Nick' veya 'Ed' değerleri olması koşuluyla sıralayınız. ( IN operatörünü kullanınız.)


SELECT first_name, last_name FROM actor 
WHERE first_name IN ('Penelope', 'Nick', 'Ed');


![image](https://github.com/CYazar12/SQL_Homeworks/assets/109551508/f759d74c-4d1f-4754-9418-f42f25fd0a47)

3-) film tablosunda bulunan tüm sütunlardaki verileri rental_rate 0.99, 2.99, 4.99 VE replacement_cost 12.99, 15.99, 28.99 olma koşullarıyla sıralayınız. ( IN operatörünü kullanınız.)

SELECT * FROM film
WHERE rental_rate IN (0.99, 2.99, 4.99) AND replacement_cost IN (12.99, 15.99, 28.99);

![image](https://github.com/CYazar12/SQL_Homeworks/assets/109551508/d62364e7-dc7c-4eef-87cd-2be8c925f8ea)
