#Latihan 1

# labpy1



Instalasi Git



•	Download Git, buka website resminya Git (git-scm.com).

•	Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.

•	Selamat, Git sudah terinstal di Windows. Untuk mencobanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah 

![image](https://user-images.githubusercontent.com/56479448/72219140-4d25f380-3575-11ea-9ed9-06d301876c9c.png)

![image](https://user-images.githubusercontent.com/56479448/72219147-6169f080-3575-11ea-8bcd-ad037794147d.png)



Menambahkan Global Config



•	Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email

•	konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository.

•	apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit

•	Config Global Repository

![image](https://user-images.githubusercontent.com/56479448/72219151-78104780-3575-11ea-9969-3febf9819850.png)

![image](https://user-images.githubusercontent.com/56479448/72219156-7cd4fb80-3575-11ea-8957-7a4a4735dba8.png)




Membuat Repository Local




•	Buka direktory aktif, misal: d:\labs_pemrograman1 (buka menggunakan Windows Explorer)

•	klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash, sehingga muncul git bash commad

•	Buat direktory project praktikum pertama dengan nama latihan1


![image](https://user-images.githubusercontent.com/56479448/72258630-246b3000-3641-11ea-81f4-dd25fb7af78a.png)



•	Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change directory)

•	direktory aktif menjadi: d:\labs_pemrograman\latihan1


![image](https://user-images.githubusercontent.com/56479448/72259161-55983000-3642-11ea-8fc9-e3c6b20b62e9.png)


Membuat Repository Local



•	Jalankan perintah git init, untuk membuat repository local.

![image](https://user-images.githubusercontent.com/56479448/72219178-b73e9880-3575-11ea-8dd3-f8644fc9fe1f.png)

![image](https://user-images.githubusercontent.com/56479448/72262500-a65f5700-3649-11ea-84bd-2dcd9551801b.png)


•	Repository baru berhasil di inisialisasi, dengan terbentuknya satu direktori hidden dengan nama .git

•	Pada direktori tersebut, semua perubahan pada working directory akan disimpan.



Menambahkan File baru pada repository



•	Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)

•	disini kita akan coba buat satu file bernama README.md (text file)


![image](https://user-images.githubusercontent.com/56479448/72259737-c5f38100-3643-11ea-80fd-b51f2e513562.png)


•	File README.md berhasil dibuat.


![image](https://user-images.githubusercontent.com/56479448/72262599-d4449b80-3649-11ea-9774-fe750b675a2f.png)



Menambahkan File baru pada repository



•	Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add.

![image](https://user-images.githubusercontent.com/56479448/72260126-b4f73f80-3644-11ea-8c41-cf06884fe108.png)



File README.md berhasil ditambahkan.


![image](https://user-images.githubusercontent.com/56479448/72260734-123fc080-3646-11ea-8a81-536bdf58b813.png)


Membuat repository server



•	Server reopsitory yang akan kita gunakan adalah http://github.com

•	Anda harus membuat akun terlebih dahulu. 

•	Pada laman github, klik tombol start a project, atau

•	Dari menu (icon +) klik New Repository

![image](https://user-images.githubusercontent.com/56479448/72219232-5794bd00-3576-11ea-83e3-1b57b79c19b7.png)



Membuat repository server



•	Isi nama repositorynya, misal: Labpy1

•	lalu klik tombol Create repository


![image](https://user-images.githubusercontent.com/56479448/72261386-4c5d9200-3647-11ea-99b7-a3378f200cf8.png)




Menambahkan Remote Repository



•	Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user.

•	Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url]

![image](https://user-images.githubusercontent.com/56479448/72261686-dc034080-3647-11ea-84d0-9d5f23db8f1b.png)



Push (Mengirim perubahan ke server)



•	Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.

![image](https://user-images.githubusercontent.com/56479448/72219256-9c205880-3576-11ea-8b8f-a14ee0885639.png)

•	Perintah ini akan meminta memasukkan username dan password pada akun github.com


![image](https://user-images.githubusercontent.com/56479448/72262993-96944280-364a-11ea-81d1-1d548b98909d.png)


Melihat hasilnya pada server repository



•	Buka laman github.com, arahkan pada repositori-nya.

•	Maka perubahan akan terlihat pada laman tersebut.

![image](https://user-images.githubusercontent.com/56479448/72262148-e5d97380-3648-11ea-9a0d-4c76d6738806.png)
