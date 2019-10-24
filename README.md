#Python Lab 1


Latihan praktikum menggunakan Python

Pertama, saya mencoba menggunakan text editor notepad untuk membuat file program python.
Saya tuliskan perintah sesuai yang dosen berikan kedalam notepad seperti berikut :  
  
#Latihan penggunaan end  
print('A', end= '')  
print('B', end= '')  
print('C', end= '')  
print ()  
print('X', end = '')  
print('Y', end = '')  
print('Z', end = '')  

**Pemahaman yang ditangkap :  
Perintah *end adalah perintah untuk memberikan akhiran pada perintah,  
jika dalam *end = ''* atau kosong, maka akan diabaikan.  
Jika *end = '\n'* maka hasilnya akan pindah berganti ke baris di bawahnya.
  
#Latihan penggunaan separator  
w, x, y, z = 10, 15, 20, 25  
print(w, x, y, z)  
print(w, x, y, z, sep=',')  
print(w, x, y, z, sep='')  
print(w, x, y, z, sep=':')  
print(w, x, y, z, sep='-----')  
  
**Pemahaman yang ditangkap :  
Perintah *sep* adalah perintah untuk menyisipkan karakter diantara nilai veriable,  
jika dalam *sep = ''* atau kosong, maka akan diabaikan.  
Jika *sep = 'karakter'*, maka hasilnya diantara variable akan dipisahkan atau  
disisipi karakter tersebut.  
  
  
#String format  
print(0, 10**0)  
print(1, 10**1)  
print(2, 10**2)  
print(3, 10**3)  
print(4, 10**4)  
print(5, 10**5)  
print(6, 10**6)  
print(7, 10**7)  
print(8, 10**8)  
print(9, 10**9)  
print(10, 10**10)  
  
**Pemahaman yang ditangkap :  
Perintah *dengan string format*, akan menampilkan hasil sebagai karakter.  
Pada contoh diatas angka pertama akan muncul sebagai nomor, dan angka _10**n_ akan
menghasilkan nilai _10 pangkat n_.  
  
  
  
#String format  
print('{0:>3} {1:>16}'.format(0, 10**0))  
print('{0:>3} {1:>16}'.format(1, 10**1))  
print('{0:>3} {1:>16}'.format(2, 10**2))  
print('{0:>3} {1:>16}'.format(3, 10**3))  
print('{0:>3} {1:>16}'.format(4, 10**4))  
print('{0:>3} {1:>16}'.format(5, 10**5))  
print('{0:>3} {1:>16}'.format(6, 10**6))  
print('{0:>3} {1:>16}'.format(7, 10**7))  
print('{0:>3} {1:>16}'.format(8, 10**8))  
print('{0:>3} {1:>16}'.format(9, 10**9))  
print('{0:>4} {1:>16}'.format(10, 10**10))   
  
Kemudian saya simpan file tersebut menjadi file python dengan nama **Python_Lab1.py**  
Kemudian saya buka file tersebut dengan menggunakan applikasi Python 3.8.0. Shell.
Setelah itu saya coba run **(F5)** file tersebut, dan saya pelajari hasilnya dari setiap format yang dipakai.  

