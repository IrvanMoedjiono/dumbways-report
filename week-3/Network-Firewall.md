## Network Firewall

<p align="justify">Network Firewall adalah sistem keamanan jaringan komputer yang bertujuan mengontrol semua akses keluar/masuk suatu jaringan berdasarkan aturan yang telah ditetapkan. Network Firewall memiliki fungsi melindungi data/system dari serangan hacker dan mampu memblok konten yang tidak diinginkan.</p>

- `sudo apt install ufw` : untuk menginstall ufw

<p align="center"><img src="../week-3/assets/Network-Firewall/1.png"></p>

- `sudo ufw enable` : untuk mengaktifkan firewall

<p align="center"><img src="../week-3/assets/Network-Firewall/10.png"></p>

- `sudo ufw disable` : untuk menonaktifkan filrewall

<p align="center"><img src="../week-3/assets/Network-Firewall/13.png"></p>

- `sudo ufw default deny incoming`  : untuk melarang semua akses yg masuk
- `sudo ufw default allow outgoing` : untuk mengizinkan semua akses yg masuk

<p align="center"><img src="../week-3/assets/Network-Firewall/2.png"></p>

- `sudo ufw app list` : untuk menampilkan daftar aplikasi yang dapat menggunakan firewall
- `sudo ufw allow "Nginx Full"` : untuk memberi akses full nginx

<p align="center"><img src="../week-3/assets/Network-Firewall/3.png"></p>

<p align="center"><img src="../week-3/assets/Network-Firewall/4.png"></p>

- `sudo ufw allow 22` : untuk mengizinkan akses pada port 22

<p align="center"><img src="../week-3/assets/Network-Firewall/5.png"></p>

- `sudo ufw deny 80` : untuk melarang akses pada port 80

<p align="center"><img src="../week-3/assets/Network-Firewall/8.png"></p>

- `sudo ufw allow 22/tcp` : untuk mengizinkan akses port 22 dengan koneksi TCP

<p align="center"><img src="../week-3/assets/Network-Firewall/6.png"></p>

- `sudo ufw allow 22/udp` : untuk mengizinkan akses port 22 dengan koneksi UDP

<p align="center"><img src="../week-3/assets/Network-Firewall/7.png"></p>

- `sudo ufw status` : untuk menampilkan status firewall

<p align="center"><img src="../week-3/assets/Network-Firewall/9.png"></p>

- `sudo ufw verbose` : untuk menampilkan status dan daftar perintah firewall

<p align="center"><img src="../week-3/assets/Network-Firewall/11.png"></p>

- `sudo ufw delete deny/allow nama-port` : untuk menghapus aturan yg dibuat

<p align="center"><img src="../week-3/assets/Network-Firewall/12.png"></p>
