# patika_sql_odev8

CREATE TABLE employee (
	id INTEGER,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);
insert into employee (name, birthday, email) values ('Terrance', null, 'twinkworth0@arstechnica.com');
insert into employee (name, birthday, email) values ('Rice', '1993-12-20', 'rtraylen1@addthis.com');
insert into employee (name, birthday, email) values ('Sharl', '1947-10-06', 'sglasgow2@dyndns.org');
insert into employee (name, birthday, email) values ('Ryann', null, 'rbalaisot3@delicious.com');
insert into employee (name, birthday, email) values ('Winnah', '1963-04-09', 'wblodget4@paypal.com');
insert into employee (name, birthday, email) values ('Felita', '1973-12-09', 'fninnotti5@cnn.com');
insert into employee (name, birthday, email) values ('Susette', null, 'sharford6@elpais.com');
insert into employee (name, birthday, email) values ('Jaynell', '1995-11-21', 'jyaus7@google.ca');
insert into employee (name, birthday, email) values ('Alfy', '1996-09-06', 'agolding8@utexas.edu');
insert into employee (name, birthday, email) values ('Helsa', '1956-12-23', 'hburlay9@opera.com');
insert into employee (name, birthday, email) values ('Tibold', '1905-12-09', 'tmacdonalda@xinhuanet.com');
insert into employee (name, birthday, email) values ('Ashia', '1975-08-13', 'alieb@who.int');
insert into employee (name, birthday, email) values ('Alleen', '1928-01-14', 'aodonoghuec@freewebs.com');
insert into employee (name, birthday, email) values ('Arabele', null, null);
insert into employee (name, birthday, email) values ('Frasier', '2001-06-06', 'ffabrie@businesswire.com');
insert into employee (name, birthday, email) values ('Jill', null, 'jbosdenf@vistaprint.com');
insert into employee (name, birthday, email) values ('Kingston', null, 'krawlingsg@jugem.jp');
insert into employee (name, birthday, email) values ('Munmro', '1956-04-06', 'mrobbinsh@php.net');
insert into employee (name, birthday, email) values ('Marianne', '1932-07-18', 'mochterlonyi@imageshack.us');
insert into employee (name, birthday, email) values ('Calley', '2011-05-04', null);
insert into employee (name, birthday, email) values ('Marmaduke', '1931-10-11', 'motuohyk@mtv.com');
insert into employee (name, birthday, email) values ('Cort', '1907-12-11', 'cbellhangerl@buzzfeed.com');
insert into employee (name, birthday, email) values ('Brien', '1972-02-01', 'bwilborm@seesaa.net');
insert into employee (name, birthday, email) values ('Shanda', '1994-12-27', 'sdominikn@imageshack.us');
insert into employee (name, birthday, email) values ('Savina', '1966-05-24', 'sgremaneo@i2i.jp');
insert into employee (name, birthday, email) values ('Freeland', '1984-12-01', null);
insert into employee (name, birthday, email) values ('Duff', '1970-06-20', 'dparlottq@163.com');
insert into employee (name, birthday, email) values ('Cassandra', '1954-03-22', 'ckellegherr@yellowpages.com');
insert into employee (name, birthday, email) values ('Marrissa', '1929-03-24', 'mbaystons@washingtonpost.com');
insert into employee (name, birthday, email) values ('Marleen', '1916-10-12', 'mbloggt@people.com.cn');
insert into employee (name, birthday, email) values ('Daven', '1928-12-01', 'dcrimesu@deliciousdays.com');
insert into employee (name, birthday, email) values ('Camille', '1945-01-11', 'cguitonv@prlog.org');
insert into employee (name, birthday, email) values ('Dallon', '1996-02-04', 'dericssonw@youku.com');
insert into employee (name, birthday, email) values ('Terri-jo', '2015-05-21', 'tdickersonx@bloglovin.com');
insert into employee (name, birthday, email) values ('Tann', '1904-04-05', 'toaklandy@last.fm');
insert into employee (name, birthday, email) values ('Morly', '1938-04-06', 'msoignez@virginia.edu');
insert into employee (name, birthday, email) values ('Austina', '1917-11-07', 'aauden10@spotify.com');
insert into employee (name, birthday, email) values ('Tom', null, 'tteek11@ustream.tv');
insert into employee (name, birthday, email) values ('Grace', '2019-10-21', null);
insert into employee (name, birthday, email) values ('Dorelia', '1940-04-08', null);
insert into employee (name, birthday, email) values ('Win', '1936-01-05', 'wcasin14@bbb.org');
insert into employee (name, birthday, email) values ('Livvyy', '1947-09-24', 'lsoares15@quantcast.com');
insert into employee (name, birthday, email) values ('Constantine', '1935-08-06', 'clubman16@latimes.com');
insert into employee (name, birthday, email) values ('Gwyneth', '1916-12-06', 'grozalski17@youtube.com');
insert into employee (name, birthday, email) values ('Eli', null, 'etomisch18@msu.edu');
insert into employee (name, birthday, email) values ('Boot', '1967-01-22', 'bbushel19@joomla.org');
insert into employee (name, birthday, email) values ('Archambault', null, 'adahmel1a@youtu.be');
insert into employee (name, birthday, email) values ('Elka', '2018-08-12', 'eleeves1b@google.es');
insert into employee (name, birthday, email) values ('Sherline', '2016-11-28', 'sperrott1c@sciencedaily.com');
insert into employee (name, birthday, email) values ('Cos', '1957-06-28', 'csherlock1d@theguardian.com');
UPDATE employee
SET name = 'irem',
	birthday = '1998-10-02',
	email = 'iremozsevim@gmail.com'
WHERE name LIKE 'T%'
RETURNING *;
UPDATE employee
SET name = 'irem',
	birthday = '1998-10-02',
	email = 'iremozsevim@gmail.com'
WHERE id BETWEEN 20 AND 25
RETURNING *;
DELETE FROM employee
WHERE id BETWEEN 20 AND 25
RETURNING *;
