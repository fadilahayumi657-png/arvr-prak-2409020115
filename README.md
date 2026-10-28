# Praktikum AR/VR - Pertemuan 1
- Nama : SHERLY AYUMI FADILAH
- NIM : 2409020115
- Link demo : https://fadilahayumi657-png.github.io/arvr-prak-2409020115/
Project ini berisi scene WebXR pertama menggunakan A-Frame 1.7.1.


Mengapa posisi objek yang terlihat pertama kali oleh pengguna memakai nilai z negatif?
Di sistem koordinat WebXR, sumbu Z positif itu arahnya ke belakang (menjauhi kita), nah kalau sumbu Z negatif itu pas di depan mata kita. Makanya, biar pas scene-nya dibuka objeknya langsung kelihatan di depan muka dan nggak nyasar di belakang kepala, posisinya harus pakai nilai negatif.

Mengapa WebXR hanya aktif pada HTTPS atau localhost?
Karena browser sekarang ketat banget soal keamanan, terutama buat fitur yang akses sensor perangkat kayak kamera atau giroskop. Makanya cuma dibolehin lewat HTTPS atau localhost yang dianggap aman, supaya data sensor kita nggak gampang dicuri atau disadap sama situs web abal-abal.

Jelaskan perbedaan peran WebXR Device API, Three.js, dan A-Frame dengan bahasa Anda sendiri!
-WebXR Device API itu ibarat jembatan utamanya di browser yang ngenalin perangkat VR atau HP kita supaya bisa nyambung ke dunia 3D.
-Three.js itu kaya perkakas (tools) berbasis JavaScript buat bikin objek, lampu, atau kamera 3D jadi lebih gampang ketimbang kita harus coding dari nol yang ribet banget.
-A-Frame itu kerangka kerja yang bikin kita bisa bikin dunia virtual pakai format mirip HTML biasa. Jadi tinggal pakai tag-tag khusus, praktis, tapi aslinya di balik layar tetap ditenagai sama Three.js.