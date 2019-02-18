# TUGAS PRAKTIKUM 3
Algoritma program latihan1.py, latihan2.py, dan program1.py

# latihan1.py
ALUR ALGORITMA latihan1.py. kita memulai pertama

# LANGKAH PERTAMA
Buka Notepad. Pada Windows 10
bukalah menu "Start" Anda lalu ketik “Notepad” pada kotak pencari.
Pilih Notepad untuk membuka aplikasi tersebut. 
Anda juga dapat beralih ke folder “Accessories” pada menu "Start" lalu pilih Notepad dari daftar aplikasi 
Pada Windows 10.
ketik “Notepad” pada kotak pencari di layar Start.

![1](https://user-images.githubusercontent.com/46732630/52913899-e2ccea80-32f4-11e9-8966-bbf56d041553.png)

# LANGKAH KEDUA

buka Program Notepad dan Ketikkan Kode di bawah ini di Program Notepad :

![2](https://user-images.githubusercontent.com/46732630/52929622-be662200-3377-11e9-833a-b1c85665a9a2.png)

# LANGKAH KETIGA

Kalau sudah saya ketik, Save AS. Untuk "Save As Type" Pilih "All Files". dan Beri Nama Filenya "latihan2.py" ".py" adalah ekstensi File Program Python.

![3](https://user-images.githubusercontent.com/46732630/52929687-06854480-3378-11e9-8bda-f5339d6bd253.png)

# LANGKAH KEEMPAT

buat file teks baru dari menu File -> New File. Sesaat kemudian akan tampil teks editor yang mirip seperti Notepad. Mari kita ketik beberapa perintah python yang sama seperti tutorial sebelumnya :

![4](https://user-images.githubusercontent.com/46732630/52929798-7398da00-3378-11e9-895c-996646a94b30.png)

# LANGKAH KELIMA

Kemudian mulai ketik codingannya text editor python dengan mengetik seperti dibawah ini :

print("==================================================")

print(" Nama  	: Winda Yulianti")

print(" Kelas 	: TI.18.A1")

print(" NIM 	: 311810518")

print("==================================================")

import random

jumlah = int(input("Masukan nilai n: "))

print()

for i in range(jumlah):

	i = random.uniform(0.0,0.5)
	print(i)
print("selesai")

berikut penjelasan tentang kodingan yang di atas :
n=input("Masukkan nilai n :") 
Sintaks ini berfungsi untuk memasukkan nilai "n"
for i in range(jumlah):
Pada sintaks ini akan menampilkan perulangan bilangan random yang nilai nya sesuai dengan nilai n yang di input sebelumnya.
n= random.uniform(0.0, 0.5) 
random.uniform digunakan untuk menampilkan bilangan float random dengan batas awal bilangan x, dan batas akhir bilangan y. Pada sintaks ini akan menampilkan bilangan random yang batas awalnya 0.0, dan batas akhirnya 0.5.

# LANGKAH KEENAM

Lalu simpan file dengan cara pilih menu File -> Save As atau bisa juga dengan menekan tombol CTRL+S. Kita bisa menyimpan file ini dimana saja, namun agar lebih rapi saya akan menyimpannya di D:\python\ dengan nama file latihan2.py. Folder ini sudah kita buat dalam tutorial sebelumnya.

Untuk menjalankan kode python, pilih menu Run -> Run Module, atau bisa juga tekan tombol F5.
![6](https://user-images.githubusercontent.com/46732630/52930016-587a9a00-3379-11e9-8d76-1b43039ba0ff.png)

# LANGKAH KETUJUH

Hasil dari file python ini akan tampil di jendela awal IDLE Python.

![7](https://user-images.githubusercontent.com/46732630/52930049-8069fd80-3379-11e9-8079-c6ecbc0a1bfb.png)

Selesai

# latihan2.py
ALUR ALGORITMA latihan2.py Sebelum kita memulai.

# LANGKAH PERTAMA.
Buka Notepad. Pada Windows 10
bukalah menu "Start" Anda lalu ketik “Notepad” pada kotak pencari.
Pilih Notepad untuk membuka aplikasi tersebut. 
Anda juga dapat beralih ke folder “Accessories” pada menu "Start" lalu pilih Notepad dari daftar aplikasi 
Pada Windows 10.
ketik “Notepad” pada kotak pencari di layar Start.

![1](https://user-images.githubusercontent.com/46732630/52913899-e2ccea80-32f4-11e9-8966-bbf56d041553.png)

# LANGKAH KEDUA

buka Program Notepad dan Ketikkan Kode di bawah ini di Program Notepad :

![2](https://user-images.githubusercontent.com/46732630/52917995-386cbb80-3324-11e9-87ca-b6bd0f6dbe24.png)

# LANGKAH KETIGA

Kalau sudah saya ketik, Save AS. Untuk "Save As Type" Pilih "All Files". dan Beri Nama Filenya "latihan2.py" ".py" adalah ekstensi File Program Python.

![3](https://user-images.githubusercontent.com/46732630/52917982-ffcce200-3323-11e9-9262-b3454a91630b.png)

# LANGKAH KEEMPAT

buat file teks baru dari menu File -> New File. Sesaat kemudian akan tampil teks editor yang mirip seperti Notepad. Mari kita ketik beberapa perintah python yang sama seperti tutorial sebelumnya :

![4](https://user-images.githubusercontent.com/46732630/52917892-df505800-3322-11e9-8c6f-75307e38a87f.png)

# LANGKAH KELIMA

Kemudian mulai ketik codingannya text editor python dengan mengetik seperti dibawah ini :

print("=======================================")
print(" Nama  : Winda Yulianti") 
print(" Kelas : TI.18.A1")
print(" NIM   : 311810518")
print("=======================================")

max = 0

while True:
a=int(input("Masukkan bilangan :"))
if max < int(a):
max = int(a)
if a == 0:
break
print(max)

berikut penjelasan tentang kodingan yang di atas :
"while" : disebut uncounted loop (perulangan yang tak terhitung), untuk perulangan yang memiliki syarat dan tidak tentu berapa banyak perulangannya. "int" : berfungsi mengkonversi bilangan maupun string angka menjadi bilangan bulat (integer). "if" = Bila suatu kondisi tertentu tercapai maka apa yang harus dilakukan. Dengan fungsi ini kita bisa menjalankan suatu perintah dalam kondisi tertentu. "break" : fungsi yang menghentikan operasi dibawahnya jika suatu kondisi yang ditentukan telah tercapai.ange yang ditentukan dari start sampai stop. "\nTotal" = Membuat garis baru, dan menampilkan total hasil dari apa yang kita inginkan.

# LANGKAH KEENAM

Lalu simpan file dengan cara pilih menu File -> Save As atau bisa juga dengan menekan tombol CTRL+S. Kita bisa menyimpan file ini dimana saja, namun agar lebih rapi saya akan menyimpannya di D:\python\ dengan nama file latihan2.py. Folder ini sudah kita buat dalam tutorial sebelumnya.

Untuk menjalankan kode python, pilih menu Run -> Run Module, atau bisa juga tekan tombol F5.
![5](https://user-images.githubusercontent.com/46732630/52917798-14a87600-3322-11e9-97de-35fa5c7ee96b.png)

# LANGKAH KETUJUH

Hasil dari file python ini akan tampil di jendela awal IDLE Python.

![6](https://user-images.githubusercontent.com/46732630/52917759-cf844400-3321-11e9-809f-86572475e3a5.png)

Selesai


# Program1.py
ALUR ALGORITMA Program1.py Sebelum kita memulai.

# LANGKAH PERTAMA
Buka Notepad. Pada Windows 10
bukalah menu "Start" Anda lalu ketik “Notepad” pada kotak pencari.
Pilih Notepad untuk membuka aplikasi tersebut. 
Anda juga dapat beralih ke folder “Accessories” pada menu "Start" lalu pilih Notepad dari daftar aplikasi 
Pada Windows 10.
ketik “Notepad” pada kotak pencari di layar Start 👍 

![1](https://user-images.githubusercontent.com/46732630/52913899-e2ccea80-32f4-11e9-8966-bbf56d041553.png)

# LANGKAH KEDUA

buka Program Notepad dan Ketikkan Kode di bawah ini di Program Notepad :

![2](https://user-images.githubusercontent.com/46732630/52928304-9d9ace00-3371-11e9-9953-9582411b6ebc.png)

# LANGKAH KETIGA

Kalau sudah saya ketik, Save AS. Untuk "Save As Type" Pilih "All Files". dan Beri Nama Filenya "Program1.py" ".py" adalah ekstensi File Program Python :

![3](https://user-images.githubusercontent.com/46732630/52928549-e69f5200-3372-11e9-9511-40453be36070.png)

# LANGKAH KEEMPAT

buat file teks baru dari menu File -> New File. Sesaat kemudian akan tampil teks editor yang mirip seperti Notepad. Mari kita ketik beberapa perintah python yang sama seperti tutorial sebelumnya :

![4](https://user-images.githubusercontent.com/46732630/52928606-4138ae00-3373-11e9-9351-071536bcb82e.png)

# LANGKAH KELIMA

Kemudian mulai ketik codingannya text editor python dengan mengetik seperti dibawah ini :

print("=======================================")
print(" Nama  : Winda Yulianti") 
print(" Kelas : TI.18.A1")
print(" NIM   : 311810518")
print("=======================================")

a = 100000000
for x in range(1,9):
	if(x>=1 and x<=2):
		b=a*0
		print("Laba Bulan Ke-",x," :",b)
	if(x>=3 and x<=4):
		c=a*0.1
		print("Laba Bulan Ke-",x," :",c)
	if(x>=5 and x<=7):
		d=a*0.5
		print("Laba Bulan Ke-",x," :",d)
	if(x==8):
		e=a*0.2
		print("Laba Bulan Ke-",x," :",e)
total = b+b+c+c+d+d+d+e
print("\nTotal : ", total)

berikut penjelasan tentang kodingan yang di atas :

a = 100000000 for x in range(1,9): if(x>=1 and x<=2): b=a0 print('Laba bulan ke-',x,' :',b) if(x>=3 and x<=4): c=a0.1 print('Laba bulan ke-',x,' :',c) if(x>=5 and x<=7): d=a0.5 print('Laba bulan ke-',x,' :',d) if(x==8): e=a0.2 print('Laba bulan ke-',x,' :',e) total = b+b+c+c+d+d+d+e print('\nTotal : ', total)
"print" = Fungsi "print()" berfungsi untuk mencetak atau menampilkan objek ke perangkat keluaran (Layar). "if" = Bila suatu kondisi tertentu tercapai maka apa yang harus dilakukan. Dengan fungsi ini kita bisa menjalankan suatu perintah dalam kondisi tertentu. "for" = Perulangan yang terhitung. "range" = Mengembalikan deret integer berurut pada range yang ditentukan dari start sampai stop. "for x in range" = "for" perulangan yang terhitung, dan "range" mengembalikan deret integer berurut pada range yang ditentukan dari start sampai stop. "\nTotal" = Membuat garis baru, dan menampilkan total hasil dari apa yang kita inginkan.

# LANGKAH KEENAM

Lalu simpan file dengan cara pilih menu File -> Save As atau bisa juga dengan menekan tombol CTRL+S. Kita bisa menyimpan file ini dimana saja, namun agar lebih rapi saya akan menyimpannya di D:\python\ dengan nama file Program1.py. Folder ini sudah kita buat dalam tutorial sebelumnya.

Untuk menjalankan kode python, pilih menu Run -> Run Module, atau bisa juga tekan tombol F5.
![6](https://user-images.githubusercontent.com/46732630/52929164-d63ca680-3375-11e9-97a1-2df14571125c.png)

# LANGKAH KETUJUH

Hasil dari file python ini akan tampil di jendela awal IDLE Python.

![7](https://user-images.githubusercontent.com/46732630/52929215-0dab5300-3376-11e9-9f5a-be4e84071808.png)

Selesai


Demikian saya ketik ini atas perhatian ucapakan terimakasih

Winda Yulianti

TI.18.A1

311810518
