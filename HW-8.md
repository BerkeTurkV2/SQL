# HW-8

### 1- test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

- Create Table employee (
	id Serial Primary Key,
	name Varchar(50) Not Null,
	birthday Date,
	email Varchar(100)
);

### 2- Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

- insert into employee (name, birthday, email) values ('Gustavus Jarrel', '1987-12-22', 'gjarrel0@shinystat.com');
insert into employee (name, birthday, email) values ('Sofie Bartolomucci', '1978-04-19', 'sbartolomucci1@github.com');
insert into employee (name, birthday, email) values ('Angie Josey', '1950-06-25', 'ajosey2@acquirethisname.com');
insert into employee (name, birthday, email) values ('Leodora Pavinese', '1994-05-29', 'lpavinese3@mapy.cz');
insert into employee (name, birthday, email) values ('Whitney Everson', '2012-11-22', 'weverson4@boston.com');
....
    50 Adet veri eklendi.

### 3- Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

- Update employee 
Set name = 'Berke Turk',
	birthday = '1998-07-28',
	email = 'berketurk035@gmail.com'
Where id = 1;

....
    5 Adet update işlemi yapıldı.

### 4- Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

- Delete From employee
Where id = 7;   

....
    5 Adet delete işlemi yapıldı.
