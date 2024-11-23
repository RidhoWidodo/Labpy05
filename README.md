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

# 3. Menu Utama:
 - Program menggunakan loop `while True` untuk menampilkan menu utama yang memungkinkan pengguna memilih opsi yang diinginkan (menambah, menampilkan, mengubah, menghapus, 
   atau mencari data mahasiswa, atau keluar dari program).

# Flowchart 
![flowchart praktikum6](https://github.com/user-attachments/assets/a470ac9f-d731-4795-b88e-ec64e505b35d)

# Berikut adalah deskripsi flowchart yang menggambarkan alur program:
 - Mulai: Program dimulai.
 - Tampilkan Menu: Menampilkan pilihan menu (Tambah Data, Ubah Data, Hapus Data, Tampilkan Data, Cari Data, Keluar).
 - Pilih Menu: Pengguna memilih opsi dari menu.
   - Jika "Tambah Data", jalankan fungsi `tambah_data`().
   - Jika "Tampilkan Data", jalankan fungsi `tampilkan_data`().
   - Jika "Ubah Data", jalankan fungsi `ubah_data`().
   - Jika "Hapus Data", jalankan fungsi `hapus_data`().
   - Jika "Cari Data", jalankan fungsi `cari_data`().
   - jika "Keluar", keluar dari loop dan program selesai.
 - Kembali ke Menu: Setelah menjalankan fungsi, kembali ke langkah 2 untuk menampilkan menu lagi.

# Contoh Penggunaan
 - Menambah Data:
    - Pengguna memasukkan nama, NIM, dan nilai untuk tugas, UTS, dan UAS. Program menghitung dan menyimpan nilai akhir.
 - Menampilkan Data:
    - rogram menampilkan semua data mahasiswa dalam tabel.
 - Mengubah Data:
    - Pengguna memasukkan nama mahasiswa yang ingin diubah dan nilai baru. Program memperbarui data
 - Pengguna memasukkan nama mahasiswa yang ingin diubah dan nilai baru. Program memperbarui data
    - Pengguna memasukkan nama mahasiswa yang ingin dihapus. Program menghapus data tersebut.
 - Pengguna memasukkan nama mahasiswa yang ingin dihapus. Program menghapus data tersebut.
    - Pengguna memasukkan nama mahasiswa yang ingin dihapus. Program menghapus data tersebut.

# Contoh Output

#  - Tambah Data
    
![Screenshot 2024-11-23 144711](https://github.com/user-attachments/assets/9d7ccd24-e410-482f-8538-cea3aa989fe1)

#  - Tampilkan Data
    
![Screenshot 2024-11-23 145024](https://github.com/user-attachments/assets/efb81301-45ed-4854-b645-7f1b3c422c9b)

#  - Ubah Data
    
![Screenshot 2024-11-23 145813](https://github.com/user-attachments/assets/c92ba354-65cc-44a3-b56c-8d597173cb92)

#  - Hapus Data
    
![Screenshot 2024-11-23 150039](https://github.com/user-attachments/assets/31c113c0-3b0e-4bfd-ac23-d10a6b98f356)

# - Cari Data

![Screenshot 2024-11-23 150226](https://github.com/user-attachments/assets/44065cd5-f76e-4a93-8d32-b72a49983ad4)

# - Keluar
   
![Screenshot 2024-11-23 150317](https://github.com/user-attachments/assets/4ace6ddf-a228-4ea4-ae52-33a6711aa03b)
