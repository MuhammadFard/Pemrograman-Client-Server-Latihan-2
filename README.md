# Pemrograman-Client-Server-Latihan-2
## Langkah - Langkah untuk membuat latihan 2
1. Untuk langkah pertama, kita perlu masuk ke link start.spring.io untuk mendownload file spring. Disini untuk file nya harus kita sesuaikan yang sudah terinstall di laptop / pc anda, yang saya gunakan :

	-> project : maven project, language : java, spring boot : 2.7.4
  -> project metadata
      group : com.farid
      artifact : latihan-service
      packaging : java
      java : 17
      untuk dependencies kita hanya menggunakan spring web
  
2. Setelah itu kita generate
3. Untuk file yang di generate tadi itu bisa kita pindahkan sesuai dengan kemauan kita sendiri, misalkan tadi letaknya didownload bisa kita pindahkan di D:\Kuliah Parid\Semester 3\Pemrograman Client Server 2\latihan-service\latihan2-service ( ini contoh punya saya ) .
3. Setelah memindahkan file ditempat yang kita inginkan kita bisa ekstrak file tersebut.
4. Lalu buka apache netbeans 13 ( karna saya punya yang 3 dan jdk 17 seperti yang sudah didownload/generate pada start.spring.io
5. Lalu import file tadi, kemudian build with dependencies dan tunggu beberapa saat sampai keluar output tulisan spring 
6. Kemudian masukkan perintah seperti dibawah ini pada Source Package -> com.farid.microservices.latihan2service -> Latihan2ServiceApplication.java
![image](https://user-images.githubusercontent.com/113502299/192331056-864b3413-7a42-4601-a738-4d1f599da2ae.png)
7. Lalu kita akan mengatur port yang akan kita gunakan, disini saya menggunakan port 8010 untuk latihan 2
![image](https://user-images.githubusercontent.com/113502299/192331353-e84e77b3-7ed4-48c9-bfd3-8184cf23f410.png)
8. Terakhir kita run file di Latihan2ServiceApplication.java
9. Setelah itu kita pergi ke chrome kita lalu ketikkan http://localhost:8010/hello
