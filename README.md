# EasyBackEndPHP
*A lightweight and customizable Object-Oriented PHP library for backend development.*

## Overview
EasyBackEndPHP simplifies backend development by providing built-in support for:
✅ SQL Queries  
✅ FTP Connections  
✅ Image Size Modifications  
✅ Session Management  
✅ String Manipulation  

## Installation
1. Clone or download the repository  
   ```bash
   git clone https://github.com/llogaricasas/EasyBackEndPHP.git
   ```
2. Include the library in your PHP file  
   ```php
   require 'EasyBackEndPHP.php';
   ```

## Usage
Initialize the library and start using its features:  
```php
$library = new EasyBackEndPHP();

$CharEncoding = $library->CharEncoding($string);
$FTP = $library->FTP($host, $user, $password);
$ImageEditor = $library->ImageEditor($filename);
$MySQL = $library->MySQL($host, $database, $user, $password);
$Session = $library->Session($lifetime, $path, $domain, $secure, $http_only);
$StringGenerator = $library->StringGenerator($length);
```

## Author
EasyBackEndPHP is maintained by **[Llogari Casas](https://www.llogaricasas.com)**  
