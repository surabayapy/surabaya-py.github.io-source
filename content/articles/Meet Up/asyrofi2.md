Title: Acara Kedua
Date: 2010-10-19 15:00
# Acara Hacktober 2019  Bagian 2
Dalam sesi kedua ini lebih mengarahkan pada proses penggunaan pelican untuk transfer localhost agar bisa terlihat pada browser

salah satu caranya sebagai berikut:

1. dengan perintah sebagai berikut, maka bisa segera digunakan untuk perintah pengcompilan.
```python
pelican
```

2. Lalu dilanjutkan dengan untuk fungsi memanggil ke localhost, maka perlu perintah sebagai berikut:
```python
pelican --listen
```

3. kemudian untuk mengupdate hasil compile'an sebelumnya kita menggunakan perintah berikut, untuk dapat dilihat hasilnya..
```python
pelican --autoreload
```

4. dan terakhir untuk mengaktifkan pada browser tinggal beri perintah pada url untuk hasil compile'an tadi.
```python
localhost:8000
```