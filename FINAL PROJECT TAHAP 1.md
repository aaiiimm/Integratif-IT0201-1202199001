## **FINAL PROJECT**  

Tahap 1 Install Laravel

1. Sebelum install Laravel, hal pertama yang harus dilakukan adalah install Composer

   <img width="675" alt="1" src="https://user-images.githubusercontent.com/62064492/173063278-1af79ebd-a515-4478-aa22-b4c95220f6e4.PNG">

2. Setelah dilakukan install Composer, maka langkah selanjutnya yaitu masuk Command Prompt dengan cara klik Win+R lalu ketik cmd dan klik **OK**

   <img width="284" alt="2" src="https://user-images.githubusercontent.com/62064492/173063291-b4d4c998-67af-478b-b751-f328445bf0ee.PNG">

   

3. Sebelum melakukan instalasi Laravel, arahkan Command Prompt atau  terminal menuju direktori file server. Lokasi file server pada XAMPP  secara default berada pada direktori xampp/htdocs. Masukan perintah ini  pada jendela Command Prompt untuk masuk ke direktori htdocs.

   ```markdown
   cd \xampp\htdocs
   ```

   

   <img width="677" alt="7" src="https://user-images.githubusercontent.com/62064492/173063319-9e94c4d7-ba69-4865-8127-0f9f5a5dd45f.PNG">

   

4. Setelah itu, membuat request untuk mengambil (serta menginstall) file Laravel yang telah disediakan dalam repositori Github.

   ```markdown
   composer create-project --prefer-dist laravel/laravel nama_projectmu
   ```

   <img width="960" alt="3" src="https://user-images.githubusercontent.com/62064492/173063301-dbcd78c1-f32a-446f-8c94-21a9f23aec38.PNG">

   

   <img width="960" alt="4" src="https://user-images.githubusercontent.com/62064492/173063308-550fbc6b-f576-44ea-874b-9d4c39a768af.PNG">

   

5. Setelah proses download file Laravel selesai, nantinya akan ada folder  baru pada direktori file server dengan nama sesuai nama project yang  telah dibuat.

   ![8](https://user-images.githubusercontent.com/62064492/173063321-99a69495-2461-4f74-b299-9e0398d6dc2c.png)

   

6. Untuk memastikan bahwa Laravel sukses terinstall dan siap untuk  digunakan, arahkan Command Prompt atau Terminal menuju direktori yang  telah dibuat sebelumnya.

   ````markdown
   Php artisan serve
   ````

   <img width="960" alt="5" src="https://user-images.githubusercontent.com/62064492/173063310-3450564c-1fd8-4fae-9872-295efa51a918.PNG">

   

7. Apabila sudah muncul tulisan `Laravel development server started` pada Command Prompt atau Terminal, maka langkah selanjutnya yaitu  membuka link yang telah disediakan oleh Laravel.  Secara default, akan  diarahkan menuju alamat server, yaitu 127.0.0.1:8000. Nantinya, akan  muncul tampilan homepage dengan tulisan Laravel di bagian tengah seperti pada gambar di bawah ini

   <img width="959" alt="6" src="https://user-images.githubusercontent.com/62064492/173063316-4f6b8d84-1979-4f6f-a613-69980c889283.PNG">
