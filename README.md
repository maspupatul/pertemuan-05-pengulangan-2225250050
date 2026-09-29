# Pertemuan 05 Perulangan Python

**Nama:** Maspupatul Hasanah
**NIM:** 2225250050
**Kelas:** 3A

## Tujuan

1. Memahami konsep perulangan menggunakan `for` dan `while` dalam Python.
2. Menggunakan `range()` untuk menentukan urutan dan jumlah iterasi.
3. Menggunakan kondisi berhenti dan memperbarui variabel kontrol pada perulangan `while`.
4. Menggabungkan seleksi `if` dengan perulangan.
5. Menggunakan akumulasi untuk menghitung jumlah nilai secara berulang.
6. Melakukan pengujian program dan mengunggah hasil pekerjaan ke GitHub.

## Struktur Folder

```text
pertemuan-05-perulangan-2225250050/
├── README.md
├── .gitignore
├── latihan/
│   ├── 01_tabel_perkalian.py
│   ├── 02_jumlah_bilangan.py
│   ├── 03_validasi_input.py
│   └── 04_hitung_genap.py
└── kuis/
    └── kuis2_deret_aritmetika.py
```

## Cara Menjalankan

Program dijalankan melalui terminal di VS Code menggunakan Python.

Untuk menjalankan latihan, gunakan perintah berikut:

```bash
python latihan/01_tabel_perkalian.py
python latihan/02_jumlah_bilangan.py
python latihan/03_validasi_input.py
python latihan/04_hitung_genap.py
```

Untuk menjalankan Kuis 2:

```bash
python kuis/kuis2_deret_aritmetika.py
```

## Algoritma Kuis 2: Deret Aritmetika

1. Meminta pengguna memasukkan suku pertama (`a`), beda (`d`), dan banyak suku (`n`).
2. Memeriksa apakah nilai `n` merupakan bilangan bulat positif.
3. Jika `n` kurang dari atau sama dengan nol, program meminta pengguna memasukkan kembali nilai `n` sampai valid.
4. Menginisialisasi variabel `total = 0` sebelum perulangan.
5. Menggunakan perulangan `for` untuk menghasilkan suku sebanyak `n` kali.
6. Menghitung setiap suku menggunakan rumus `suku = a + i * d`.
7. Menambahkan setiap suku ke variabel `total`.
8. Menampilkan nomor dan nilai setiap suku.
9. Menampilkan jumlah seluruh suku dengan dua angka di belakang koma setelah perulangan selesai.

## Hasil Pengujian

| No. | Suku Pertama (a) | Beda (d) | Banyak Suku (n) | Suku yang Dihasilkan | Jumlah |
| --- | ---------------: | -------: | --------------: | -------------------- | -----: |
| 1   |                2 |        3 |               5 | 2, 5, 8, 11, 14      |  40,00 |
| 2   |               10 |       -2 |               4 | 10, 8, 6, 4          |  28,00 |
| 3   |              1,5 |      0,5 |               3 | 1,5; 2,0; 2,5        |   6,00 |

**Catatan:** Tabel ini berisi hasil yang diharapkan berdasarkan test case pada modul. Setelah program dijalankan, sesuaikan kolom hasil aktual dan status dengan hasil pengujianmu sendiri.

## Refleksi

Melalui praktikum ini, saya mempelajari bahwa perulangan `for` sesuai digunakan ketika jumlah iterasi sudah diketahui, sedangkan `while` digunakan ketika perulangan dikendalikan oleh suatu kondisi. Saya juga memahami bahwa variabel kontrol harus diperbarui agar perulangan dapat berhenti dengan benar.

Salah satu kesalahan yang dapat terjadi adalah *infinite loop*, yaitu perulangan yang tidak berhenti karena kondisi tetap bernilai `True`. Kesalahan tersebut dapat diperbaiki dengan memeriksa kondisi dan memastikan variabel kontrol diperbarui dengan benar.

Selain itu, variabel `total` harus diinisialisasi sebelum perulangan agar hasil penjumlahan dapat terakumulasi dengan benar. Pengujian menggunakan beberapa test case membantu memastikan bahwa program menghasilkan keluaran sesuai dengan yang diharapkan.

## Pengumpulan melalui GitHub

Repositori ini berisi latihan perulangan Python, program Kuis 2 deret aritmetika, dokumentasi, dan hasil pengujian. Perubahan program dicatat menggunakan `git commit` dan dikirim ke repositori GitHub menggunakan `git push`.

## Referensi

1. Python Software Foundation. *Python 3 Documentation: Control Flow Tools*.
2. Visual Studio Code Documentation. *Python in Visual Studio Code*.
3. GitHub Docs. *Creating a New Repository* dan *Adding Locally Hosted Code to GitHub*.
4. Modul Bahan Ajar Algoritma dan Pemrograman Pertemuan 05: Perulangan `for` dan `while` dalam Python di VS Code dan Pengumpulan melalui GitHub, Tahun Ajaran 2026/2027 Ganjil.
