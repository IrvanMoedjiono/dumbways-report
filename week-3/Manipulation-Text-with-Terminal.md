## Manipulation Text with Terminal

- cat : untuk melihat teks dalam file
- cat > (nama-file) : Untuk membuat sekaligus menulis teks dalam file
- CTRL+C : untuk menghentikan perintah pada terminal

<p align="center"><img src="../week-3/assets/Manipulation-Text-with-Terminal/1.png"></p>

- echo "(teks)" > (nama-file)  : untuk me-replace teks dalam file
- echo "(teks)" >> (nama-file) : untuk menambahkan teks di baris baru dalam file

<p align="center"><img src="../week-3/assets/Manipulation-Text-with-Terminal/2.png"></p>

- sed -i 's/(teks-yg-ingin-diganti)/(teks-pengganti)/g' (nama-file)

<p align="center"><img src="../week-3/assets/Manipulation-Text-with-Terminal/3.png"></p>

- grep (teks-yg-ingin-dicari) (nama-file) : untuk mencari teks dalam file
- grep -c (teks-yg-ingin-dihitung) (nama-file) : untuk menghitung berapa banyak teks yg digunakan dalam satu file

<p align="center"><img src="../week-3/assets/Manipulation-Text-with-Terminal/4.png"></p>

-sort (nama-file) : untuk mengurutkan teks per baris dalam dalam file secara ascending

<p align="center"><img src="../week-3/assets/Manipulation-Text-with-Terminal/5.png"></p>

-sort -r (nama-file) : untuk mengurutkan teks per baris dalam dalam file secara descending

<p align="center"><img src="../week-3/assets/Manipulation-Text-with-Terminal/6.png"></p>
