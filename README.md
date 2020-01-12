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

•	Buka direktory aktif, misal: d:\labs_pemrograman2 (buka menggunakan Windows Explorer)
•	klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash, sehingga muncul git bash commad
•	Buat direktory project praktikum pertama dengan nama latihan2

![image](https://user-images.githubusercontent.com/56479448/72219171-a5f58c00-3575-11ea-8212-50f1a7522c43.png)

•	Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change directory)
•	direktory aktif menjadi: d:\labs_pemrograman2\latihan2

Membuat Repository Local

•	Jalankan perintah git init, untuk membuat repository local.

![image](https://user-images.githubusercontent.com/56479448/72219178-b73e9880-3575-11ea-8dd3-f8644fc9fe1f.png)

•	Repository baru berhasil di inisialisasi, dengan terbentuknya satu direktori hidden dengan nama .git
•	Pada direktori tersebut, semua perubahan pada working directory akan disimpan.

Menambahkan File baru pada repository

•	Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)
•	disini kita akan coba buat satu file bernama README2.md (text file)

![image](https://user-images.githubusercontent.com/56479448/72219186-cb829580-3575-11ea-8ef0-4ecac46d5ba9.png)

•	File README2.md berhasil dibuat.

![image](https://user-images.githubusercontent.com/56479448/72219191-dccba200-3575-11ea-8af1-06eb7e6b5c77.png)

Menambahkan File baru pada repository

•	Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add.

![image](https://user-images.githubusercontent.com/56479448/72219197-ee14ae80-3575-11ea-9f54-64e0d09175e0.png)

File README2.md berhasil ditambahkan.

![image](https://user-images.githubusercontent.com/56479448/72219201-0389d880-3576-11ea-9d77-579757d7505e.png)

Commit (Menyimpan perubahan ke database)

•	Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m “komentar commit”

![image](https://user-images.githubusercontent.com/56479448/72219213-274d1e80-3576-11ea-8035-2400de919926.png)

•	Perubahan berhasil disimpan.

![image](https://user-images.githubusercontent.com/56479448/72219224-4350c000-3576-11ea-86ab-53c0af787ef1.png)

Membuat repository server

•	Server reopsitory yang akan kita gunakan adalah http://github.com
•	Anda harus membuat akun terlebih dahulu. 
•	Pada laman github, klik tombol start a project, atau
•	Dari menu (icon +) klik New Repository

![image](https://user-images.githubusercontent.com/56479448/72219232-5794bd00-3576-11ea-83e3-1b57b79c19b7.png)

Membuat repository server

•	Isi nama repositorynya, misal: Pemrograman
•	lalu klik tombol Create repository

![image](https://user-images.githubusercontent.com/56479448/72219242-7004d780-3576-11ea-9e8c-0e2c107ac0b9.png)

Menambahkan Remote Repository

•	Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user.
•	Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url]

![image](https://user-images.githubusercontent.com/56479448/72219246-83b03e00-3576-11ea-82e4-d9e31ff91f95.png)

Push (Mengirim perubahan ke server)

•	Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.

![image](https://user-images.githubusercontent.com/56479448/72219256-9c205880-3576-11ea-8b8f-a14ee0885639.png)

•	Perintah ini akan meminta memasukkan username dan password pada akun github.com

![image](https://user-images.githubusercontent.com/56479448/72219262-ae01fb80-3576-11ea-8ad8-612c6b0d1c1b.png)

Melihat hasilnya pada server repository

•	Buka laman github.com, arahkan pada repositori-nya.
•	Maka perubahan akan terlihat pada laman tersebut.

![image](https://user-images.githubusercontent.com/56479448/72219269-c4a85280-3576-11ea-995b-91a083ccaa84.png)

Clone Repository

•	Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan 
nama repositorynya (working directory).

•	Untuk melakukan cloning, gunakan perintah git clone [url]

![image](https://user-images.githubusercontent.com/56479448/72219271-d1c54180-3576-11ea-9b12-79829b04c461.png)
