# Pertemuan 10 — String dan Pengolahan Teks dalam Python

**Nama:** Mutiara Sari  
**NIM:** 2225250071  
**Kelas:** 3A  
**Program Studi:** Pendidikan Matematika

## A. Deskripsi

Proyek ini dibuat untuk memenuhi tugas Pertemuan 10 mata kuliah Algoritma Pemrograman. Materi yang dipelajari adalah pengolahan string dalam Python, meliputi operasi dasar string, indeks dan slicing, method string, pembersihan teks, pemisahan dan penggabungan kata, pencarian kata, serta normalisasi data mahasiswa.

## B. Struktur Proyek

```text
pertemuan-10-string-2225250071/
├── README.md
├── .gitignore
├── latihan/
│   ├── 01_dasar_string.py
│   ├── 02_indeks_slicing.py
│   ├── 03_method_string.py
│   ├── 04_bersihkan_teks.py
│   ├── 05_split_join.py
│   └── 06_pencarian_kata.py
└── tugas/
    └── normalisasi_data_mahasiswa.py
```

## C. Cara Menjalankan Program

Pastikan Python sudah terpasang. Buka terminal pada folder proyek, kemudian jalankan salah satu perintah berikut.

Contoh menjalankan latihan:

```powershell
python latihan/01_dasar_string.py
```

Contoh menjalankan tugas utama:

```powershell
python tugas/normalisasi_data_mahasiswa.py
```

Jika perintah `python` tidak dikenali pada komputer, gunakan executable Python yang tersedia di komputer masing-masing.

## D. Ringkasan Materi

1. **Dasar string:** menampilkan teks, menghitung panjang string dengan `len()`, dan mengubah huruf menggunakan `upper()` serta `lower()`.
2. **Indeks dan slicing:** mengambil karakter berdasarkan indeks dan memotong string.
3. **Method string:** membersihkan spasi menggunakan `strip()` serta mengubah format huruf menggunakan `title()` dan `upper()`.
4. **Pembersihan teks:** menghapus spasi berlebih dan merapikan teks.
5. **Split dan join:** memisahkan teks menjadi daftar kata dan menggabungkannya kembali.
6. **Pencarian kata:** memeriksa keberadaan kata, menghitung kemunculan dengan `count()`, dan mencari posisi dengan `find()`.

## E. Hasil Pengujian Tugas Utama

| No. | Input nama | Input kode kelas | Nama bersih | Kode bersih | Jumlah kata | Inisial | Status |
|---|---|---|---|---|---:|---|---|
| 1 | aan hendrayana | pmat a 2026 | Aan Hendrayana | PMAT-A-2026 | 2 | AH | Berhasil |
| 2 | fATHIYYAH mUTHMAINNAH | kelas b | Fathiyyah Muthmainnah | KELAS-B | 2 | FM | Berhasil |
| 3 | BUDI | pmtk 01 | Budi | PMTK-01 | 1 | B | Berhasil |
| 4 | siti nur aisyah | kelas c | Siti Nur Aisyah | KELAS-C | 3 | SNA | Berhasil |

Keempat pengujian telah dijalankan dan menghasilkan keluaran yang sesuai dengan hasil yang diharapkan.

## F. Kesimpulan dan Refleksi

Melalui praktikum ini, saya mempelajari cara mengolah string menggunakan berbagai method bawaan Python. Saya juga memahami bahwa kombinasi `strip()`, `split()`, `join()`, dan `title()` dapat digunakan untuk menormalisasi data nama, sedangkan `upper()` dan `join()` dapat membantu menyeragamkan kode kelas.

Pengujian dengan variasi huruf kapital dan spasi berlebih menunjukkan bahwa program dapat menghasilkan format data yang konsisten. Praktikum ini membantu saya memahami penggunaan fungsi, pengolahan teks, dan pengujian program secara bertahap.