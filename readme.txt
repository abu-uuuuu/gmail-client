���������� �� ���������



1. �������� � ���������� ������:

smartresponder_db.7z  - ��

smart-responder.7z    - ���������



2. �������� �� �� ������� smartresponder.sql 



3. �������� ������������ smartresponder � ������� smartresponder 
(��� ������� ��������� ���������� � �� � ����� config.php)



4. �������� ����������� ����. ������ ������ �� httpd-vhosts.conf


<VirtualHost *:80\>

    DocumentRoot "D:\www\vhosts\smart-responder"

    ServerName smart-responder

</VirtualHost\>



�������� ��� ����� �������� � ��� ������������ �����.

5. � php.ini ��������� ����������: pdo � imap


extension=php_pdo_mysql.dll

extension=php_imap.dll
