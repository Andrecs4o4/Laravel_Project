# Website Inventori

Aplikasi inventaris barang sekolah menggunakan Framework Laravel 8.

(Cloned from [Andre Christian Surbakti/inven-bs](https://github.com/Andrecs4o4/Laravel_Project) with some modifications based on my requirement, please refer there for official update and the newest change)

### Prasyarat

Berikut beberapa hal yang perlu diinstal terlebih dahulu:

-   Composer (https://getcomposer.org/)
-   PHP 7.2.x
-   MySQL 14.5.x
-   XAMPP

Jika Anda menggunakan XAMPP, untuk PHP dan MySQL sudah menjadi 1 (bundle) didalam aplikasi XAMPP

### Fitur

-   CRUD Barang
-   Import/export excel barang
-   Print
-   CRUD BOS (Bantuan Operasional Sekolah)
-   CRUD Ruangan


### Langkah-langkah instalasi

-   Clone repository ini

```
https://github.com/mrizkimaulidan/inven-bs.git
```

```
git@github.com:mrizkimaulidan/inven-bs.git
```

-   Install seluruh packages yang dibutuhkan

```
composer install
```

-   Siapkan database dan atur file .env sesuai dengan konfigurasi Anda
-   Jika sudah, migrate seluruh migrasi dan seeding data

```
php artisan migrate --seed
```

-   Jalankan local server

```
php artisan serve
```

-   User default aplikasi untuk login

```
Email       : admin@mail.com
Password    : admin
```

### Dibuat dengan

-   [Laravel](https://laravel.com) - Web Framework

### Kontribusi

Silahkan request melalui kolom `Pull Requests` jika ingin melakukan kontribusi

### Pembuat

-   **Muhammad Rizki Maulidan** - _Programmer_ - [Andre Christian Surbakti](https://github.com/Andrecs4o4/Laravel_Project)

### Lisensi

Aplikasi ini boleh untuk dibagi dan diubah. Mohon tidak untuk diperjualbelikan!

### Ucapan terima kasih

-   Stackoverflow
-   Google
