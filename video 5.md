# BEKERJA DENGAN GIT

## Git command

```
$ git init
$ git add <file(s)>
$ git status 
$ git commit 
$ git config
$ git branch
$ git help
```
## 3 area pada repo git
1. Working tree, folder tempat kita bekerja
2. Staging area, kita memberi tahu git bahwa kita telah melakukan perubahan
3. History, kita memberi tahu git untuk menyimpan perubahan

staging area dan history akan tersimpan di folder git.

## Hands On

Berikut adalah percobaan git sederhana sesuai dengan video ke 5 dari channel Web Pemrograman Unpas:

![Screenshot 1](https://user-images.githubusercontent.com/116989429/217222779-380345b6-c120-449c-a056-baedce436d58.png)
![Screenshot 2](https://user-images.githubusercontent.com/116989429/217222815-8cd06aa9-f385-4c62-9ede-c3b2a6607b87.png)
![Screenshot 3](https://user-images.githubusercontent.com/116989429/217222822-cda19024-6ecf-40ef-8803-2c9a06e84643.png)
![Screenshot 4](https://user-images.githubusercontent.com/116989429/217222842-cb42dfac-7ffb-41b3-bc2c-9fe43e401088.png)

![Screenshot 5](https://user-images.githubusercontent.com/116989429/217222850-bcc2e69b-ef60-4fa7-86ec-03d9b1503d93.png)


keterangan:
1. git init: kita memberi tahu git untuk mengawasi file tertentu
2. ls: digunakan untuk mengetahui isi yang ada di folder tersebut
3. git status: untuk mengecek perubahan yang sedang terjadi apakah ada atau tidak
4. git add index.html: digunakan memasukkan file index.html ke dalam stagging area.
5. git config --global user.name: untuk mengenalkan identitas nama kepada git
6. git config --global user.name: untuk mengenalkan identitas email kepada git
7. git commit -m "nama file" : digunakan untuk menyimpan perubahan yang terjadi
8. git log: digunakan untuk mengecek semua perubahan yang terjadi
9. git add . : digunakan untuk menamabahkan semua file ke stagging area.
10. git log -3: digunakan untuk mengecek 3 perubahan terakhir yang terjadi.
11. git checkout 6kodeawal -- file : digunakan untuk mengembalikan file yang sudah dihapus.




