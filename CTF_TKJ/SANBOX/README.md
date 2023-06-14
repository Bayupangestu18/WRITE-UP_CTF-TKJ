## shell injection - SANBOX

# Attached
![shell](https://github.com/Bayupangestu18/WRITE-UP_CTF-TKJ/assets/119099396/0680c8b9-27a3-4a9d-b168-9afc86047f4e)

Di soal ini kita di beri ip dan port untuk koneksi ke server netcat.

# Solutions
![sh2](https://github.com/Bayupangestu18/WRITE-UP_CTF-TKJ/assets/119099396/ac1654dc-9ffa-417c-b40e-aa475614e1e5)
Di saat kita mengkoneksikan dengan nc kita tampilannya seperti ini saat kita masukkan teks atau angka maka dia akan mengconvert jadi hex jadi kita harus mencari cara agar teks kita tidak di convert menjadi teks kita bisa membaca script python yang di kasih jadi kita bisa tau vuln nya berada dimana vuln nya ini adalah command injection jadi kita harus mencari contoh payload command injection saya menggunakan payload `'; ls ;'`. Lalu kita pilih bagian hex dan kita akan melihat sebuah file flag.txt kemudian kita tinggal membaca file nya.

![sh3](https://github.com/Bayupangestu18/WRITE-UP_CTF-TKJ/assets/119099396/e4c4cdea-6470-4155-9655-90a7ea7b2a5b)

lalu kita bisa menggunakan perintah cat untuk membaca isi dari file flag.txt
![sh3](https://github.com/Bayupangestu18/WRITE-UP_CTF-TKJ/assets/119099396/e4c4cdea-6470-4155-9655-90a7ea7b2a5b)

