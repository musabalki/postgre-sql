# postgre-sql
### Bağlan
psql –d postgres –U kullaniciAdi
psql –d veritabaniAdi –U kullaniciAdi

### Kullanıcı Oluştur
CREATE ROLE kullaniciAdi WITH LOGIN PASSWORD ‘sifre’;

### Kullanıcı Listele
\du

### Kullanıcıya Yetki Verme
ALTER ROLE kullaniciAdi CREATEDB;

### Veritabanı Listeleme
\list

### Çık
\q

### Veritabanı Oluştur
CREATE DATABASE veritabaniAdi

### Veritabanına Bağlan
\c veritabaniAdi
