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
