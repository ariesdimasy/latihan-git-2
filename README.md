# Latihan Git

## Front End 
- masuk ke folder front-end di terminal
- ketik `npm install` lalu enter
- buka browser , lalu ketik `localhost:3000`

## Back End 
- masuk ke folder backend 
- buka terminal , arahkan ke working directory project folder backend 
- ketik `npm install` lalu enter
- buat database `nama_db` di database administrator mysql
- ketik `sequelize db:migrate` lalu enter
- ketik `sequelize db:seed:all` lalu enter
- ketik `nodemon index` untuk menjalankan aplikasi
- buka browser , lalu ketik `localhost:4567` untuk menjalankan API

```git

git init : untuk initialisasi project git 
git clone url_git : untuk mendownload repo hosting ( github ) ke local computer , menjadikan repo local baru secara otomatis 
git remote add origin url_git : untuk menyambungkan repo local git ke repo hosting ( github )
git add nama_file : untuk mendaftarkan file sebelum di commit 
git commit -m "isi message commit" : untuk mendaftarkan file file dari hasil git add sebelum di push 
git push origin nama_branch : untuk push file local ke file git hosting ( github )
git pull origin nama_branch : untuk menarik / download file di hosting ( github ) ke local repo 

git branch : untuk mengetahui list branch dan branch yang aktif 
git branch nama_branch : untuk membuat nama branch baru 
git checkout : untuk berpindah branch 
git checkout -b nama_branch : untuk membuat branch baru san pindah ke branch itu 
git branch -M main : 
```
