# HW-4

### 1- film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız.

- Select Distinct replacement_cost From film;

### 2- film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?

- Select Count(Distinct replacement_cost) From film;

### 3- film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?

- Select Count(*) From film Where title Like 'T%' And rating = 'G';

### 4- country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?

- Select Count(*) From country Where country Like '_____';

### 5- city tablosundaki şehir isimlerinin kaç tanesi 'R' veya r karakteri ile biter?

- Select Count(*) From city Where city Ilike '%r';

