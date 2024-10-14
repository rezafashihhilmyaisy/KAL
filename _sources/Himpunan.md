---
title: Himpunan

---


Tugas Mathdisk

1. hukum de morgan's laws

$\begin{aligned} & \overline{A \cap B}=\bar{A} \cup \bar{B} \\ & \overline{A \cup B}=\bar{A} \cap \bar{B}\end{aligned}$
Misalkan ( A ) dan ( B ) adalah dua himpunan. Diberikan:

( A = {1, 2, 3} )
( B = {2, 3, 4} )

Tentukan komplemen dari gabungan ( A ) dan ( B ).
Jawaban:
Menurut Hukum De Morgan, komplemen dari gabungan ( A ) dan ( B ) adalah:
<math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><semantics><mrow><mover accent="true"><mrow><mi>A</mi><mo>∪</mo><mi>B</mi></mrow><mo stretchy="true">‾</mo></mover><mo>=</mo><mover accent="true"><mi>A</mi><mo stretchy="true">‾</mo></mover><mo>∩</mo><mover accent="true"><mi>B</mi><mo stretchy="true">‾</mo></mover></mrow><annotation encoding="application/x-tex">
    2. absorption laws
    
$\begin{aligned} & A \cup(A \cap B)=A \\ & A \cap(A \cup B)=A\end{aligned}$
    Diberikan dua himpunan ( P = {1, 2, 3} ) dan ( Q = {2, 3, 4} ). Buktikan hukum idempoten dengan menunjukkan bahwa:

$( P \cup (P \cap Q) = P )$
$( P \cap (P \cup Q) = P )$
Langkah-langkah Penyelesaian:

Bukti untuk $( P \cup (P \cap Q) = P ):$
$( P \cap Q = {2, 3} )$
$( P \cup (P \cap Q) = {1, 2, 3} \cup {2, 3} = {1, 2, 3} = P )$
Bukti untuk $( P \cap (P \cup Q) = P ):$
$( P \cup Q = {1, 2, 3, 4} )$
$( P \cap (P \cup Q) = {1, 2, 3} \cap {1, 2, 3, 4} = {1, 2, 3} = P )$
Dengan demikian, kedua hukum idempoten terbukti benar untuk himpunan ( P ) dan ( Q ).
    
3. Complement laws
    
    $\begin{aligned} & A \cup \bar{A}=U \\ & A \cap \bar{A}=\emptyset\end{aligned}$
    
    
Diberikan himpunan semesta ( U = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10} ) dan himpunan ( A = {2, 4, 6, 8, 10} ).

Tentukan komplemen dari himpunan $( A ) (( A’ ))$.
Verifikasi bahwa $( A \cup A’ = U )$.
Verifikasi bahwa $( A \cap A’ = \emptyset )$.
Penyelesaian:
Komplemen dari himpunan $( A ) (( A’ )): [ A’ = U - A =$ {1, 3, 5, 7, 9} ]
Verifikasi bahwa $( A \cup A’ = U ): [ A \cup A’ =$ {2, 4, 6, 8, 10} $\cup$ {1, 3, 5, 7, 9} = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10} = $U$]
Verifikasi bahwa $( A \cap A’ = \emptyset ): [ A \cap A’ =${2, 4, 6, 8, 10} $\cap$ {1, 3, 5, 7, 9} $= \emptyset$]