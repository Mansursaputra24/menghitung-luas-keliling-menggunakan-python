# menghitung-luas-keliling-menggunakan-python

Rumus Luas & Keliling Lingkaran
Luas     = π × r²
Keliling = 2 x π × r
Nilai Phi yang akan kita gunakan adalah 3.14
r merupakan jari-jari lingkaran
Phi merupakan nilai konstanta di matematika sementara jari-jari merupakan jarak antara titik pusat dengan tepi lingkaran. Sebetulnya ada rumus lain untuk menghitung keliling lingkaran yaitu dengan menggunakan diameter, tapi pada kasus ini kita cukup menggunakan jari jari lingkaran saja.

Program Python Menghitung Luas & Keliling Lingkaran
import math
r = float(input("Masukan Jari-jari : "))

luas = math.pi*(r*r)
keliling = 2*math.pi*r

print ("Luas Lingkaran \t\t= ",luas)
print ("Keliling Lingkaran\t= ",keliling)

Output:

Masukan Jari-jari : 3.6
Luas Lingkaran          =  40.71504079052372
Keliling Lingkaran      =  22.61946710584651

Penjelasan:
Program diatas saya mengimport modul math yang sudah di sediakan oleh python. Fungsinya supaya saya dapat menyertakan nilai phi yang sudah tersedia dalam modul tersebut dengan perintah math.pi jika kita coba mencetak fungsi tersebut maka akan menghasilkan nilai 3.14
