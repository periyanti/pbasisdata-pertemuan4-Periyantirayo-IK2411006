# 📘 README.md


 **Nama** : Periyanti Rayo
 
 **NIM**  : IK2411006



Repository ini berisi tugas praktikum SQL yang membahas pembuatan database, tabel, serta penggunaan logika pemrograman pada MySQL seperti **IF ELSE**, **CASE**, dan **Stored Procedure**.

### 🗄️ Database yang digunakan

```sql
db_pertemuan4
```


### 1️⃣ Procedure `cek_status_stok`

Procedure ini berfungsi untuk menentukan status stok barang berdasarkan jumlah stok.

📌 Kategori:

* 0 → Habis
* 1–5 → Hampir Habis
* 6–20 → Tersedia
* > 20 → Stok Aman

Menggunakan struktur **IF ELSEIF**.

---

### 2️⃣ Tabel `produk` dan CASE

Membuat tabel `produk` dengan field:

* `id_produk`
* `nama_produk`
* `stok`

Kemudian menggunakan **CASE** untuk menampilkan status stok secara otomatis.

---

### 3️⃣ Procedure `hitung_diskon`

Procedure ini digunakan untuk menghitung diskon berdasarkan total belanja.

💰 Ketentuan diskon:

* ≥ 1.000.000 → 15%
* ≥ 500.000 → 10%
* ≥ 250.000 → 5%
* < 250.000 → 0%

📤 Output:

* total_belanja
* diskon
* jumlah_diskon
* total_bayar

---

### 4️⃣ Procedure `cek_predikat_mahasiswa`

Procedure ini menentukan:

* predikat nilai mahasiswa
* status kelulusan

🎓 Kategori predikat:

* ≥ 90 → Sangat Memuaskan
* ≥ 80 → Memuaskan
* ≥ 70 → Baik
* ≥ 60 → Cukup
* < 60 → Kurang

📍 Status:

* ≥ 70 → Lulus
* < 70 → Tidak Lulus

---

## ▶️ Cara Menjalankan Script SQL

### 1️⃣ Jalankan MySQL

Gunakan:

* XAMPP (phpMyAdmin)
* MySQL Command Line

---

### 2️⃣ Import File SQL

Jalankan file:

```sql
program.3sql.sql
```

Menggunakan command line:

```sql
SOURCE lokasi_file/program.3sql.sql;
```

Contoh:

```sql
SOURCE C:/xampp/mysql/program.3sql.sql;
```

---

### 3️⃣ Database Otomatis Dibuat

Script akan membuat dan menggunakan database:

```sql
db_pertemuan4
```

---

### 4️⃣ Menjalankan Procedure

Contoh penggunaan:

```sql
CALL cek_status_stok(10);
CALL hitung_diskon(700000);
CALL cek_predikat_mahasiswa(85);










## ✨ Penutup

Dokumen ini dibuat sebagai panduan penggunaan repository serta ringkasan dari tugas praktikum SQL yang telah dikerjakan.

---
