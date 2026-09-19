#### 1. Diketahui 2 buah matrix yaitu A dan B

$$
A = \begin{pmatrix}
2 & 1 \\
0 & 3
\end{pmatrix}

B = \begin{pmatrix}
1 & 4 \\
-2 & 5
\end{pmatrix}
$$

Hitunglah:

- $2A$
- $AB$
- $2A + AB$

**Jawaban**

1a. Untuk mengalikan sebuah matrix dengan nilai skalar, elemen-elemennya harus dikalikan dengan nilai yang sama. Jadi, 2A adalah:

$$
2 \times A = \begin{pmatrix}
2 \times 2 & 2 \times 1 \\
2 \times 0 & 2 \times 3
\end{pmatrix}
$$

Maka hasil dari kalkulasi 2A adalah:

$$
2A = \begin{pmatrix}
4 & 2 \\
0 & 6
\end{pmatrix}
$$

1b. Untuk mengalikan 2 buah matrix dapat dilakukan dengan syarat jumlah baris dari martix pertama harus sama dengan jumlah kolom dari matrix kedua, atau sebaliknya, pada kasus ini matrix A dan B merupakan matrix bujur sangkar dengan ordo $2 \times 2$, jadi memenuhi syarat, operasi perkalian matrix dapat dilakukan dengan menjumlahkan perkalian dari masing masing elemen pada baris matrix A dengan masing masing elemen pada baris matrix B, sebagai berikut:

$$
A \times B = \begin{pmatrix}
2 \times 1 + 1 \times (-2) & 2 \times 4 + 1 \times 5 \\
0 \times 1 + 3 \times (-2) & 0 \times 4 + 3 \times 5
\end{pmatrix}
$$

$$
AB = \begin{pmatrix}
2 - 2 & 8 + 5 \\
0 - 6 & 0 + 15
\end{pmatrix}
$$

Maka hasil akhir dari perkalian matrix $A$ dan $B$ adalah:

$$
AB = \begin{pmatrix}
0 & 13 \\
-6 & 15
\end{pmatrix}
$$

1c. Untuk menjumlahkan 2 buah matrix diperlukan 2 matrix dengan jumlah ordo yang sama, pada kasus ini matrix $2A$ dan $AB$ memliki jumlah ordo yang sama sehingga dapat dilakukan, penjumlahan matrix dilakukan dengan menjumlahkan elemen pada posisi index baris dan kolom yang sama di kedua matrix, contohnya sebagai berikut:

$$
2A + AB = \begin{pmatrix}
4 + 0 & 2 + 13 \\
0 - 6 & 6 + 15
\end{pmatrix}
$$

Maka hasil penjumlahan matrix $2A + AB$ adalah:

$$
2A + AB = \begin{pmatrix}
4 & 15 \\
-6 & 21
\end{pmatrix}
$$

#### 2. Apakah matriks berikut merupakan matriks bujur sangkar? berikan penjelasannya!

$$
C = \begin{pmatrix}
1 & 5 & 2 \\
5 & 4 & 5
\end{pmatrix}
$$

**Jawaban**

Matrix $C$ diatas bukan merupakan matrix bujur sangkar, sebuah matrix dapat dikategorikan ke dalam tipe matrix bujur sangkar apabila jumlah baris dan kolomnya sama, contohnya matrix $A$ dan $B$ pada sola sebelumnya
