# Composer autoloder

## Description

Autoloader tidak nge-load file `folder/Kumis.php` dan `folder/Lembu.php` pada saat kita include `vendor/autoload.php`.

Tapi bila file `index.php` menggunakan `new Kumis`, baru saat itu file `folder/Kumis.php` di-load.

Kesimpulannya autoloader hanya nge-load class pada saat dipanggil.

## Usage

1. `composer dump-autoload`

2. `php index.php`
