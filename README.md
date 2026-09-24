# tes_deploy

Kerangka aplikasi Laravel kosong dengan versi yang diminta:

- PHP 7.4.22
- Laravel Framework 8.83.27
- MariaDB 10.4.6

## Menjalankan

Siapkan dependensi Composer, lalu jalankan `docker compose up --build`. Aplikasi tersedia di http://localhost:8000. MariaDB tersedia dari komputer lokal di port 3307; dari container Laravel gunakan host `db` dan port 3306.

Composer memblokir versi Laravel yang diminta karena advisori keamanan. Berkas dependensi belum dikunci atau dipasang sampai keputusan tentang blokir tersebut diberikan.
