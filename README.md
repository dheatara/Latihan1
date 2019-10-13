1. Setelah terinstall untuk mencobanya silahkan double klik icon Gitbash, kemudian ketik perintah “git --version”

![image](https://user-images.githubusercontent.com/56398506/66709815-ff42f900-ed95-11e9-9725-4fb5fd78e3fc.png)

Pada saat pertama kali menggunakan harus melakukan configurasi “user.name” dan” user.email” dengan ketik perintah

(git config --global user.name "nama_anda")

(git config --global user.email "email_anda")

![image](https://user-images.githubusercontent.com/56398506/66709908-f81cea80-ed97-11e9-9d20-399bb4353e0b.png)

2. Buat directory project praktikum baru dengan nama “latihan1” dengan ketik perintah

(mkdir latihan1)

(cd latihan1) 

![image](https://user-images.githubusercontent.com/56398506/66709970-2c44db00-ed99-11e9-8609-63b10fa4406f.png)

3. selanjutnya kita akan membuat repository local dengan perintah “git init”

![image](https://user-images.githubusercontent.com/56398506/66710039-a4f86700-ed9a-11e9-8ef7-9f681c9d6db7.png)

4. Kita akan membuat satu file bernama README.md(text file)dengan ketik perintah

(echo “#Latihan 1” >> README.md)

![image](https://user-images.githubusercontent.com/56398506/66710099-da518480-ed9b-11e9-9ac4-1f77665cc6e2.png)

File README.md berhasil dibuat. 

![image](https://user-images.githubusercontent.com/56398506/66710107-04a34200-ed9c-11e9-8cf5-a1b0189ee7a9.png)

5. Kemudian masukan file yang baru dibuat dengan menggunakan perintah  “git add”

(git add README.md) 

![image](https://user-images.githubusercontent.com/56398506/66710117-387e6780-ed9c-11e9-9afe-499f45e152c3.png)

6. Untuk menyimpan perubahan pada database repository local gunakan perintah 

(git commit –m “File pertama saya”) 

Perubahan berhasil dilakukan. 

![image](https://user-images.githubusercontent.com/56398506/66710133-91e69680-ed9c-11e9-8160-67231140b169.png)

7. Selanjutnya adalah membuat repository server.

•	Kunjungi halaman https://github.com/github

•	Anda harus membuat akun github terlebih dahulu

•	Kemudian klik ikon (+) dipojok kanan atas, pilih New repository

•	Pilih Start a project

![image](https://user-images.githubusercontent.com/56398506/66710148-eb4ec580-ed9c-11e9-9900-e105caaacf27.png)

![image](https://user-images.githubusercontent.com/56398506/66710165-23560880-ed9d-11e9-9c0b-2c87f5bf616f.png)

•	Isi repository name nya dengan nama "Latihan1"

•	Kemudian klik tombol Crate Repository di bagian bawah 

![image](https://user-images.githubusercontent.com/56398506/66710168-4bde0280-ed9d-11e9-85ba-426f19908101.png)

8. Supaya dapat di akses oleh banyak user, untuk melakukan remote repository gunakan perintah : 

"git remote add origin [https://github.com/dheatara/Latihan1.git]"

![image](https://user-images.githubusercontent.com/56398506/66710208-01a95100-ed9e-11e9-8d31-4db489d7a9e5.png)

9. Untuk mengirim perubahan pada local repository ke server gunakan perintah “git push”

(git push –u origin master)

Perintah ini akan menampilkan kotak perintah dan meminta anda memasukan username dan password akun git hub.

![image](https://user-images.githubusercontent.com/56398506/66710215-230a3d00-ed9e-11e9-8eb4-b37965c737b5.png)

10. Langakh terakhir liat hasil nya pada Repository Server. Buka laman https://github.com/github kemudian arahkan pada repository nya. Maka akan muncul tampilan seperti di bawah ini. Selamat repository server anda berhasil dibuat.

![image](https://user-images.githubusercontent.com/56398506/66710229-5220ae80-ed9e-11e9-877e-c9db14fe0507.png)

