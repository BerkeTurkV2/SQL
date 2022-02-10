# HW-5

### 1- film tablosunda bulunan ve film ismi (title) 'n' karakteri ile biten en uzun (length) 5 filmi sıralayınız.

- Select title, length From film Where title Like '%n' Order By length Desc Limit 5;

### 2- film tablosunda bulunan ve film ismi (title) 'n' karakteri ile biten en kısa (length) ikinci(6,7,8,9,10) 5 filmi(6,7,8,9,10) sıralayınız.

- Select title, length From film Where title Like '%n' Order By length Asc Offset 5 Limit 5;

### 3- customer tablosunda bulunan last_name sütununa göre azalan yapılan sıralamada store_id 1 olmak koşuluyla ilk 4 veriyi sıralayınız.

- Select * From customer Where store_id = 1 Order By last_name Desc Limit 4;

