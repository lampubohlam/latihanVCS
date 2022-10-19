# HALO PERKENALKAN NAMA SAYA ABDUL AZIZ
Saya akan akan mempelajari cara informasi tentang Vesrion Control Systeem (VCS) dengan menggunakan Git

# 1. Penginstalan Git
        Pergi ke website www.git-scm.com
        pilih menu download dan silahkan pilih device anda apakah 32 bit atau 64 bit
        jika sudah maka instal aplikasi ke dengan mencari folder git dan instal aplikasinya
        
# 2. Membuat Repository Lokal
        cara membuat repoitory local :
        pastikan file sudah berada di home/dokumen lain lalu buka windows directory di windows explorer
         saya menggunakan direktory c/user/..
    kita bisa berpindah directory dengan cara $ cd .. lalu cd d/nama_folder
    
    Kita akan membuat repository dengan perintah $ mkdir nama_directory
          contoh : $ mkdir lab_komputer, $ mkdir tugas1
          
	   Selanjutnya kita akan masuk kedalam directory menggunakan perintah $ cd nama_directory
      -membuat repository local dengan perintah $  git init
      -lalu membuat sebuah file (teks) dengan menggunakan perintah $ echo "# membuat teks" >> README.md
      -Sebelum kita menambahkan file kedalam repository,sebaiknya masukan perintah git config agar saat proses git commit tidak eror
  ($ git config --global user.name "nama.user"), 
  ($ git config --global user.email "email.user")
  
  Setelah menambahkan git config untuk memasukan file kedalam repository kita gunakan perintah $ git add README.md
  Untuk menyimpan perubahan kedalam database repository maka menggunakan perintah $ git commit -m "komentar"
# 3 membuat repository sistem
      -Masuk ke website git (www.github.com)
      - Lalu lakukan login / membuat akun terlebih dahulu
      -masukan email & pasword
      -ikuti instruksi dari github.com
      -klik create repository di pojok kanan atas
# 4 mengirim perubahan
      menambahkan remote repository,fungsinya adalah menyimpan setiap perubahan pada repository local
    -pada repository server ada link yang akan kita gunakan untuk menjalankan perintah $ git remote add origin [url]
    $ git remote add origin https://github.com/lampubohlam/LatihanVCS.git
    
     -mengirim file ke repository server dengan perintah $ git push -u master
     -masukan nama user & sandi
     - untuk memeriksa hasil,buka kembali website github > user > repository > klik repository
# 5 Clone repository
     -.Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working directory).
Perintahnya adalah $ git clone [URL]


                                                           "TERIMA KASIH"
     
