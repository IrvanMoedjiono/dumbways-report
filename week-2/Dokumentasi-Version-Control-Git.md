## Dokumentasi Version Control Git

- git --version        : untuk mengecek versi dari git
- sudo apt install git : untuk menginstall git

<p align="center"><img src="../week-2/assets/Version-Control-Git/1.png"></p>

- git config --global user.name "(usernamegithub)" : untuk configurasi username git secara global
- git config --global user.email "(emailgithub)"   : untuk configurasi email git secara global
- git config --list : untuk menampilkan daftar configurasi

<p align="center"><img src="../week-2/assets/Version-Control-Git/2.png"></p>

- git init (namadir) : untuk membuat direktori yang terinisialisasi git (menjadi repositori git)

<p align="center"><img src="../week-2/assets/Version-Control-Git/7.png"></p>

- nano .gitignore : untuk mengasingkan file saat proses push

<p align="center"><img src="../week-2/assets/Version-Control-Git/9.png"></p>

<p align="center"><img src="../week-2/assets/Version-Control-Git/8.png"></p>

- git add .  : untuk menambahkan semua perubahan agar siap dicommit
- git status : untuk melihat status git

<p align="center"><img src="../week-2/assets/Version-Control-Git/10.png"></p>

- git commit -m "(komentar)" : untuk commit file agar siap untuk dipush

<p align="center"><img src="../week-2/assets/Version-Control-Git/11.png"></p>

- git branch -m (namabranch) : untuk membuat branch baru dan pindah kebranch tersebut
- git remote add (namaremote) (ssh-repositori-github) : untuk menambahkan remote repositori
- git push (nama-remote) (nama-branch) : untuk push/upload ke github

<p align="center"><img src="../week-2/assets/Version-Control-Git/13.png"></p>

<p align="center">SSH Remote repositori</p>

<p align="center"><img src="../week-2/assets/Version-Control-Git/12.png"></p>

- git branch (nama-branch) : untuk membuat branch baru tetapi tidak langsung pindah ke branch baru
- git branch -a : untuk melihat daftar branch dan sedang memakai branch apa
- git checkout (nama-branch) : untuk pindah ke branch lain yang disebutkan

<p align="center"><img src="../week-2/assets/Version-Control-Git/16.png"></p>

- git pull (nama-remote) (nama-branch-yg-dicopy) : untuk menyalin suatu branch

<p align="center"><img src="../week-2/assets/Version-Control-Git/18.png"></p>

- git clone (ssh-key-repositori-github) : untuk menyalin dan mengunduuh repositori di github

<p align="center"><img src="../week-2/assets/Version-Control-Git/22.png"></p>

- git branch -d (nama-branch) : untuk menghapus branch lokal
- git push (nama-remote) --delete (nama-branch) : untuk menghapus branch public

<p align="center"><img src="../week-2/assets/Version-Control-Git/24.png"></p>



### Generate SSH key ke Github

- ssh-keygen            : untuk membuat ssh key komputer kita
- ssh -T git@github.com : untuk memeriksa apakah sudah terkoneksi ke github

1. ketik perintah 'ssh-keygen' diterminal untuk membuat dan menyimpan ssh key. Untuk "enter file in which..." dan passphrase bisa diskip dengan tombol enter. Setelah selesai masuk ke direktori .ssh dengan perintah 'cd .ssh'. Lihat ssh key pada file id_rsa.pub dengan perintah 'cat id_rsa.pub' dan copy semua isinya.

<p align="center"><img src="../week-2/assets/Version-Control-Git/3.png"></p>

2. Masuk ke Githib, pilih setting (1), pilih SSH and GPG keys (2), pilih New SSh key (3).

<p align="center"><img src="../week-2/assets/Version-Control-Git/5.png"></p>

3. Masukkan SSH key yang sudah tercopy tadi kedalam kotak biru, lalu isikan nama/title. Setelah selesai klik add SSH key, lalu masukkan password github

<p align="center"><img src="../week-2/assets/Version-Control-Git/6.png"></p>

4. Kembali ke terminal, ketik ssh -T git@github.com untuk memeriksa apakah sudah terkoneksi ke github

<p align="center"><img src="../week-2/assets/Version-Control-Git/4.png"></p>

### Study Case Git Merge on Process Development, Staging, and Production

1. Branch development merupakan ruang kerja bagi developer untuk membuat perubahan, testing, dll. pada branch developer.

<p align="center"><img src="../week-2/assets/Version-Control-Git/25.png"></p>

2. Branch staging merupakan ruang kerja bagi QA untuk menguji code baik manual/otomatis yang dibuat developer di branch development. Untuk membuat branch staging sama dengan branch development dibutuhkan perintah git merge.

<p align="center"><img src="../week-2/assets/Version-Control-Git/26.png"></p>

3. Branch Production merupakan tahap yang siap diluncurkan kepada user/customer. Apabila ada kerusakan sistem bisa dikembalikan ke versi sebelumnya dengan cara merge dari branch staging.
