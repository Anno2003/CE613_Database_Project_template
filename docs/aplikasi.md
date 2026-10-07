---
title: Dokumentasi Aplikasi
nav_order: 2
---

# Dokumentasi Aplikasi

Halaman ini berisi cara menyiapkan dan menjalankan aplikasi. Penjelasan desain dan analisis ada di [Laporan Project](index.md).

## 1. Ringkasan

Satu paragraf: aplikasi ini untuk apa dan siapa penggunanya.

**Tech stack:**

| Komponen | Teknologi | Versi |
|---|---|---|
| Database | | |
| Backend | | |
| Frontend | | |

## 2. Prasyarat

-
-

## 3. Instalasi

### 3.1 Clone repository

```bash
git clone <url-repo>
cd <nama-folder>
```

### 3.2 Setup database

```bash
# Buat database
# Jalankan skema (DDL)
# Jalankan data contoh (seed)
```

Berkas SQL: `database/schema.sql`, `database/seed.sql`

### 3.3 Konfigurasi environment

Salin `.env.example` menjadi `.env`, lalu isi:

| Variabel | Keterangan | Contoh |
|---|---|---|
| DB_HOST | | localhost |
| DB_NAME | | |
| DB_USER | | |
| DB_PASSWORD | | (jangan di-commit) |

> Jangan pernah commit `.env` atau kredensial asli ke repository.

### 3.4 Install dependensi

```bash
```

## 4. Menjalankan Aplikasi

```bash
```

Aplikasi dapat diakses di: `http://localhost:<port>`

## 5. Akun Demo

| Peran | Username | Password |
|---|---|---|
| Admin | | |
| Pengguna | | |

## 6. Panduan Penggunaan Singkat

Alur utama untuk setiap peran, beserta tangkapan layar.

1.
2.

## 7. Struktur Proyek

```
.
├── database/
├── src/
└── README.md
```

## 8. Pemecahan Masalah

| Masalah | Penyebab Umum | Solusi |
|---|---|---|
| | | |

## 9. Catatan

- Seluruh data contoh bersifat fiktif.
- Batasan yang diketahui:
