![mysql]https://tse2.mm.bing.net/th?id=OIP.zeQ4kZkfdqXn3xesbTc6_wHaFI&pid=Api&P=0

# SQL QUERY

 ### Melihat database
```bash 
create database nama_database;
```
 ### Membuat database
```bash 
show databases;
```
 ### Masuk ke salah satu databases
```bash 
use nama_database;
```
 ### Membuat tabel
```bash 
create table nama_tabel(isi structure dari databasenya misalnya id int primary key auto_increment, nama varchar(100), alamat dan ssampai selesai );
```
 ### Melihat tabel
```bash 
show tables;
```
 ### Melihat structure tabel
```bash 
describe nama_tabel
```
 ### Menambahkan data/ insert data
 + Cara Pertama
```bash 
insert into nama_tabel(nama, alamat, nip, nohp) values('Sena pernata', 'Br. Dinas Bias', 989878764654, 9898776765575);
```
atau

+ Cara kedua
```bash
insert into nama_tabel values('', 'Sena Pernata', 'abang', 978967654644, 9978787567568);
```

Silahkan ubruk pilih salah satu cara diatas dan cara penggunaannya berbeda ya lihat pada cara kedua itu untuk id diberi string kosong tapi yang cara pertama itu tidak isi id karena id itu akan dibuatkan secara otomatis oleh mysqlnya. Kalian bisa pilih salah satu dari kedua cara itu gunakan juga caranya sesuai dengan yang diatas.


 ### Melihat data yang baru di insert
```bash 
SELECT * FROM nama_tabel
```
 ### Melihat data sesuai dengan filter yang diberi
```bash 
select nip from nama_tabel;
```

### Melihat data dengan filter untuk mencari data lebih dari satu
```bash
select id, nama from nama_tabel;
```

### Melihat data atau memfilter dengan sebuah id atau pun yang lain untuk mencari data seseorang melalui id nya itu
```bash
select * from nama_tabel where id=1;
```

### Update data yang ada di database
```bash
update nama_tabel set nama='Pernata', alamat='banjar sadimara' where id=1;
```
catatan : jika yang tidak mau di update jangan di tulis.


### Delete data yang ada
```bash
delete from nama_tabel where id=1;
```

### Menghapus tabel database
```bash
drop table nama_tabel;
```

### Menghapus Database
```bash
drop database nama_database;
```


