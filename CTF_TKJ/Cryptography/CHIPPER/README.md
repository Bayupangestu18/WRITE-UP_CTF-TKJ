# CHIPPER - Cryptography

![CHR_1](https://user-images.githubusercontent.com/119099396/229657085-f2a8dff0-9b70-4d94-98d4-b1aebe40f91d.png)

Di soal ini deskripsinya hanya tertulis password, itu berarti untuk mendecrypt nya kita perlu memasukkan passwordnya. Dan di sini terdapat hint seperti 
berikut.

![CHR_2](https://user-images.githubusercontent.com/119099396/229657796-89a21c61-2c4c-4085-8438-da2d42f8dcc2.png)

## Solutions

![CHR_3](https://user-images.githubusercontent.com/119099396/229658644-f973b1db-958b-4638-8e84-81dd412230b4.png)

Untuk penyelesaian nya kita perlu mencari chipper yang bila mana kalau mendecrypt dan memerlukan password di hint tersebut terdapat kata `cyber` mungkin ini meyangkut web brute force yaitu [cyber cheff](https://gchq.github.io/CyberChef), kita perlu mencari sebuah chipper yang bila mana kita decrypt butuh memasukkan password, nah di sini saya menemukan nya yaitu sebuah CHIPPERSABER2 coba kita decrypt teks tersebut.

![CHR_4](https://user-images.githubusercontent.com/119099396/229659275-e82d6373-ab0a-43ec-ac16-8c099777c9b2.png)

Nah disini flag nya berada di rounds `20` dengan format `hex` dan password nya `walisongo` jika kita memasukkan semua nya dengan benar maka hasil decrypt an nya akan sesuai dengan yang kita ingikan.

FLAG = W9{************************}
