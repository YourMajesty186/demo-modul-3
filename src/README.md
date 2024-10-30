# Kalkulator Hitung Luas

Proyek ini adalah aplikasi sederhana untuk menghitung luas berbagai bentuk geometri dasar, yaitu persegi, persegi panjang, dan segitiga. Aplikasi ini menggunakan struktur kelas terpisah untuk setiap bentuk geometris dan memanfaatkan refactoring agar kode lebih terstruktur dan mudah dikelola.

## Fitur Aplikasi
1. **Hitung Luas Persegi**
2. **Hitung Luas Persegi Panjang**
3. **Hitung Luas Segitiga**

## Struktur Kelas

### 1. `MainR`
- Ini adalah kelas utama (`MainR`) yang menyediakan antarmuka interaktif bagi pengguna untuk memilih jenis perhitungan luas yang diinginkan.
- Kelas ini menggunakan `Scanner` untuk mengambil input dari pengguna dan mengelola logika pilihan bentuk geometri.

### 2. `Tugas4R`
- Kelas `Tugas4R` mengandung metode untuk menghitung luas setiap bentuk geometri yang diterima sebagai parameter.
- Metode-metode yang ada:
    - `hitungPersegi`: Menghitung luas persegi.
    - `hitungPersegiPanjang`: Menghitung luas persegi panjang.
    - `hitungSegitiga`: Menghitung luas segitiga.

### 3. Kelas-kelas Bentuk Geometri
- Kelas `persegi`, `persegipanjang`, dan `segitiga` adalah kelas model yang mewakili bentuk-bentuk geometri. Setiap kelas ini berisi atribut-atribut (seperti `sisi` untuk persegi atau `alas` dan `tinggi` untuk segitiga) yang diperlukan untuk menghitung luas.


