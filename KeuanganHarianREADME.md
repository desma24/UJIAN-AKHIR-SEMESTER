Penjelasan Kode:
Header Files: Menggunakan #include <iostream> untuk input dan output, dan #include <string> untuk menggunakan tipe data string.
Variabel:
saldo: Menyimpan saldo awal pengguna.
totalPengeluaran: Menyimpan total pengeluaran yang telah dicatat.
pilihan: Menyimpan pilihan menu pengguna.
kategori: Menyimpan kategori pengeluaran.
jumlah: Menyimpan jumlah pengeluaran.
Input Saldo Awal: Meminta pengguna untuk memasukkan saldo awal.
Loop do-while: Menampilkan menu utama dan meminta pengguna untuk memilih opsi hingga pengguna memilih untuk keluar.
Switch-case: Menggunakan struktur switch-case untuk menangani pilihan pengguna:
Tambah Pengeluaran: Meminta kategori dan jumlah pengeluaran, kemudian memperbarui total pengeluaran dan saldo.
Tampilkan Total Pengeluaran: Menampilkan total pengeluaran yang telah dicatat.
Tampilkan Sisa Saldo: Menampilkan sisa saldo saat ini.
Keluar: Menampilkan pesan perpisahan dan keluar dari aplikasi.
Validasi Pilihan: Jika pengguna memasukkan pilihan yang tidak valid, aplikasi akan memberikan pesan kesalahan.

Cara Menjalankan:
Salin kode di atas ke dalam file dengan ekstensi .cpp, misalnya keuangan_harian.cpp.
Kompilasi kode menggunakan compiler C++ (misalnya, g++) dengan perintah:
bash

Verify

Open In Editor
Run
Copy code
g++ keuangan_harian.cpp -o keuangan_harian
Jalankan program dengan perintah:
bash

Verify

Open In Editor
Run
Copy code
./keuangan_harian
