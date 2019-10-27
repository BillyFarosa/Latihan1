                        Cara Penggunaan Git Beserta Tutorialnya.
                        
      1. Silahkan daftar ke http://github.com atau git lainnya. 
      Caranya : 1. Buka http://github.com atau git yang diinginkan.
                2. Pilih menu berikut :
![Untitled](https://user-images.githubusercontent.com/57003140/67624265-93ae6080-f858-11e9-8463-f1c6b4d5c23c.png)
                Maka akan muncul
![Untitled](https://user-images.githubusercontent.com/57003140/67624306-2f3fd100-f859-11e9-9ec5-78718ac280af.png)
                3. Isilah format tersebut sesuai data pribadi.
                4. Selamat anda telah membuat aku Git-Hub anda sendiri.
     
     
     
     2. Buat Repository baru dengan cara berikut :
![Untitled](https://user-images.githubusercontent.com/57003140/67624404-50ed8800-f85a-11e9-9b11-2cfed2070400.png)
         Selesai.
     
     
     
     3. Install GitBash dengan cara :
          1. Buka http://git-scm.com
          2. pilih download dan sesuaikan dengan spesifikasi PC anda
![00-56-54-67517048-ee668180-f6cb-11e9-8f7e-999a25a197c2](https://user-images.githubusercontent.com/57003140/67624625-310b9380-f85d-11e9-96de-865141f7823a.png)
          3. Install GitBash ketika selesai di download.
          
![00-57-10-67518391-ebb95b80-f6ce-11e9-97ed-37038b021405](https://user-images.githubusercontent.com/57003140/67624666-c4dd5f80-f85d-11e9-942e-6a9bf4169683.png)

    4. Menambahkan Global Config dengan cara : 
        1. Pada saat pertama kali menggunakan git,perlu dilakukan konfigurasi user.name dan user.mai
        2. Konfigurasi ini bisa dilakukan untuk global repository atau individual repository
        3. Apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit
        4.   Config Global Repository
$ git config --global user.name “nama_user”

$ git config --global user.email “nama_user”

     5. Perintah Dasar Git
        • git init, perintah untuk membuat repository local 
        • git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit. 
        • git commit, perintah untuk menyimpan perubahan kedalam database git. 
        • git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository. 
        • git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever. 
        • git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory) 
        • git pull, perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke local repository 

    6. Membuat Reposiory Local
        • Buka direktory aktif, misal: F:\labs_pemrograman1 (buka menggunakan Windows Explorer) 
        • klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash, sehingga muncul git bash commad 
        • Buat direktory project praktikum pertama dengan nama latihan1
          $ mkdir latihan1 
          $ cd latihan1
        • Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change directory) 
        • direktory aktif menjadi: F:\labs_pemrograman1\
        
 ![Tanpa judul](https://user-images.githubusercontent.com/57003140/67628055-17387380-f892-11e9-915f-7cbbc63c1fca.png)
    
    7. Membuat Reposiory Local
        • Jalankan perintah git init, untuk membuat repository local.
          $ git init
        • Repository baru berhasil di inisialisasi, dengan terbentuknya satu direktori hidden dengan nama .git 
        • Pada direktori tersebut, semua perubahan pada working directory akan disimpan. 
        
    8. Menambahkan File baru pada repository
        • Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository) 
        • disini kita akan coba buat satu file bernama README.md (text file)
          $ echo “#Latihan 1” >> README.md
        • File README.md berhasil dibuat. 
        
 ![Tanpa judul](https://user-images.githubusercontent.com/57003140/67628096-eefd4480-f892-11e9-835c-46a085db88f0.png)
       
     9. Menambahkan File baru pada repository
        • Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add.
          $ git add README.md
        • File README.md berhasil ditambahkan.
        
 ![Tanpa judul](https://user-images.githubusercontent.com/57003140/67628226-6e3f4800-f894-11e9-9d15-93cd670fe6da.png)
 
     10. Commit (Menyimpan perubahan ke database)
        • Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m “komentar commit”
          $ git commit -m “File pertama saya”
        • Perubahan berhasil disimpan. 
        
 ![Tanpa judul](https://user-images.githubusercontent.com/57003140/67628263-bb231e80-f894-11e9-8c38-67d287b4e96f.png)
 
     11.  Menambahkan Remote Repository
        • Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user. 
        • Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url]
         $ git remote add origin https://github.com/BillyFarosa/Latihan1
     12. Push (Mengirim perubahan ke server)
        • Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
          $ git push -u origin master
        • Perintah ini akan meminta memasukkan username dan password pada akun github.com 
     13. Clone Repository
        • Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working directory). 
        • Untuk melakukan cloning, gunakan perintah git clone [url]





      


