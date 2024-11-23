# Labpy05
# Tugaas Pemrograman P10

![Screenshot 2024-11-23 131916](https://github.com/user-attachments/assets/ba5e0edf-bf9a-472d-8e65-be69a11fa289)
![Screenshot 2024-11-23 132117](https://github.com/user-attachments/assets/ecc6b668-30d1-4db6-b275-7597c358e08c)
![Screenshot 2024-11-23 132349](https://github.com/user-attachments/assets/0c944637-a5cc-4f48-ac2b-446f1f3a1a37)
![Screenshot 2024-11-23 132433](https://github.com/user-attachments/assets/2c10296c-64bb-426c-9af1-e1646b89a42d)
![Screenshot 2024-11-23 132456](https://github.com/user-attachments/assets/db5585e8-5cad-4319-81cc-213ca91cd1d8)

# Penjelasan Program
Berikut adalah penjelasan mengenai program sederhana yang mengelola daftar nilai mahasiswa menggunakan Python dengan struktur data dictionary. Program ini memungkinkan pengguna untuk menambah, mengubah, menghapus, menampilkan, dan mencari data mahasiswa.

# 1. Struktur Data:
 - Program menggunakan dictionary (`dataMahasiswa`) untuk menyimpan data mahasiswa. Nama mahasiswa menjadi kunci (key), dan nilai-nilai (NIM, nilai tugas, UTS, UAS, dan nilai 
   akhir) disimpan dalam dictionary terpisah sebagai nilai (value).
   
# 2.Fungsi-Fungsi:
 - `tambah_data()`:
   - Fungsi ini meminta pengguna untuk memasukkan nama, NIM, dan nilai untuk tugas, UTS, dan UAS.
   - Menghitung nilai akhir dengan rumus: [ \text{Nilai Akhir} = (0.30 \times \text{Tugas}) + (0.35 \times \text{UTS}) + (0.35 \times \text{UAS}) ]
   - Menyimpan semua data ke dalam dictionary `dataMahasiswa`.

 - `tampilkan_data()`:
   - Fungsi ini menampilkan semua data mahasiswa dalam format tabel.
   - Fungsi ini menampilkan semua data mahasiswa dalam format tabel.

 - `ubah_data()`:
   - Meminta pengguna untuk memasukkan nama mahasiswa yang ingin diubah
   - Jika nama ditemukan, pengguna akan diminta untuk memasukkan nilai baru.
   - Jika nama ditemukan, pengguna akan diminta untuk memasukkan nilai baru.
     
 - `hapus_data():`
   - Meminta pengguna untuk memasukkan nama mahasiswa yang ingin dihapus.
   - Jika nama ditemukan, data mahasiswa akan dihapus dari dictionary.
  
 - `cari_data()`:
   - Meminta pengguna untuk memasukkan nama mahasiswa untuk dicari.
   - Jika ditemukan, akan menampilkan detail nilai mahasiswa tersebut.

# Menu Utama:
 - Program menggunakan loop `while True` untuk menampilkan menu utama yang memungkinkan pengguna memilih opsi yang diinginkan (menambah, menampilkan, mengubah, menghapus, 
   atau mencari data mahasiswa, atau keluar dari program).
