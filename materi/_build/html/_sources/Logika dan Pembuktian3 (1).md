---
title: Logika dan Pembuktian3

---

## Logika Matematika

## Negasi

Apa itu Negasi?
Negasi dalam logika matematika adalah operasi yang mengubah nilai kebenaran suatu proposisi menjadi kebalikannya. Jika proposisi awal $( p )$ bernilai benar, maka negasinya $( \neg p )$ bernilai salah, dan sebaliknya.

Contoh:

$( p )$: Semua anak suka menonton film horror.
$( \neg p )$: Tidak semua anak suka menonton film horror.
Negasi sering digunakan dalam berbagai bidang, termasuk matematika dan bahasa, untuk menyatakan penyangkalan atau peniadaan

| P | -P | 
| - | - |
|  T  | F  | 


## Konjungsi

Dalam logika matematika, konjungsi adalah operasi logika yang menghubungkan dua pernyataan atau proposisi dengan kata penghubung “dan” $(AND)$. Konjungsi dari dua pernyataan $( p )$ dan $( q )$ dinyatakan sebagai $( p \land q )$ (dibaca: “p dan q”). Konjungsi $( p \land q )$ bernilai benar hanya jika kedua pernyataan $( p )$ dan $( q )$ bernilai benar. Jika salah satu atau kedua pernyataan bernilai salah, maka konjungsi tersebut bernilai salah.

Contoh:

$( p )$: Hari ini hujan.
$( q )$: Saya membawa payung.
Konjungsi $( p \land q )$: Hari ini hujan dan saya membawa payung.
Tabel kebenaran untuk konjungsi adalah sebagai berikut:

Tabel

|( p )|	( q )|	$( p \land q )$|
| -----|-----|---------------|
|T	|T	|T|
|T	|F|F|
|F	|T	|F|
|F|F	|F|

Di sini, “T” berarti benar (true) dan “F” berarti salah (false).

## Disjungsi

Disjungsi dalam matematika adalah salah satu operator logika yang digunakan untuk menghubungkan dua proposisi atau pernyataan dengan kata “atau” (dilambangkan dengan simbol $( \vee )$. Disjungsi bernilai benar jika salah satu atau kedua proposisi yang dihubungkan bernilai benar, dan bernilai salah hanya jika kedua proposisi bernilai salah1.

Contoh sederhana dari disjungsi adalah:

$( p )$: “Hari ini hujan.”
$( q )$: “Hari ini cerah.”
Disjungsi dari $( p )$ dan ( q ) adalah ( p \vee q ), yang berarti “Hari ini hujan atau hari ini cerah.” Pernyataan ini akan bernilai benar jika salah satu dari ( p ) atau ( q ) benar, atau jika keduanya benar. Pernyataan ini hanya akan bernilai salah jika kedua ( p ) dan ( q ) salah.

## Implikasi

Dalam logika matematika, implikasi adalah pernyataan majemuk yang menghubungkan dua proposisi dengan menggunakan kata “jika” dan “maka” (dilambangkan dengan simbol $( \rightarrow )$. Implikasi menyatakan hubungan sebab-akibat antara dua proposisi.

Contoh sederhana dari implikasi adalah:

( p ): “Jika hari ini hujan.”
( q ): “Maka saya akan membawa payung.”
Implikasi dari ( p ) dan ( q ) adalah ( p \rightarrow q ), yang berarti “Jika hari ini hujan, maka saya akan membawa payung.” Pernyataan ini hanya akan bernilai salah jika ( p ) benar dan ( q ) salah. Dalam semua kasus lainnya, implikasi ini bernilai benar



| $(p)$ | $(q)$ | $(p\rightarrow q)$|
| -------- | -------- | -------- |
|   T  | T     | T   |
|T|F|F|
|F|T|T|
|F|F|T|

## Biimplikasi

Dalam logika matematika, biimplikasi adalah pernyataan majemuk yang menghubungkan dua proposisi dengan kata “jika dan hanya jika” (dilambangkan dengan simbol ( \leftrightarrow )). Biimplikasi menyatakan bahwa kedua proposisi memiliki nilai kebenaran yang sama: keduanya benar atau keduanya salah1.

Contoh sederhana dari biimplikasi adalah:

( p ): “Hari ini hujan.”
( q ): “Saya membawa payung.”
Biimplikasi dari ( p ) dan ( q ) adalah $( p \leftrightarrow q )$, yang berarti “Hari ini hujan jika dan hanya jika saya membawa payung.” Pernyataan ini akan bernilai benar jika kedua ( p ) dan ( q ) benar atau kedua ( p ) dan ( q ) salah. Pernyataan ini akan bernilai salah jika salah satu dari ( p ) atau ( q ) benar dan yang lainnya salah.

Berikut adalah tabel kebenaran untuk biimplikasi:
( p )|	( q )	|$( p \leftrightarrow q )$|
|----|-----|---|
T	|T|	T
T	|F	|F
F	|T|	F
F|	F|	T

Penjelasan:

( p ) dan ( q ) adalah proposisi.
( p \leftrightarrow q ) adalah biimplikasi yang berarti “jika dan hanya jika ( p ), maka ( q )”.
Tabel menunjukkan bahwa biimplikasi  $( p \leftrightarrow q )$ hanya bernilai benar jika kedua proposisi memiliki nilai kebenaran yang sama2.