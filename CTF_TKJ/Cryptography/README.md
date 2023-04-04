# Dots N D4sh3s - Cryptography

## Attached

![CRY_1](https://user-images.githubusercontent.com/119099396/229521839-0900a5ae-7f4c-4788-997f-f102096a7fa6.png)

Di soal cryptography ini di berikan soal berupa file txt, di dalam file txt tersebut ada tulisan yang tidak bisa di baca jadi kita harus mencari teks aslinya.

## Solutions

![CRY_2](https://user-images.githubusercontent.com/119099396/229522976-d3af1ebc-36cf-4b81-8261-fd9be9152d3e.png)

Di sini terdapat tulisan yang tidak bisa kita baca jadi kita harus mencari teks aslinya agar bisa menemukan flag nya, nah kebetulan kode tersebut adalah morse code bagaimana kita tau kalau itu merupakan morse code?, kita bisa memakai tools berikut [Chipper Identifier](https://www.dcode.fr/cipher-identifier) tinggal kita paste aja teks yang mau kita cari identitas nya, misal seperti ini nah di situ terlihat bahwa morse code vote nya sangat banyak jadi teks tersebut adalah sebuah morse code.

![CRY_3](https://user-images.githubusercontent.com/119099396/229527037-6da4c018-7830-4a76-b5f3-a1cbacd49589.png)

lalu kita bisa mendecrypt teks tersebut agar menjadi teks asli seperti ini, setelah kita decrypt teks tersebut berupa teks lain dan ini adalah teks binary jadi kita hanya perlu mendecrypt dari binary ke teks.

![CRY_4](https://user-images.githubusercontent.com/119099396/229528459-ec92cec7-782c-4250-b41e-80f4a4bd6120.png)

Decrypt binary ke text bisa lewat web ini [Binary to Text](https://www.rapidtables.com/convert/number/binary-to-ascii.html), dan nanti kita akan mendapatkan flag nya seperti ini.

![CRY_5](https://user-images.githubusercontent.com/119099396/229528482-1170bedc-d952-421a-be37-58733f78fdab.png)

FLAG = W9{*********************}

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

