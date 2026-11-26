CLEANOVA — Laundry Online
==========================

REQUIREMENT
- XAMPP
- Apache
- MySQL
- PHP 8.2+ / 8.3

INSTALASI
1. Salin folder cleanova ke:
   C:\xampp\htdocs\cleanova

2. Jalankan Apache dan MySQL dari XAMPP.

3. Buka phpMyAdmin:
   http://localhost/phpmyadmin

4. Import:
   database/cleanova.sql

5. Buka:
   http://localhost/cleanova/

ADMIN
1. Setelah database di-import, buka:
   http://localhost/cleanova/database/create_admin.php

2. Login:
   http://localhost/cleanova/admin/login.php

   Username: admin
   Password: cleanova123

3. SEGERA hapus file:
   database/create_admin.php

Catatan:
- Ganti password admin pada tahap security/authentication berikutnya.
- Nomor WhatsApp dan jam operasional pada halaman kontak masih placeholder.
- Versi ini adalah MVP awal dan akan dikembangkan bertahap.
