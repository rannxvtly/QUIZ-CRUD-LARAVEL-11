# 🎓 CRUD Data Mahasiswa - Laravel 11

## 📌 Deskripsi Project

Project ini merupakan aplikasi CRUD (Create, Read, Update, Delete) sederhana berbasis Laravel 11 dengan studi kasus pengelolaan data mahasiswa.
Aplikasi ini dibuat untuk latihan dasar framework Laravel menggunakan konsep MVC (Model View Controller), Migration, Seeder, Routing, dan Blade Template.

---

## ✨ Fitur

* Menampilkan data mahasiswa
* Menambahkan data mahasiswa
* Mengedit data mahasiswa
* Menghapus data mahasiswa
* Seeder data dummy mahasiswa
* Menggunakan Laravel 11
* Menggunakan Blade Template

---

## 🛠️ Teknologi yang Digunakan

* Laravel 11
* PHP
* MySQL
* Blade Template
* HTML

---

## 📂 Struktur Folder Penting

```bash
app/
├── Http/Controllers/
│   └── MahasiswaController.php
│
├── Models/
│   └── Mahasiswa.php

database/
├── migrations/
├── seeders/
│   ├── DatabaseSeeder.php
│   └── MahasiswaSeeder.php

resources/
└── views/
    └── mahasiswa/
        ├── index.blade.php
        ├── create.blade.php
        └── edit.blade.php

routes/
└── web.php
```

---

## ⚙️ Cara Menjalankan Project

### 1. Clone Repository

```bash
git clone https://github.com/username/kuis.git
```

---

### 2. Masuk ke Folder Project

```bash
cd kuis
```

---

### 3. Install Dependency

```bash
composer install
```

---

### 4. Copy File Environment

```bash
cp .env.example .env
```

---

### 5. Generate Key

```bash
php artisan key:generate
```

---

### 6. Konfigurasi Database

Buka file `.env`

```env
DB_DATABASE=kuis
DB_USERNAME=root
DB_PASSWORD=
```

---

### 7. Jalankan Migration dan Seeder

```bash
php artisan migrate --seed
```

---

### 8. Jalankan Laravel

```bash
php artisan serve
```

---

## 🌐 URL Project

```bash
http://127.0.0.1:8000/mahasiswa
```

---

## 👨‍💻 Author

Kirana Larasati Dewi

---

## 📖 Tujuan Project

Project ini dibuat untuk:

* memenuhi tugas praktikum Laravel
* mempelajari CRUD Laravel 11
* memahami konsep MVC
* memahami Migration dan Seeder
* latihan penggunaan routing dan blade template
