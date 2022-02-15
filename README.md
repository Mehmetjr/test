# test
test
test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
Create Table employee(id INTEGER,

name VARCHAR(50),

birthday DATE,

email VARCHAR(100));






Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

Delete from employee where id=5
Delete from employee where email='ekirwin14@admin.ch'
Delete from employee where name='Nolie' aynı isimde birden fazla kişi varsa hepsini siler
Delete from employee where birthday='2021-09-26'
Delete from employee where name='Cordey' and birthday='2021-05-29'
