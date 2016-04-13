# gmail-client

Инструкция по установке

1. Скачайте и распакуйте архивы:
smartresponder_db.7z  - БД
smart-responder.7z    - исходники

2. Создайте БД из скрипта smartresponder.sql 

3. Создайте пользователя smartresponder с паролем smartresponder (или задайте параметры соединения с БД в файле config.php)

4. Создайте виртуальный хост. Пример записи из httpd-vhosts.conf
<VirtualHost *:80>
    DocumentRoot "D:\www\vhosts\smart-responder" 
    ServerName smart-responder
</VirtualHost>

5. в php.ini разрешите расширения: pdo и imap
extension=php_pdo_mysql.dll
extension=php_imap.dll
