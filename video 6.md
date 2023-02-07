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

![Alt text](Screenshot%201.png)
Keterangan:

head akan menunjuk ke arah branch yang aktif. Saat dilakukan commit, head juga akan berpindah dan menunjuk branch aktif setelah commit. Defaultnya branch akan menunjuk branch utama yang disebut master.

kondisi akhir:

![Alt text](Screenshot%202.png)

