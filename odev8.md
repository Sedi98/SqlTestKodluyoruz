## test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

create table employee (
id integer primary key,
name varchar(50) not null,
	email varchar(100) not null,
	birthday date not null
);

## Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
ok
## Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.


update employee
set 
name='Maykl'
where id=2

update employee
set 
name='Maykl'
where id=7

update employee
set 
name='Maykl'
where id=9


update employee
set 
name='Maykl'
where id=14

update employee
set 
name='Maykl'
where id=17

## Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

delete from employee
where id<5
