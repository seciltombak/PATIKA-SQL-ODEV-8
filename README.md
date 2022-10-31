# PATIKA-SQL-ODEV-8
PATİKA LİNKİM = https://app.patika.dev/seciltombak
1.test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.  
2.Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.  
```
CREATE TABLE employee (
id INTEGER,
name VARCHAR(50) ,
birthday DATE,
email VARCHAR(100)
);
```

```
insert into employee (name , birthday, email) values ('Kathi', '1904-08-13', 'kjennens0@so-net.ne.jp');
insert into employee (name , birthday, email) values ('Stu', '1982-01-16', 'smolden1@blog.com');
insert into employee (name , birthday, email) values ('Aretha', '1979-08-05', 'amosedall2@de.vu');
insert into employee (name , birthday, email) values ('Reggie', '2009-11-03', 'rhissie3@wisc.edu');
insert into employee (name , birthday, email) values ('Dode', '1909-12-30', 'dbruhnsen4@bbb.org');
insert into employee (name , birthday, email) values ('Vachel', '1950-02-07', 'vardron5@last.fm');
insert into employee (name , birthday, email) values ('Butch', '1918-08-28', 'bhughman6@sourceforge.net');
insert into employee (name , birthday, email) values ('Yvette', '1934-04-12', 'yscay7@comsenz.com');
insert into employee (name , birthday, email) values ('Adriana', '1920-06-05', 'adolphin8@google.cn');
insert into employee (name , birthday, email) values ('Tomaso', null, null);
insert into employee (name , birthday, email) values ('Ashley', null, null);
insert into employee (name , birthday, email) values ('Berke', null, null);
insert into employee (name , birthday, email) values ('Pauly', '2019-03-01', 'pbrasenerc@reddit.com');
insert into employee (name , birthday, email) values ('Aldric', '1948-01-27', 'aolahyd@rediff.com');
insert into employee (name , birthday, email) values ('Elvera', '2019-10-09', 'etournere@fastcompany.com');
insert into employee (name , birthday, email) values ('Karylin', '1981-10-13', 'kpittendreighf@npr.org');
insert into employee (name , birthday, email) values ('Elfreda', '2016-07-24', 'egreenhamg@wired.com');
insert into employee (name , birthday, email) values ('Matty', '1991-04-22', 'meshelbyh@php.net');
insert into employee (name , birthday, email) values ('Byrom', '1959-01-22', 'bshovelli@aboutads.info');
insert into employee (name , birthday, email) values ('Tabby', '1903-12-19', 'tadlingtonj@youku.com');
insert into employee (name , birthday, email) values ('Chelsea', null, null);
insert into employee (name , birthday, email) values ('Dal', null, null);
insert into employee (name , birthday, email) values ('Neddy', null, null);
insert into employee (name , birthday, email) values ('Kacey', '2001-12-31', 'kmorenon@answers.com');
insert into employee (name , birthday, email) values ('Correy', '2010-10-11', 'cfarncombo@flickr.com');
insert into employee (name , birthday, email) values ('Milton', null, null);
insert into employee (name , birthday, email) values ('Cristian', '1931-08-26', 'cbunnq@jalbum.net');
insert into employee (name , birthday, email) values ('Parsifal', null, null);
insert into employee (name , birthday, email) values ('Magnum', '2011-10-01', 'msmoughtons@census.gov');
insert into employee (name , birthday, email) values ('Berk', '1996-04-03', 'bbraimet@hatena.ne.jp');
insert into employee (name , birthday, email) values ('Bianca', '1911-04-10', 'blefeveru@angelfire.com');
insert into employee (name , birthday, email) values ('Lolly', '1992-04-08', 'lhaslehurstv@washington.edu');
insert into employee (name , birthday, email) values ('Ameline', '1945-05-08', 'acapnorw@google.nl');
insert into employee (name , birthday, email) values ('Saxe', '1958-01-29', 'sorsx@bandcamp.com');
insert into employee (name , birthday, email) values ('Dian', null, null);
insert into employee (name , birthday, email) values ('Jon', '2016-04-24', 'jtuckleyz@psu.edu');
insert into employee (name , birthday, email) values ('Mick', '1901-12-16', 'mwalley10@weibo.com');
insert into employee (name , birthday, email) values ('Gertrudis', '2013-02-08', 'ghuguet11@techcrunch.com');
insert into employee (name , birthday, email) values ('Emmie', '1940-09-25', 'etrevena12@nasa.gov');
insert into employee (name , birthday, email) values ('Pablo', '1997-03-20', 'pslany13@sourceforge.net');
insert into employee (name , birthday, email) values ('Miles', '1932-01-27', 'mmaund14@google.com');
insert into employee (name , birthday, email) values ('Sonni', '1907-08-29', 'srattenbury15@edublogs.org');
insert into employee (name , birthday, email) values ('Beckie', '2007-06-08', 'baidler16@huffingtonpost.com');
insert into employee (name , birthday, email) values ('Hilliary', '1958-05-28', 'hbirrane17@delicious.com');
insert into employee (name , birthday, email) values ('Lalo', null, null);
insert into employee (name , birthday, email) values ('Otto', '1990-10-19', 'ohallward19@mail.ru');
insert into employee (name , birthday, email) values ('Tulley', '1955-04-17', 'tnorris1a@wufoo.com');
insert into employee (name , birthday, email) values ('Ailis', '1975-09-23', 'ahammelberg1b@surveymonkey.com');
insert into employee (name , birthday, email) values ('Hymie', '2015-12-16', 'hcockshutt1c@mysql.com');
insert into employee (name , birthday, email) values ('Ulric', '1942-05-16', 'uhandley1d@yelp.com');

```
3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.  
```
UPDATE employee
		 SET name = 'Ali ' ,
		 email ='Ali@gmail.com' ,
		 birthday ='1995-03-23'
		 WHERE id = 1 ;

UPDATE employee
		 SET name = 'Veli' ,
		 email ='Veli@gmail.com' ,
		 birthday ='1978-02-06'
		 WHERE id = 2 ;
UPDATE employee
		 SET name = 'Hüso  ' ,
		 email ='Hüso@gmail.com' ,
		 birthday ='1971-02-01'
		 WHERE id = 3 ;
UPDATE employee
		 SET name = 'Hatice ' ,
		 email ='Hatice@gmail.com' ,
		 birthday ='2000-03-05'
		 WHERE id = 4 ;
UPDATE employee
		 SET name = 'Netice ' ,
		 email ='Netice@gmail.com' ,
		 birthday ='1994-02-24'
		 WHERE id = 5 ;

```

4.Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.  
```
DELETE FROM employee
		WHERE id IN (5,7,9,11,13)
		RETURNING *;
```
