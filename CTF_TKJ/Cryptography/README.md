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
