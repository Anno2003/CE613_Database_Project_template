---
title: Laporan Project
nav_order: 1
---
<!-- Comment HTML seperti ini tidak tampil di halaman web, 
tapi bisa dhapus agar bersih. -->

**Kelompok:** ...  
**Organisasi/Bisnis:** ...  

## Anggota Kelompok
 
| Nama | NIM |
|---|---|
| | |

---

## 1. Pendahuluan
### 1.1 Latar Belakang
<!-- Penjelasan bisnis/organisasi apa yang dijadikan project -->

### 1.2 Rumusan Masalah

### 1.3 Tujuan

### 1.4 Scope
<!-- list apa yang termasuk dan tidak termasuk kedalam project -->

## 2. Pengumpulan Data
<!-- Ringkasan proses wawncara, kapan dan dimana dilakukan, apa saja yang ditemukan, -->
<!-- beserta dengan dokumentasinya. -->

## 3. Perancangan
### 3.1 Business Rule

<!-- Business rule ditulis disini dalam bentuk tabel, No. bisa diganti dengan id
     jika business rule diidentifikasi dengan id -->
<!-- Business rule harus spesifik dan bisa diuji (bisa dijadikan constraint/trigger/query). -->
<!-- Contoh rule kurang baik: "Anggota dapat meminjam buku." -->
<!-- Contoh rule baik: "Satu anggota maksimal meminjam 3 buku aktif." -->
<!-- Kolom Implikasi menjelaskan BAGAIMANA rule diterapkan di database: -->
<!-- constraint, trigger, unique key, dsb — bukan mengulang rule-nya. -->

| No. | Business Rule | Implikasi ke Database |
|-----|---------------|-----------------------|
| 1   | Satu anggota dapat meminjam maksimal 3 buku sekaligus. | Constraint jumlah pinjaman aktif per anggota (dengan trigger/check). |

### 3.2 Skema Database
<!-- Entity Relationship Diagram beserta penjelasannya  -->
<!-- Penjelasan implementasi database,  -->
<!-- Normalisasi(kalau ada) yang digunakan pada database, mulai dari data awal hingga 3NF.  -->

## 4. Implementasi Database
### 4.1 DDL dan sample data 
<!-- sertakan snippet ddl atau link ke file sql yang digunakan untuk membuat database, -->
<!-- data sample harus fiktif & tidak mengandung informasi sensistif. -->

### 4.2 Stored Procedures & Triggers
<!-- Penjelasan stored procedure & trigger yang digunakan dalam database -->

### 4.3 Query 
<!-- Query penting yang mendukung kebutuhan Organisasi beserta contoh hasil. -->

### 4.4 Pengujian
<!-- Uji setiap business rule yang diimplementasikan sebagai constraint/trigger (dari 3.1). -->
<!-- Untuk setiap pengujian, sertakan: -->
<!-- 1. Business rule yang diuji (cocokkan dengan bab sebelumnya  menggunakan nomor, id atau tulis langsung)-->
<!-- 2. Skenario/langkah pengujian (query atau urutan query) -->
<!-- 3. Screenshot hasil aktual, dan kesimpulan (berhasil/gagal sesuai ekspektasi) -->
<!-- Minimal satu skenario negatif: tunjukkan rule MENOLAK input yang melanggar, -->
<!-- bukan hanya query yang mengembalikan hasil benar. -->
<!-- Format bebas (tabel, daftar, atau per-skenario), yang penting ketiga poin diatas ada. -->

---
 
## 5. Evaluasi 
 
### 5.1 Kendala dan Penyelesaian
 
### 5.2 Keterbatasan dan Pengembangan Lanjutan
 
---
 
## 6. Pembagian Tugas
 
| Anggota | Tanggung Jawab | 
|---|---|
| | |
