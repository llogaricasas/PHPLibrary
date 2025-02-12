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
```

### 1. Character Encoding  
Convert strings to a specific character encoding format.  
```php
$CharEncoding = $library->CharEncoding($string);
```
🔹 *Use case:* Ensures proper text formatting when handling different character sets.  

### 2. FTP Connection  
Connect to an FTP server for file transfers.  
```php
$FTP = $library->FTP($host, $user, $password);
```
🔹 *Use case:* Upload/download files from a remote server.  

### 3. Image Editor  
Modify image sizes and apply changes.  
```php
$ImageEditor = $library->ImageEditor($filename);
```
🔹 *Use case:* Resize images dynamically for web applications.  

### 4. MySQL Database Connection  
Establish a connection to a MySQL database.  
```php
$MySQL = $library->MySQL($host, $database, $user, $password);
```
🔹 *Use case:* Perform SQL queries and manage data efficiently.  

### 5. Session Management  
Handle user sessions securely.  
```php
$Session = $library->Session($lifetime, $path, $domain, $secure, $http_only);
```
🔹 *Use case:* Maintain user authentication and session state.  

### 6. String Generator  
Generate random strings of a specified length.  
```php
$StringGenerator = $library->StringGenerator($length);
```
🔹 *Use case:* Useful for generating unique tokens, passwords, or IDs.  

## Author
EasyBackEndPHP is maintained by **[Llogari Casas](https://www.llogaricasas.com)**  
