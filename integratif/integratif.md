# TAHAP 2 - RSS #
---

• Mengubah DB_DATABASE di .env sesuai dengan nama database yang dibuat di phpmyadmin

![](ss/1.png)

![](ss/2.png)

• Buatlah 2 table rrs dan news dengan fitur migrations menggunakan syntax

```
php artisan make:migration create_rss_table

php artisan make:migration create_news_table
```



• Tambahkan kolom name dan url pada table rss


![](ss/3.png)
![](ss/4.png)

• Untuk menjalankan migrasi yang dibuat jalankan perintah diterminal , lalu cek database
php artisan migrate

![](ss/5.png)

• Buatlah koneksi model ke database dengan membuat seeder dan controller untuk tabel Rss dan News, dengan sytanx
```
    php artisan make:model Rss –seed -controller
```
![](ss/6.png)


• Edit file Rss.php, RssSeeder.php serta DatabaseSeeder.php 

![](ss/7.png)
![](ss/8.png)
![](ss/9.png)

•  Kemudian cek koneksi , dengan syntax



• Edit file News.php, NewsController.php, web.php, serta file migration News

![](ss/10.png)
![](ss/11.png)
![](ss/12.png)
![](ss/13.png)

• Cek dilokal host 

http://127.0.0.1:8000/aggregrate/1

http://127.0.0.1:8000/aggregrate/5

http://127.0.0.1:8000/aggregrate/6 

dan phpmyadmin

![](ss/14.png)

![](ss/15.png)

![](ss/16.png)

![](ss/17.png)

![](ss/18.png)




**Sakalangkong**

