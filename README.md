# praktikum.8
Nama :Muflih Salda Maulana <P>
nim  :312410527 <p>
kelas:TI 24 A5 <p>
# FLOWCHART 
![flowchart](https://github.com/user-attachments/assets/aab21970-0ae3-4da2-8957-b976f6b69bd0)

# PENJELASAN PROGRAM
class Mahasiswa:
"""Kelas untuk merepresentasikan daftar mahasiswa."""

Kelas ini memiliki atribut daftar_mahasiswa, yang merupakan daftar untuk menyimpan data mahasiswa.
Metode tambah, tampilkan, hapus, dan ubah digunakan untuk mengelola data mahasiswa.

2. Metode __init__
def __init__(self):
self.daftar_mahasiswa = []
    
Konstruktor: Metode __init__ adalah konstruktor yang dipanggil saat objek dari kelas Mahasiswa dibuat.
Atribut daftar_mahasiswa: Atribut ini adalah list kosong yang akan digunakan untuk menyimpan data mahasiswa dalam bentuk dictionary, di mana setiap dictionary berisi nama dan nilai.
3. Metode tambah

Verify
Copy code
def tambah(self, nama, nilai):
    """Menambah data mahasiswa."""
    self.daftar_mahasiswa.append({'nama': nama, 'nilai': nilai})
    print(f"Data mahasiswa {nama} berhasil ditambahkan.")
Fungsi: Metode ini digunakan untuk menambahkan data mahasiswa baru ke dalam daftar_mahasiswa.
Parameter: Menerima dua parameter, nama dan nilai.
Proses: Data mahasiswa ditambahkan ke dalam list sebagai dictionary, dan pesan konfirmasi ditampilkan.
