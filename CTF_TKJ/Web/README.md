# Nice to meet you - Web

## Attached
![INS_1](https://user-images.githubusercontent.com/119099396/229414885-5fd9fbfe-a40e-4702-9a10-2586e7fa5843.png)

Soal web pertama kita di berikan link lalu kita di suruh untuk mencari flag yang di sembunyikan pada web tersebut!!!

## Solutions
![INS_2](https://user-images.githubusercontent.com/119099396/229415597-9b4c5425-ec1a-4d89-8672-ee3a1eeea6e8.png)

Saat kita buka link tersebut hanya tertera kata `The flag is not here... ` flag tidak berada di halaman web tersebut, untuk cara awal kita coba lihat di source code web tersebut barang kali flag nya di sembunyikan dengan comment html, untuk cara melihat source code kita bisa menekan tombol `Ctrl + U.`

![INS_3](https://user-images.githubusercontent.com/119099396/229422179-d94196f8-1917-4cad-b4a7-71ac0ebe995e.png)
maka hasil dari `Ctrl + U` tersebut kita bisa melihat source code nya dan benar flag tersebut terlihat saat kita melihat source code web tersebut, itu karena flag tersebut di berikan comment yang mana jika sebuah teks di berikan comment di html, contoh comment di html `<!-- ini adalah comment -->`  maka teks tersebut tidak akan di eksekusi.

FLAG = W9{***********************}


# MAGIC - Web

## Attached
![MGC_1](https://user-images.githubusercontent.com/119099396/229423390-c0c40293-f120-4eac-8f12-1802f810515e.png)

Di soal ini kita di berikan link lalu saat link tersebut di buka ada source code php, dan ini adalah php `type jungling.`

![MGC_2](https://user-images.githubusercontent.com/119099396/229425074-2a3059a1-06ec-4ef0-b2fe-2f0e96fbabea.png)

## Solutions
Kalau kita analisis source tersebut saat kita membuka file flag.php web tidak akan menampilkan flag karena kita tidak menginputkan value yang di minta, di source code tersebut di minta kita mengirimkan parameter x dan y dan kita harus menambahkan md5, jadi flag tersebut akan muncul saat kita mengirim parameter x dan y dengan md5 yang serupa tapi tak sama misal `x=tes` dan `y=ttes`, untuk kumpulan hash md5 bisa kalian buka link tersebut `https://gist.github.com/atoponce/bb672d93233121560d2841f67e41698b`

![MGC_3](https://user-images.githubusercontent.com/119099396/229425575-dbe221cf-aa9e-40a7-ade3-93ad37c64b66.png)

Kita coba request x dan y dengan md5 yang serupa tapi tak sama seperti gambar di bawah ini 

![MGC_4](https://user-images.githubusercontent.com/119099396/229426773-f7001085-0cde-40f6-ae47-f351f30c05d5.png)

Dan boom flag nya akan muncul karena kita mengirimkan parameter yang sesuai dari permintaan source code tersebut!!

![MGC_5](https://user-images.githubusercontent.com/119099396/229426929-c50ac47e-8bda-4dc8-bec0-d9bd2f080854.png)


FLAG = W9{****************************}
