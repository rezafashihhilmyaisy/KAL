---
title: DERET

---

# DERET
Deretan adalah suatu urutan atau susunan elemen atau objek yang disusun secara teratur berdasarkan suatu aturan tertentu. Elemen dalam deretan biasanya berupa angka, huruf, simbol, atau objek lainnya, dan urutannya dapat didasarkan pada pola, nilai, atau hubungan tertentu
Definisi: Sebuah deretan adalah fungsi dari subset suatu himpunan bilangan bulat (biasanya N atau P) ke sebuah himpunan S.

   N = {1, 2, 3, 4, … }
   S misalnya {2, 4, 6, 8, …},   {1/3, 1/5, 1/7, …},  dsb

Notasi deretan: {an}
Deretan umumnya dinyatakan dalam suatu formula, misalnya:
	an = 2n
	an = 1/n
	an = 7 – 3n
Dalam konteks matematika, deretan sering merujuk pada barisan bilangan, yaitu kumpulan bilangan yang disusun dalam suatu pola tertentu.
 Misalnya:
Deretan bilangan ganjil: 1,3,5,7,…
Deretan bilangan genap: 2,4,6,8,…
Deretan bilangan yang membentuk deret aritmetika: 3,6,9,12....

Contoh-contoh deretan dan formulanya:

Deret Aritmetika
Deret dengan pola kenaikan atau penurunan tetap.- Contoh: 2,5,8,11,14,…- Rumus suku ke-n:U_n=a+(n−1)⋅bDi mana:- a: suku pertama - b: beda (selisih antar suku- n: nomor suku yang dicari
Deret Geometri
Deret dengan pola kelipatan tetap.- Contoh: 3,6,12,24,48,…- Rumus suku ke-n:U_n=a⋅r^(n−1)Di mana:- a: suku pertama - r: rasio (perbandingan antar suku,- n: nomor suku yang dicari

Deret Bilangan Kuadrat
Deret dengan pola nilai berupa kuadrat bilangan bulat.- Contoh: 1,4,9,16,25,…- Rumus suku ke-n:U_n=n^2
Deret Bilangan Kubik
Deret dengan pola nilai berupa kubik bilangan bulat.- Contoh: 1,8,27,64,125,…- Rumus suku ke-n:U_n=n^3

Deret Fibonacci
Deret dengan pola di mana setiap suku merupakan jumlah dua suku sebelumnya.- Contoh: 0,1,1,2,3,5,8,…- Rumus suku ke-n (rekursif):F_n=F_n−1+F_n−2,F_0=0,F_1=1

String adalah deretan berhingga karakter berbentuk
		a1a2a3a4…an

    Panjang string S adalah jumlah karakter di dalam string tersebut
     
    Contoh:  informatika adalah string dengan panjang 11 karakter
	         10100101 adalah string biner dengan panjang 8 bit

String kosong dilambangkan dengan , panjangnya = 0
### penjumlahhan deretan
Contoh 2: Berapa nilai ∑_k=1^5▒k^2?
Jawaban: 
	∑_k=1^5▒k^2= 12 + 22 + 32 + 42 + 52 = 1 + 4 + 9 + 16 + 25 = 55

Contoh 3: Batas bawah sumasi kadangkala perlu digeser agar dapat dijumlahkan dengan sumasi lain yang memiliki batas bawah berbeda. Pada contoh 2 di atas batas bawah digeser dari 1 menjadi 0, akibatnya:
	 ∑_k=1^5▒k^2= ∑_k=0^4▒(k+1)^2 

Contoh 4: Sumasi dapat dipecah dengan membagi dua indeksnya, misalnya
	  ∑_k=1^100▒k^2=  ∑_k=1^49▒k^2 +  ∑_k=50^100▒k^2
      
### sumasi ganda
Di dalam algoritma, kita perlu menghitung berapa kali suatu operasi tertentu dilakukan di dalam sebuah kalang bersarang (nested loop). Penjumlahan semua operasi di dalam kalang bersarang dinyatakan dalam bentuk sumasi ganda.

    Contoh: ∑_i=1^4▒∑_j=1^3▒ij 

    Untuk menghitung sumasi ganda, mula-mula ekspansi sumasi terdalam, lalu  dilanjukan dengan sumasi terluar:
	 	∑_i=1^4▒∑_j=1^3▒ij = ∑_i=1^4▒(i+2i+3i)= ∑_i=1^4▒6i = 6 + 12 + 18 + 24 = 60
## REKURSI
Sebuah objek dikatakan rekursif  (recursive) jika ia didefinisikan dalam terminologi dirinya sendiri. 

Proses mendefinisikan objek dalam terminologi dirinya sendiri disebut rekursi (recursion).

### fungsi rekursi
Fungsi rekursif didefinisikan oleh dua bagian:
 (i)  Basis 
Bagian yang berisi nilai fungsi yang terdefinisi secara eksplisit. 
Bagian ini juga sekaligus menghentikan rekursif (dan memberikan sebuah nilai yang terdefinisi pada fungsi rekursif).
 
 (ii)  Rekurens
Bagian ini mendefinisikan fungsi dalam terminologi dirinya sendiri. 
Berisi kaidah untuk menemukan nilai fungsi pada suatu input dari nilai-nilai lainnya pada input yang lebih kecil. 

Contoh 6:  Misalkan f didefinsikan secara rekusif sbb

								
		           
		        Tentukan nilai f(4)!
	
	Solusi:      f(4) = 2f(3) + 4 
			=  2(2f(2) + 4) + 4
			=  2(2(2f(1) + 4) + 4) + 4
			=  2(2(2(2f(0) + 4) + 4) + 4) + 4
			=  2(2(2(23 + 4) + 4) + 4) + 4	
			=  2(2(2(10) + 4) + 4) + 4
			=  2(2(24) + 4) + 4
			=  2(52) + 4
			= 108	
function Faktorial (input  n :integer)integer
{ mengembalikan nilai n!;
  basis   : jika n = 0, maka 0! = 1
  rekurens: jika n > 0, maka n! = n  (n-1)!
}
DEKLARASI
      -
ALGORITMA:
    if n = 0 then
       return 1		              { basis }
    else
       return  n * Faktorial(n – 1)	{ rekurens }
    end

### struktur rekursif
Simpul (node) pada pohon biner mempunyai paling banyak dua buah anak.

Jumlah anak pada setiap simpul bisa 1, 2, atau 0.

Simpul yang mempunyai anak disebut simpul cabang (branch node) atau simpul dalam (internal node)

Simpul yang tidak mempunyai anak disebut simpul daun (leave).

