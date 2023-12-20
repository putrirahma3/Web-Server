# Web-Server
Server web adalah serangkaian perangkat yang membantu pengguna  mengakses situs web dengan lebih mudah. Server web mencakup perangkat keras dan perangkat lunak yang menerima permintaan HTTP/HTTPS dari klien atau browser web. Web server kemudian mengirimkan respon  permintaan ke klien dalam bentuk halaman web.

Tools yangdigunakan:
1. Ubuntu server
2. apache
3. ssh
4. php
5. ftp (FileZilla)

INSTALLASI 
1. Install apache2
``
sudo apt upddate
sudo apt install apache2
``sh
3. menjalankan apache
``
sudo systemctl start apache2
sudo systemctl enable apache2
``sh
4. Mengecek apache
``
http://alamat_IP_server/
``sh

1. Install php
``
sudo apt update
sudo apt install php
sudo apt install php-mysql
sudo systemctl restart apache2
``sh
2. Menambahkan direktori
``
sudo nano /var/www/html/info.php
``sh
ganti dengan :
``
<?php
phpinfo();
?>
``sh

1. Install ssh
``
sudo apt update
sudo apt install open-ssh-server
sudo systemctl status ssh
``sh
2. Restart ssh
``
sudo systemctl restart ssh
``sh
