# MVC PHP Native - Data Mahasiswa

Aplikasi CRUD sederhana untuk mempelajari pola Model-View-Controller pada PHP Native.

## Kebutuhan
- PHP 8.0 atau lebih baru
- MySQL/MariaDB
- Web server lokal seperti XAMPP atau Laragon
- Git

## Instalasi
1. Clone atau salin project ke folder web server.
2. Import `database/kampus.sql`.
3. Sesuaikan koneksi pada `config/database.php`.
4. Buka `http://localhost/mvc-native/public/index.php`.

## Struktur MVC
- `app/models/` : akses dan operasi data.
- `app/controllers/` : alur request dan pemanggilan Model/View.
- `app/views/` : tampilan HTML.
- `config/` : konfigurasi koneksi database.
- `database/` : skema dan data awal SQL.
- `public/` : entry point aplikasi.

## Fitur
- Menampilkan data mahasiswa
- Menambah data mahasiswa
- Mengubah data mahasiswa
- Menghapus data mahasiswa

## Histori Git
### git log --oneline --graph --decorate
PS D:\laragon\www\mvc-native> git log --oneline --graph --decorate
* d7eef3b (HEAD -> main, origin/main) docs: add installation and MVC documentation
* b4b54d5 feat: add complete CRUD routing
* 0810e34 feat: add complete student CRUD views
* 550d04b feat: add complete student CRUD controller
* 233aa27 feat: add complete student CRUD model
* f686b5a feat: add PDO database connection
* ff030b7 feat: add student database schema and seed data
* 6b370ef chore: initialize mvc php native project