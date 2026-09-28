# Pertemuan 05 Perulangan Python

Nama: Adelilya Salsha
NIM: [Isi NIM]
Kelas: [Isi Kelas]

## Tujuan

Menggunakan `for` dan `while` untuk menyelesaikan masalah iteratif.

## Cara Menjalankan

Program Kuis 2 dapat dijalankan dengan perintah:

```bash
python3 kuis/kuis2_deret_aritmetika.py
```

## Algoritma Kuis 2

1. Memasukkan suku pertama `a`.
2. Memasukkan beda `d`.
3. Memasukkan banyak suku `n`.
4. Memeriksa nilai `n` menggunakan `while`.
5. Jika `n <= 0`, pengguna diminta memasukkan kembali nilai `n`.
6. Menentukan `total = 0`.
7. Menggunakan `for` untuk mengulang sebanyak `n` suku.
8. Menghitung setiap suku dengan `suku = a + i * d`.
9. Menambahkan setiap suku ke dalam `total`.
10. Menampilkan setiap suku dan jumlah seluruh suku.

## Hasil Pengujian

| No | Input (a, d, n) | Keluaran yang Diharapkan        | Keluaran Aktual                                | Status   |
| -- | --------------- | ------------------------------- | ---------------------------------------------- | -------- |
| 1  | 2, 3, 5         | 2, 5, 8, 11, 14; Jumlah = 40.00 | 2.00, 5.00, 8.00, 11.00, 14.00; Jumlah = 40.00 | Berhasil |
| 2  | 10, -2, 4       | 10, 8, 6, 4; Jumlah = 28.00     | 10.00, 8.00, 6.00, 4.00; Jumlah = 28.00        | Berhasil |
| 3  | 1.5, 0.5, 3     | 1.5, 2.0, 2.5; Jumlah = 6.00    | 1.50, 2.00, 2.50; Jumlah = 6.00                | Berhasil |

## Refleksi

Kesalahan yang ditemukan adalah jika nilai `n` kurang dari atau sama dengan 0, program tidak dapat menjalankan perulangan dengan benar. Kesalahan tersebut diperbaiki dengan menggunakan `while` untuk meminta pengguna memasukkan nilai `n` kembali sampai mendapatkan bilangan bulat positif.

Penggunaan `while` digunakan untuk validasi input, sedangkan `for` digunakan untuk memproses deret dengan jumlah perulangan yang sudah diketahui.
