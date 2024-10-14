---
title: Algoritma

---

# Algoritma
## Definisi Algoritma
Algoritma adalah serangkaian instruksi atau langkah-langkah yang didefinisikan dengan jelas dan sistematis untuk menyelesaikan suatu tugas atau memecahkan masalah tertentu. Dalam konteks pemrograman, algoritma adalah resep dasar yang memberitahu komputer bagaimana mengeksekusi serangkaian tugas.
##### Referensi
1.https://dailysocial.id/post/algoritma-pengertian-fungsi-sejarah-dan-contoh-penerapannya
2.https://tirto.id/algoritma-definisi-ciri-jenis-struktur-dan-contohnya-gjgn
3.https://www.gramedia.com/literasi/pengertian-algoritma/
### Algoritma sequantial search
Algoritma Sequential Search adalah metode pencarian data yang dilakukan dengan membandingkan setiap elemen dalam daftar satu per satu, mulai dari elemen pertama hingga elemen yang dicari ditemukan atau seluruh elemen telah diperiksa12. Algoritma ini sangat sederhana dan sering digunakan ketika data tidak terstruktur atau tidak diurutkan.

Cara Kerja Sequential Search
Mulai dari elemen pertama dalam daftar.
Bandingkan elemen saat ini dengan elemen yang dicari.
Jika elemen cocok, pencarian selesai.
Jika tidak, lanjutkan ke elemen berikutnya.
Ulangi langkah 2-4 sampai elemen ditemukan atau daftar habis.
##### Referensi
1.https://fikti.umsu.ac.id/algoritma-sequential-search-pengertian-fungsi-dan-cara-kerjanya/
### Algoritma binary search
Algoritma Binary Search adalah metode pencarian yang efisien untuk menemukan elemen dalam daftar yang sudah diurutkan. Algoritma ini bekerja dengan membagi daftar menjadi dua bagian secara berulang hingga elemen yang dicari ditemukan atau ruang pencarian habis12.

Cara Kerja Binary Search
Tentukan elemen tengah dari daftar yang diurutkan.
Bandingkan elemen tengah dengan elemen yang dicari:
Jika elemen tengah adalah elemen yang dicari, pencarian selesai.
Jika elemen tengah lebih besar dari elemen yang dicari, ulangi proses pada bagian kiri daftar.
Jika elemen tengah lebih kecil dari elemen yang dicari, ulangi proses pada bagian kanan daftar.
Ulangi langkah 1-2 hingga elemen ditemukan atau ruang pencarian habis.
##### Referensi
1.https://tekno.kompas.com/read/2022/12/03/03000047/pengertian-binary-search-cara-kerja-dan-keunggulannya
### Pseudcode adalah....
Pseudocode adalah deskripsi langkah demi langkah dari suatu algoritma yang ditulis dalam bahasa yang mudah dipahami oleh manusia12. Pseudocode tidak menggunakan sintaks dari bahasa pemrograman tertentu, melainkan menggunakan bahasa Inggris sederhana atau bahasa alami lainnya untuk menjelaskan logika dan alur dari algoritma tersebut12.

Tujuan Pseudocode
Mempermudah Pemahaman: Membantu programmer dan non-programmer untuk memahami logika algoritma tanpa harus memahami sintaks bahasa pemrograman tertentu.
Perencanaan: Digunakan dalam tahap perencanaan sebelum menulis kode sebenarnya, sehingga memudahkan transisi dari ide ke implementasi.
Dokumentasi: Menyediakan dokumentasi yang jelas dan mudah dipahami tentang bagaimana algoritma bekerja.
### Referensi
1.https://www.geeksforgeeks.org/what-is-pseudocode-a-complete-tutorial/
2.https://en.wikipedia.org/wiki/Pseudocode
### Big 0 algoritma
Big O Notation adalah cara untuk menggambarkan kompleksitas waktu atau ruang dari suatu algoritma dalam hal ukuran inputnya. Notasi ini digunakan untuk mengukur seberapa efisien suatu algoritma, terutama dalam skenario terburuk12.

Jenis-Jenis Big O Notation
O(1): Konstan - Waktu eksekusi tidak berubah meskipun ukuran input berubah.
O(n): Linear - Waktu eksekusi meningkat secara linear dengan ukuran input.
O(n^2): Kuadratik - Waktu eksekusi meningkat secara kuadrat dengan ukuran input.
O(log n): Logaritmik - Waktu eksekusi meningkat secara logaritmik dengan ukuran input.
O(n log n): Linear Logaritmik - Kombinasi dari linear dan logaritmik.
##### Refeensi
1.https://www.geeksforgeeks.org/analysis-algorithms-big-o-analysis/
2.https
### Hitung big o dari algoritma sequantial search://www.freecodecamp.org/news/big-o-cheat-sheet-time-complexity-chart/
### Hitung big O dari algoritma sequantial search
Algoritma Sequential Search memiliki kompleksitas waktu O(n)1. Ini berarti bahwa dalam skenario terburuk, waktu yang dibutuhkan untuk mencari elemen dalam daftar akan meningkat secara linear dengan ukuran daftar tersebut.

Penjelasan
O(n): Kompleksitas waktu linear menunjukkan bahwa jika ada ( n ) elemen dalam daftar, algoritma mungkin harus memeriksa setiap elemen satu per satu hingga menemukan elemen yang dicari atau mencapai akhir daftar.
Skenario Terburuk: Dalam kasus terburuk, elemen yang dicari berada di posisi terakhir atau tidak ada dalam daftar, sehingga algoritma harus memeriksa semua ( n ) elemen.
Contoh
Jika Anda memiliki daftar dengan 10 elemen, Sequential Search mungkin harus melakukan hingga 10 perbandingan dalam skenario terburuk. Jika daftar memiliki 1.000 elemen, algoritma mungkin harus melakukan hingga 1.000 perbandingan.
### Referensi
1. https://runestone.academy/ns/books/published/pythonds/SortSearch/TheSequentialSearch.html
