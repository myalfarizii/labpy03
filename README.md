# labpy03
TUGAS PRAKTIKUM 3 

Nama : Muhammad Yunus Alfarizi

Nim : 352310842

Kelas : IE.23.C12

LATIHAN 1 intruksi perintah :

1. Tampilkan nilai n bilangan acak yang lebih kecil dari 0.5
2. Nilai n diisi saat run time
3. Menggunakan while atau for
4. Menggunakan fungsi random

Screenshoot Hasil Program yang dibuat
![latihan 2 yunusCapture](https://github.com/user-attachments/assets/076538be-099c-46cb-8b34-58183a522ecb)
Algoritma dan penjelasan

1. Pertama kita buat program terlebih dahulu menggunakan Idle

2. Saat membuat program, yang pertama kita buat sistem input terlebih dahulu agar kita bisa menginput suatu bilangan saat di runtime dengan rumus n = int(input("Masukkan jumlah bilangan acak yang ingin ditampilkan: "))

3. Selanjutnya kita nisialisasi variabel untuk menghitung jumlah bilangan yang telah ditampilkan dengan rumus count = 0

4. Selanjutnya kita akan Menggunakan while untuk terus menghasilkan bilangan acak sampai mencapai n, dengan rumus while count < n:

5. Selanjutya kita akan menghasilkan bilangan acak dengan a = random()

6. Selanjutnya Memeriksa apakah bilangan acak kurang dari 0.5, rumus: if a < 0.5: count += 1 # Menambah hitungan bilangan yang ditampilkan print(f"Data ke : {count} => {a}")
   Menampilkan bilangan acak dengan format yang diinginkan
7. Selesai


LATIHAN 2 
Intruksi : Buat program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan. Masukkan angka 0 untuk berhenti.

Screenshot Hasil Dari Program yang dibuat
![Capture latihan 2](https://github.com/user-attachments/assets/aeaef81b-e648-44e8-82db-506ad430315e)
Algoritma dan penjelasan

1. Pertama kita buat program terlebih dahulu menggunakan Idle

2. Kita buat Inisialisasi variabel untuk menyimpan bilangan terbesar dengan rumus max_number = None

3. Selanjutnya kita buat while true : Mengambil input dari pengguna,

4. Memeriksa apakah pengguna memasukkan 0, Memperbarui bilangan terbesar jika diperlukan

5. Selanjutnya kita akan menamplkan bilangan terbesarnya dengan rumus, if max_number is not None: print("Bilangan terbesar adalah:", max_number) else: ("Tidak ada angka yang dimasukkan.")

6. Selesai

PROGRAM 1 Intruksi : Seorang pengusaha menginvestasikan uangnya untuk memulai usahanya dengan modal awal 100 juta, pada bulan pertama dan kedua belum mendapatkan laba. pada bulan ketiga baru mulai mendapatkan laba sebesar 1% dan pada bulan ke 5, pendapatan meningkat 5%, selanjutnya pada bulan ke 8 mengalami penurunan keuntungan sebesar 2%, sehingga laba menjadi 3%. Hitung total keuntungan selama 8 bulan berjalan usahanya.

Screenshot Hasil Dari Program yang dibuat
![Capture latihan 3  yunus ](https://github.com/user-attachments/assets/8f5ebfbf-ec06-4f25-916c-d39ad822ca30)
Algoritma dan penjelasan

1. Pertama kita buat program terlebih dahulu menggunakan Idle
2. Buat print modal awal,rumus :modal_awal = 100_000_000
3. Kita buat nisialisasi list untuk menyimpan laba setiap bulan dengan menggunakan statement for, in, If, elif
4. Menghitung total laba dengan rumus SUM
5. Menampilkan hasil dengan rumus For 1 in
6. Selesai
