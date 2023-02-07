# Branch & Merge

## Command
- command berikut adalah command commit dan bisa dipakai kalau file dalam keadaan _modified_ untuk meng _commit_ suatu file
```
$ git commit -am
```

- command berikut digunakan untuk mengecek branch apa aja yang ada di folder tersebut saat ini
```
$ git branch
```

- command berikut digunakan untuk membuat branch
```
$ git branch <nama branch>
```
-  command berikut digunakan untuk memvisualisasikan perubahan yang terjadi pada folder
```
- git log --all --decorate --oneline --graph
```
- alias dipakai buat menyingkat pemanggilan
```
alias graph = "git log --all --decorate --oneline --graph

```
- pindah branch
```
git checkout <nama branch>
```
- menggabungkan dua branch
```
git merge
```

- menghapus branch
```
git -d <nama branch>
```
- ngecek file yang udah di merge
```
git branch --merged
```

## Branch
Branch adalah cabang bebas dari commit-commit kita. Digunakan ketika membuat fitur baru dan belum yakin akan impelementasinya dan ketika mengerjakan suatu projek secara berkelompok.

## Merge
Merge adalah menggabungkan cabang. Berikut adalah jenis-jenis merge:

1. Fast Forward terjadi ketika branch yang ingin digabungkan berada pada jalur langsung atau direct path.

## Implementasi Branch

kondisi awal:

![Screenshot 1](https://user-images.githubusercontent.com/116989429/217262554-e0feaa19-0375-4451-94fd-4d2ae919089c.png)

Keterangan:

head akan menunjuk ke arah branch yang aktif. Saat dilakukan commit, head juga akan berpindah dan menunjuk branch aktif setelah commit. Defaultnya branch akan menunjuk branch utama yang disebut master.

kondisi akhir:
![Screenshot 2](https://user-images.githubusercontent.com/116989429/217262573-25e35dae-5736-4bdd-b8a2-8d675388146f.png)

Dokumentasi
![Screenshot 3](https://user-images.githubusercontent.com/116989429/217262731-39afadfd-d15e-428a-9c47-027be831e7ba.png)
![Screenshot 4](https://user-images.githubusercontent.com/116989429/217262737-e5d2b602-879e-42e3-a3f4-32cd44c8d859.png)
![screenshot 5](https://user-images.githubusercontent.com/116989429/217262748-129c2262-11df-449f-bbdf-187feceb7154.png)
![Screenshot 6](https://user-images.githubusercontent.com/116989429/217262760-7e3788d7-09a0-4cb1-9bf6-ef0e11cffdb3.png)
![Screenshot 7](https://user-images.githubusercontent.com/116989429/217262771-035fb0ac-4141-4097-88cd-73023bbe4125.png)








