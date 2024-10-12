# install-apache
Instalasi aplikasi web server root@smkmanusa:~# apt instal apache2

root@smkmanusa:~# nano /etc/apache2/sites-available/000-default.conf

ServerAdmin mail.smkmanusa.sch.id

DocumentRoot /var/lib/roundcube

root@smkmanusa:~# layanan apache2 restart

Pengujian Web server dari sisi Client Windows:Buka web browser dan ketik: 172.30.1.1
