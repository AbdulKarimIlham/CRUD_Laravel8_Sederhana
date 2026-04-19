# 🍽️ CRUD Makanan Khas Indonesia (Laravel 8)

Project ini merupakan aplikasi sederhana berbasis **Laravel 8** yang digunakan untuk mengelola data makanan khas Indonesia dengan fitur CRUD (Create, Read, Update, Delete).

---

## 🚀 Fitur Utama

* ✅ Tambah Data Makanan
* ✅ Lihat Data Makanan
* ✅ Edit Data
* ✅ Hapus Data

---

## 🧱 Struktur Data

Tabel: `makanans`

| Field        | Tipe      |
| ------------ | --------- |
| id           | bigint    |
| nama_makanan | string    |
| provinsi     | string    |
| daerah       | string    |
| created_at   | timestamp |
| updated_at   | timestamp |

---

## ⚙️ Cara Menjalankan Project

### 1. Clone / Copy Project

```bash
git clone (url-repository)
cd nama-project
```

### 2. Install Dependency

```bash
composer install
```

### 3. Copy File .env

```bash
cp .env.example .env
```

### 4. Setting Database di .env

```env
DB_DATABASE=nama_database
DB_USERNAME=root
DB_PASSWORD=
```

### 5. Generate Key

```bash
php artisan key:generate
```

### 6. Migrate Database

```bash
php artisan migrate
```

### 7. Jalankan Server

```bash
php artisan serve
```

### 8. Akses di Browser

```
http://127.0.0.1:8000/makanan
```

---

## 🛠️ Teknologi yang Digunakan

* Laravel 8
* PHP
* MySQL
* Blade Template

---

## 👨‍💻 Author

Dibuat oleh: **Aan**

---

## 📌 Catatan

Project ini dibuat untuk keperluan pembelajaran CRUD menggunakan Laravel.
