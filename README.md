1. flowchart & code untuk menentukan bilangan terbesar dari 3 buah bilangan yang diinputkan

   A.	Penjelasan flowchart untuk menentukan bilangan terbesar dari 3 buah bilangan yang diinputkan
Menjelaskan detail flowchart tersebut yang menampilkan algoritma untuk mencari bilangan terbesar dari 3 bilangan:
 1.  Mulai 
o	Program dimulai dengan input 3 bilangan: bil1, bil2, dan bil3
 2.	Proses Input 
o	Memasukkan bil1
o	Memasukkan bil2
o	Memasukkan bil3
 3.	Proses Perbandingan (ada 2 tahap) 
o	Tahap 1: Membandingkan bil1+bil2+bil3 > bil1 
	Jika Ya: Terbesar = bil1
	Jika Tidak: Lanjut ke tahap 2
o	Tahap 2: Membandingkan bil2>bil3 
	Jika Ya: Terbesar = bil2
	Jika Tidak: Terbesar = bil3
 4.	Output 
o	Menampilkan nilai "Terbesar = [nilai]"
o	Nilai yang ditampilkan adalah bilangan yang paling besar di antara ketiga bilangan input
 5.	Selesai 
o	Program berakhir setelah menampilkan output
Flowchart ini merupakan algoritma sederhana untuk menentukan nilai terbesar dari 3 bilangan yang diinputkan. Prosesnya menggunakan perbandingan bertingkat untuk memastikan bilangan terbesar ditemukan dengan benar.
Saat dijalankan, program akan:
  1.	Meminta input 3 bilangan
  2.	Membandingkan bilangan-bilangan tersebut
  3.	Menentukan bilangan terbesar
  4.	Menampilkan hasilnya
  5.	Mengakhiri program




B.	Penjelasan dari pseudocode untuk menentukan bilangan terbesar dari  3 buah bilangan :
 1.	Definisi Fungsi:
def cari_terbesar():
•	Ini menciptakan sebuah fungsi bernama cari_terbesar(berarti "menemukan yang terbesar" dalam bahasa Indonesia)
•	Tanda kurung kosong ()berarti tidak ada parameter yang diambil
 2.	Bagian Input:
print("Masukkan 3 bilangan:")
bil1 = float(input("Masukkan bilangan pertama: "))
bil2 = float(input("Masukkan bilangan kedua: "))
bil3 = float(input("Masukkan bilangan ketiga: "))
•	Meminta pengguna untuk memasukkan 3 angka
•	input()menerima input pengguna sebagai string
•	float()mengubah string input menjadi angka desimal
•	Nilai disimpan dalam variabel bil1, bil2, danbil3
 3.	Logika Perbandingan:
terbesar = None  # Initialize variable to store largest number

if bil1 >= bil2 and bil1 >= bil3:  # If bil1 is >= both bil2 and bil3
    terbesar = bil1
elif bil2 >= bil3:                 # If bil2 is >= bil3
    terbesar = bil2
else:                             # If neither above is true
    terbesar = bil3
Ini adalah logika inti yang membandingkan angka-angka:
•	Pertama periksa apakah bil1itu terbesar dengan membandingkannya dengan kedua angka lainnya
•	Jika bil1tidak terbesar, periksa apakah bil2lebih besar daribil3
•	Jika tidak ada yang benar, bil3maka harus menjadi yang terbesar
 4.	Bagian Keluaran:
print("\nBilangan yang dimasukkan:", bil1, bil2, bil3)
print("Bilangan terbesar adalah:", terbesar)
•	Menampilkan nomor input
•	Menunjukkan angka mana yang terbesar
 5.	Eksekusi Program Utama:
if __name__ == "__main__":
    print("Program Mencari Bilangan Terbesar dari 3 Bilangan")
    print("===============================================")
    cari_terbesar()
•	Ini adalah idiom Python standar yang menjalankan kode hanya jika file dijalankan secara langsung
•	Mencetak judul/header
•	Memanggil cari_terbesar()fungsi untuk memulai program
Misalnya, jika Anda memasukkan:
•	Angka pertama: 10
•	Angka kedua: 5
•	Angka ketiga: 7
Program ini akan:
  1.	Bandingkan 10 dengan 5 dan 7 (10 ≥ 5 dan 10 ≥ 7 adalah benar)
  2.	Mengaturterbesar = 10
  3.	Tampilkan bahwa 10 adalah angka terbesar


2. flowchart & code untuk menentukan bilangan terbesar dari N bilangan yang diinputkan, untuk menentukan jumlah N, berikan masukan angka 0.

   A. Penjelasan dari Flowchart untuk menentukan bilangan terbesar dari N bilangan yang diinputkan :
 1.	Mulai Program
•	Program dimulai dari simbol "Mulai"
•	Langkah pertama adalah menginisialisasi variabel Max = 0
 2.	Data Masukan
•	Program menerima masukan nilai N
•	Setelah input, dilakukan pengecekan kondisi pertama
 3.	Kondisi Pertama (N = 0)
•	Jika N = 0 (Ya): Program akan menampilkan nilai Max dan berakhir
•	Jika N ≠ 0 (Tidak): Program lanjut ke pengecekan kondisi kedua
 4.	Kondisi Kedua (N > Max)
•	Program membandingkan nilai N dengan nilai Max
•	Jika N > Max (Ya): Nilai Max akan diperbarui menjadi nilai N saat ini
•	Jika N ≤ Max (Tidak): Program kembali ke langkah input N
 5.	Perbarui Max
•	Jika N > Max, maka nilai Max diperbarui dengan nilai N
•	Setelah update, program kembali ke langkah input N
 6.	Output dan Selesai
•	Ketika N = 0, program akan menampilkan nilai Max terakhir
•	Program berakhir di simbol "Selesai"
   Tujuannya Flowchart ini dirancang untuk mencari nilai terbesar (maksimum) dari N kumpulan angka yang diinput. Program akan terus meminta input sampai pengguna memasukkan angka 0 sebagai penanda untuk mengakhiri input.
Cara Kerja:
  1.	Pengguna memasukkan angka satu per satu
  2.	Setiap angka dibandingkan dengan nilai maksimum yang ada
  3.	Jika angka baru lebih besar, maka itu menjadi nilai maksimum yang baru
  4.	Proses berlanjut sampai pengguna memasukkan 0
  5.	Program menampilkan nilai terbesar yang ditemukan




B. Penjelasan dari pseudocode untuk menentukan bilangan terbesar dari N bilangan yang diinputkan :
•  Menginisialisasi variabel Max dengan nilai 0 
•  Meminta input angka secara terus menerus 
•  Jika input = 0, program akan menampilkan nilai maksimum dan berhenti 
•  Jika input lebih besar dari nilai Max saat ini, nilai Max akan diupdate 
•  Proses akan terus berulang sampai pengguna memasukkan angka 0
   Misalnya, jika Anda memasukkan:
•	Max Angka pertama: 0
•	N Angka pertama: 6
•	Max Angka kedua menjadi: 6
•	N Angka kedua: 2
• Max Tetap Angka : 6 ( karena N<max )
•	N Angka ketiga: 12
•	Max Angka ketiga menjadi: 12
•	N Angka keempat: 0 ( Selesai )
   Program ini akan:
Membandingkan hinnga N = 0
•	Max = 0
N =  6
6 > 0
Max = 6

•	N = 2
2 < 6

•	N = 12
12 > 6
Max = 12

•	N = 0
0 < 12
Dari Hasil Flowchart & Code Diatas Mendapatkan Nilai max = 6, 12




