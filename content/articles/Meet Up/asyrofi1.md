Title: Acara Pertama
Date: 2010-10-19 14:00
# Acara Hacktober 2019  Bagian 1
Dalam acara ini seputar tentang pembahasan bagaimana penggunaan git untuk push-pull parameter pada github.io

salah satu caranya sebagai berikut:

1. Penggunaan fungsi print pada python untuk membaca perintah string langsung ke monitor.
```python
print('Hello world')
```

2. selanjutnya kita menggunakan perintah git sebagai berikut:
 ```python
git config --global user.email "email_anda@home.com"
git config --global user.name "user_anda"
```
perintah ini digunakan untuk pertama menginisialisai git pada kode editor anda.

3. selanjutnya kita menggunakan perintah clone untuk mengkloning atau ngemirror file yang ingin kita download ke file directory kita berikut:
 ```python
git clone
```

4. kemudian  perintah git selanjutnya digunakan untuk:
 ```python
git add.
```
perintah ini digunakan menambah untuk semua file yang ada directory anda.

 ```python
git add nama_file.py
```
perintah ini digunakan menambah untuk file tertentu yang ada directory anda.

5. setelah itu perintah git commit untuk memberi komentar, pada file yang ingin dirubah
 ```python
git commit -m "tambah_file"
```

6. setelah itu perintah push untuk mempush file yang ingin ditambahakan ke repository github anda.
 ```python
git push -u origin master
```

7. selanjutnya kita menggunakan fungsi status untuk melihat kondisi file directory kita saat ini, apakah perlu tambahan apa tidak
 ```python
git status
```

bila ada perubahan, maka lakukan proses dari poin 4-6

8. Fungsi terakhir apabila kita ingin mengetahui update apa saja yang terbaru dari repository sebelumnya, maka lakukan proses pull untuk menarik file2 update sebelumnya.
 ```python
git pull
```
