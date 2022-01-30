# Introduction to DevOps

DevOps : Praktik dalam sebuah pengembangan Software yang Menghubungkan antara tim Developer dengan tim Operation agar terotomatisasi hingga tahap rilis publik.

Tujuan : Agar proses deploy perubahan / update suatu software menjadi terotomatisasi dan mencegah apabila suatu code yg dibuat tim developer crash dengan software lama.

## Alur DevOps & Konsep CI/CD

<p align="center"><img src="../week-1/assets/DevOps.png"></p>

- Alur dimulai dari DevOps membuat rancangan perubahan / update yang diserahkan ke Developer (Programmer)
- Developer membuat code
- Debeloper memberikan code ke DevOps
- DevOps melakukan release. jika ada masalah maka dikembalikan ke Developer untuk diperbaiki
- Jika tidak DevOps melakukan deploy ke publik
- kemudian DevOps memantau software

Continuous integration (CI) : pengintegrasian kode ke dalam repositori kode kemudian menjalankan pengujian secara otomatis.

continuous deployment (CD) : adalah praktik yang dilakukan setelah proses CI dan seluruh kode berhasil terintegrasi.

## Virtualization & Container

- Virtualization : Suatu metode untuk membuat Virtual Machine untuk minginstal berbagai Operation System dalam satu hardware dengan spesifikasi yang ditentukan diawal pembuatan.

<p align="center"><img src="../week-1/assets/Virtual Machine.png"></p>

- Container : Suatu metode untuk membuka berbagai aplikasi sesuai dengan spesifikasi kebutuhan aplikasi tersebut

<p align="center"><img src="../week-1/assets/Container.png"></p>

## Cloud Computing

Cloud Computing adalah metode penyampaian berbagai layanan melalui internet. Seorang DevOps harus paham mengenai Cloud Computing karena berhubungan dengan penyimpanan secara publik agar bisa diakses oleh user dimana saja dan kapan saja.

Cloud Computing memiliki 3 layanan : 

<p align="center"><img src="../week-1/assets/Cloud-computing.jpg"></p>

1.IaaS (Infrastructure as a Service) : layanan cloud yang pada dasarnya merupakan server fisik dan virtual server. Penyedia layanan IaaS menyediakan resource cloud seperti server, jaringan, storage dan ruang data center.

2.PaaS (Platform as a Service) : layanan Cloud yang disediakan dalam bentuk platform dan dapat dimanfaatkan pengguna untuk membuat aplikasi di atasnya. PaaS memberikan framework bagi developer yang dapat mereka bangun dan gunakan untuk membuat aplikasi yang telah disesuaikan.

3.Saas (Software as a Service) : Sebuah perangkat lunak yang dijadikan sebagai layanan yang bersifat online, SaaS ini juga disebut sebagai layanan aplikasi Cloud.

