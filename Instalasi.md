## Minimal Sistem dan Pengetahuan Dasar
[I'm an inline-style link](https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/5.6.28/xampp-win32-5.6.28-1-VC11-installer.exe/download)
- Web Server:
  - [Download XAMPP] (https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/5.6.28/xampp-win32-5.6.28-1-VC11-installer.exe/download) 
- Database that laravel supports, actually can be:
  - Bawaan XAMPP yang tadi kamu sudah download, jangan lupa install dulu. Kalo udah ada versi lain, rename yang versi lama.
- PHP
  - [Cara setting path php di Windows] (https://www.petanikode.com/php-cmd)
- Composer
  - [Cara Install Composer di Windows] (https://jagowebdev.com/cara-install-menjalankan-composer-di-windows)
- Laravel 5.4
  - Install
 ```php
 $ composer create-project --prefer-dist laravel/laravel blog "5.4.*"
 ```
  - Beres install laravel, masih di folder yang sama. Coba jalankan perintah 
 ```php
 $ php artisan serve
 ```
