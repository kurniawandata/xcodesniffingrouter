# xcodesniffingrouter

X-code Sniffing Router for Ubuntu 16.04 LTS v2.92 Stable (Support web managemen)
------------------------------------------

Released 28/04/2020
-------------------

![alt text](http://xcode.or.id/04_small-logo.png)

Aplikasi untuk membangun NAT, DHCP Server, access log, cache web, port forwarding, VPN Server secara cepat termasuk konfigurasinya, pada versi X-code sniffing router ditambahkan fitur-fitur sniffing username dan password. Mendukung SSLStripping.

Aplikasi ini khusus untuk fitur sniffing dibuat untuk tujuan riset dan belajar, bukan untuk diimplementasikan mengambil username dan password orang lain.

Saya tidak bertanggung jawab segala hal yang diakibatkan program ini.

SSLStrip
---------
Sumber SSLStrip : https://github.com/moxie0/sslstrip 


Cara menggunakan :
------------------

Pastikan di CPU anda sudah terinstall Ubuntu Server 16.04 dengan 2 LAN Card jika ingin dibangun router. Jika server aja, cukup 1 LAN Card.

Jika belum diinstall bisa download ISO-nya 

Dari release ubuntu

- https://releases.ubuntu.com/16.04/ubuntu-16.04.6-server-i386.iso (32 bit)

- https://releases.ubuntu.com/16.04/ubuntu-16.04.7-server-amd64.iso (64 bit)

Perintah instalasi dan menjalankannya
-------------------------------------

- Download : 

- git clone https://github.com/kurniawandata/xcodesniffingrouter

- cd xcodesniffingrouter

- dpkg -i xcodesniffingrouter.deb

- cd /xcodepandawa2

- ./xcoderouter (lakukan instalasi X-code pandawa router, lalu install NAT melalui program, lalu jika ingin langsung aktifkan sniffing pilih nomor 20 yaitu "Pindah ke X-code Sniffing Router").

- Untuk akses web managemen : https://ip addresss:1500


Video cara penggunaan serta demonya
----------------------
- https://drive.google.com/file/d/1t1RmGux-Yu0pVaMNqPQtkrVXeWyvJvbJ/view


Progammer 
---------

- Programmer : Kurniawan. xcode.or.id. E-mail : kurniawanajazenfone@gmail.com


License
------- 

- GNU General Public v3 License


Donasi :
--------
Donasi untuk Kurniawan telah berkontribusi sebagai pengembang free software & open source dalam bentuk gopay<br />

 <img src="https://xcode.co.id/qrcode5.png" alt="gopay"> <br />
 Gopay (Customer)

