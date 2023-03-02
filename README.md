# Routh-Stability
Tugas Sistem Kendali - Stabilitas Routh dengan program Python

Dalam program digunakan library sympy yang berfungsi menampilkan simbol-simbol matematis, serta menggunakan fungsi routh dari library tbcontrol untuk melakukan perhitungan stabilitas routh.
Di awal program dideklarasikan simbol K dan s sebagai variabel dalam perhitungan, sesuai dengan soal yang diberikan, dengan fungsi sympy.Symbol().
Sebelum memulai perhitungan, persamaan polinomial dideklarasikan dalam variabel p.
Untuk mengonstruksi persamaan polinomial dalam variabel p digunakan fungsi sympy.Poly().

Pada bagian selanjutnya, membuat tabel Routh dengan fungsi routh dari library tbcontrol. Untuk menggunakan fungsi routh perlu memasukkan persamaan polinomial yang telah dikonstruksi sebelumnya dengan sympy.Poly().
Akhirnya gunakan fungsi sympy.solve untuk menemukan nilai K dengan syarat setiap nilai dalam kolom ke-0 (kolom pertama) R adalah lebih besar dari nol.
