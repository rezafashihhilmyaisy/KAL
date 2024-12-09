---
title: Graph

---

# Graph
graaph adalah kumpulan note yang sling berhubungan
## social network
social network merupakan bidang kajian yang mengekplorasi tentang hubungan manusia dengan menggunakan teori graf. Implementasi Social Network Analysis dapat menjelaskan relasi atau hubungan antar aktor melalui visualisasi berbentuk graf. Relasi dalam analisis jaringan sosial dapat diproses dalam bentuk perhitungan yang disebut centrality dalam sebuah jaringan sosial sesuai dengan posisi masing-masing aktor di dalam struktur jaringan tersebut
## Degree Centrality
Degree centrality adalah jumlah edge yang terkoneksi pada suatu node yang mewakili interaksi.
Pentingnya node ditentukan oleh jumlah node yang berdekatan dengan node tersebut
Lebih besar derajatnya (degree), maka lebih penting node itu dalam suatu jaringan 
Hanya sebagian kecil node yang memiliki derajat tinggi dalam jaringan 
rumus:
  $C_D(v) = \frac{\deg(v)}{n-1}$
  
contoh: 


## closeness Centrality
Closenes centrality adalah nilai kedekatan antara satu node dengan node lain dalam jaringan dengan menghitung rata-rata dari jarak relasi node-node tersebut. Skor closeness centrality mewakili kecepatan dalam penyebaran informasi.
rumus:
 $C_C(v) = \frac{n-1}{\sum_{u \neq v} d(v, u)}$

## betweenness centrality
Skor betweeness Centrality mewakili seberapa besar informasi yang tersebar dari suatu aktor. Semakin besar skor, artinya aktor tersebut semakin berperan dalam penyebaran informasi 

Semakin banyak lintasan yang harus melewati persimpangan itu (misal tidak ada jalan alternatif), maka semakin penting arti persimpangan tersebut. Hal ini menandakan seberapa besar suatu node diperlukan sebagai penghubung dalam penyebaran informasi di dalam jaringan

Ukuran ini juga dapat digunakan untuk mengidentifikasi boundary spanners, yaitu orang atau node yang berperan sebagai penghubung (jembatan) antara dua komunitas
rumus: 
$C_B(v) = \sum_{s \neq v \neq t} \frac{\sigma(s,t|v)}{\sigma(s,t)}$


