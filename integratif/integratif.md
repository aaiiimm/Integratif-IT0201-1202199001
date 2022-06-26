# TAHAP 2 - RSS #
---

• Mengubah DB_DATABASE di .env sesuai dengan nama database yang dibuat di phpmyadmin

![](ss/1.PNG)

![](ss/2.PNG)

• Buatlah 2 table rrs dan news dengan fitur migrations menggunakan syntax

```
php artisan make:migration create_rss_table

php artisan make:migration create_news_table
```



• Tambahkan kolom name dan url pada table rss


![](ss/3.PNG)
![](ss/4.PNG)

• Untuk menjalankan migrasi yang dibuat jalankan perintah diterminal , lalu cek database
php artisan migrate

![](ss/5.PNG)

• Buatlah koneksi model ke database dengan membuat seeder dan controller untuk tabel Rss dan News, dengan sytanx
```
    php artisan make:model Rss –seed -controller
```
![](ss/6.PNG)


• Edit file Rss.php, RssSeeder.php serta DatabaseSeeder.php 

![](ss/7.PNG)
![](ss/8.PNG)
![](ss/9.PNG)

•  Kemudian cek koneksi , dengan syntax



• Edit file News.php, NewsController.php, web.php, serta file migration News

![](ss/10.PNG)
![](ss/11.PNG)
![](ss/12.PNG)
![](ss/13.PNG)

• Cek dilokal host 

http://127.0.0.1:8000/aggregrate/1

http://127.0.0.1:8000/aggregrate/5

http://127.0.0.1:8000/aggregrate/6 

dan phpmyadmin

![](ss/14.PNG)

![](ss/15.PNG)

![](ss/16.PNG)

![](ss/17.PNG)

![](ss/18.PNG)




**Sakalangkong**

