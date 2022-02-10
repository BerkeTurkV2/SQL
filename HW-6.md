# HW-6

### 1- film tablosunda bulunan rental_rate sütunundaki değerlerin ortalaması nedir?

- Select Round(Avg(rental_rate),3) From film;

### 2- film tablosunda bulunan filmlerden kaç tanesi 'C' karakteri ile başlar?

- Select Count(*) From film Where title Like 'C%';

### 3- film tablosunda bulunan filmlerden rental_rate değeri 0.99 a eşit olan en uzun (length) film kaç dakikadır?

- Select Max(length) From film Where rental_rate = 0.99;

### 4- film tablosunda bulunan filmlerin uzunluğu 150 dakikadan büyük olanlarına ait kaç farklı replacement_cost değeri vardır?

- Select Count(Distinct replacement_cost) From film Where length > 150;

