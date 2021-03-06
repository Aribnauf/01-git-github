# 01-git-github
---------------
Git dan GitHub merupakan dua platform yang didirikan oleh satu perusahaan dengan tujuan sama serta fitur yang berbeda. Namun kedua platform ini sangat membantu pekerjaan programmer dalam menyusun kode script secara tim. Seluruh pekerjaan juga dapat dipantau dan dievaluasi dengan mudah karena penggunaan kontrol sistem.

Git merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project. Developer software biasa menggunakan Git untuk distributed revision (VCS terdistribusi), hal ini bertujuan untuk menyimpan database tidak hanya ke satu tempat. Namun semua orang yang terlibat dalam penyusunan kode dapat menyimpan database ini.

GitHub merupakan layanan cloud yang berguna untuk menyimpan dan mengelola sebuah project yang dinamakan repository (repo git). Cara kerja pada GitHub harus terkoneksi pada internet sehingga tidak perlu meng-install sebuah software ke dalam perangkat keras. Hal ini memberikan keringanan penyimpanan komputer yang kita gunakan karena file project tersimpan oleh cloud GitHub.

##Instalasi Git di Windows
==========================
1. Download Git di: https://git-scm.com/downloads
2. Double click pada file yang di download, maka akan muncul licence, dan click next.
3. Pada halaman berikutnya "Select Components" jika ingin menambahlan icon Git pada Desktop, maka silahkan click/centang pada "Additional icon", adapun untuk pilihan yang lainnya biarkan saja pada pilihan default.
@@ -25,3 +27,24 @@ GitHub merupakan layanan cloud yang berguna untuk menyimpan dan mengelola sebuah
16. Jika selesai akan muncul dialog pemberitahuan. Klik pada Finish.
17. Untuk menjalankan, dari Start menu, ketikkan "Git", akan muncul beberapa pilihan. Pilih "Git Bash" atau "Git GUI".
18. Untuk mencoba dari command prompt, masuk ke command prompt, setelah itu eksekusi "git --version" untuk melihat apakah sudah terinstall atau belum. Jika sudah terinstall dengan benar, maka akan muncul versi dari Git yang kita pakai serta jenis sistem Operasi yang kita pakai.

##Konfigurasi Git
=================
Pada saat membuat perubahan pada repo Git, git akan membuat sebuah snapshot tentang siapa dan apa perubahan yang dilakukan pada repo git kita. Untuk itu, Git memerlukan username dan email dari user untuk mengetahui siapa yang melakukan perubahan tersebut. Adapun cara untuk mengkonfigurasi username dan email adalah sebagai berikut :
1. Buka Git Bash atau Command prompt
2. Ketikkan perintahm :
	a. Untuk Username : $ git config --global user.name "Username yang dibuat saat register di GitHub"
	b. Untuk Email    : $ git config --global user.email "Email yang dimasukkan saat register di GitHub"
3. Cek konfigurasi apakah sudah ada dengan mengetik perintah : $ git config --list
Setelah perintah tersebut diberikan, maka akan muncul userename dan email yang sudah dikonfigurasi.

##Membuat Repo Di Github
========================
Untuk Membuat Repo di github hal pertama yang perlu diperhatikan adalah kita register di github itu sendiri. Adapunlangkah-angkah pembuatan repo di github adalah sebagai berikut :
1. Setelah masuk ke akun github kita sendiri, klik tanda plus pada sisi kanan atas lalu pilih "new repository"
2. Isi "Repository name" dengan nama repo kita sesuai yang kita inginkan.
3. Isi "Description" jika ingin, namun ini hanya optional dan tidak berpengaruh apa - apa pada repo kita.
4. Centang pilihan "Add a README file" jika anda ingin membuat file README di dalam repo anda.
5. Centang pilihan "choose Licence" jika anda ingin membuat suatu lisensi tertentu pada repo anda.
6. Creat Repository.
7. Pilih edit untuk mengedit repository
