# Composer autoloder

## Description

Autoloader tidak meng-include `folder/Kumis.php` dan `folder/Lembu.php` secara otomatis.

Tapi bila file `index.php` menggunakan `new Kumis`, baru saat itu file `folder/Kumis.php` di-load.

## Usage

1. `composer dump-autoload`

2. `php index.php`
