# Apa itu Routing Ospf,Ip Dhcp,Ip Address Dan Antar Jaringan Lan 😀
1. Routing OSPF
OSPF (Open Shortest Path First) adalah metode routing dinamis yang digunakan router untuk saling bertukar informasi jalur jaringan secara otomatis.

Contoh pada praktikmu:
- R1 terhubung ke R2.
- R1 terhubung ke R3.
- OSPF membantu R1, R2, dan R3 mengenali jaringan satu sama lain.
Intinya: OSPF memudahkan router menentukan jalur untuk mengirim data.
2. IP Address
IP Address adalah alamat unik yang diberikan kepada perangkat agar bisa berkomunikasi dalam jaringan.

Contoh:
- R1: 172.12.15.1
- R2: 172.12.15.2
- PC1: 192.168.1.254
- PC2: 192.168.2.254
Intinya: IP Address adalah alamat perangkat dalam jaringan.
3. DHCP
DHCP (Dynamic Host Configuration Protocol) adalah layanan yang memberikan konfigurasi IP secara otomatis kepada perangkat seperti komputer.

Contoh pada praktikmu:
- R2 memberikan IP otomatis kepada PC1.
- R3 memberikan IP otomatis kepada PC2.
PC tidak perlu mengatur IP secara manual.

Intinya: DHCP memudahkan pemberian IP secara otomatis.
4. Antarjaringan LAN
LAN (Local Area Network) adalah jaringan lokal yang menghubungkan beberapa perangkat dalam area tertentu.

Contoh pada praktikmu:
- LAN 1 menggunakan jaringan 192.168.1.0/24.
- LAN 2 menggunakan jaringan 192.168.2.0/24.
Kedua LAN tersebut dihubungkan melalui router MikroTik sehingga PC1 dan PC2 bisa saling berkomunikasi.

Intinya: Antarjaringan LAN berarti menghubungkan dua atau lebih jaringan lokal yang berbeda.


# TOPOLOGI 🎉🎉
<img width="596" height="369" alt="image" src="https://github.com/user-attachments/assets/41b5314d-d3f8-40be-a8f4-6745d1a1d6c7" />

# PERANGKAT YANG DIGUNAKAN 🛠🛠
GNSV3M
ORACLE VIRTUALBOX
WINBOX
ROUTER 1
ROUTER 2
ROUTER 3
CLOUD
PC 1
PC 2

# CARA NGETESTNYA
jangan lupa kalian test yah dengan antar router
R1 
/ping 172.12.15.2
/ping 170.12.30.2
R2
/ping 172.12.15.1
/ping 170.12.30.2
R3
/ping 170.12.30.1
/ping 172.12.15.2
ping antarouter ini untuk memastikan bahwa koneksi antarrouter berjalan dengan baik dan jika sudah lalu kalian masukkan ip dhcp di pc
PC 1
ip dhcp
PC 2
ip dhcp
dan kalian bakal mendapatkan ip dhcpnya
langsung kalian disitu ping
/ping 192.168.1.apalah
/ping 192.168.2.apalah


#KONFIGURASI NOTES
