MARS MUSIC PLAYER: APLIKASI MUSIC PLAYER BERBASIS PYTHON (TKINTER)

Oleh kelompok 11: 
1. Ariba Raihana Alyashila 
2. Shindy Yusnidha Azzahra 
3. Retno Eka Sari

## Deskripsi Proyek
Proyek MARS Music Player adalah sebuah aplikasi pemutar musik desktop standalone yang dikembangkan menggunakan bahasa pemrograman Python dengan antarmuka grafis (GUI) yang dibangun menggunakan toolkit Tkinter. Aplikasi ini dirancang untuk mendemonstrasikan implementasi fundamental dari konsep Struktur Data tingkat lanjut, terutama Doubly Linked List, dalam skenario aplikasi nyata (pengelolaan antrian pemutaran/playlist). Selain itu, sistem ini menerapkan manajemen otentikasi sederhana untuk memisahkan hak akses antara Administrator dan Pengguna.

## Fitur Utama
* **Autentikasi Pengguna:** Mode login untuk Administrator dan Pengguna biasa (User).
* **Kontrol Akses:** Pengguna hanya dapat memutar lagu, sementara Admin memiliki akses penuh (tambah, hapus, kelola).
* **Manajemen Lagu (Admin Only):** Admin dapat menambahkan lagu secara manual (per file) atau memasukkan seluruh folder musik sekaligus.
* **Struktur Data:** Penggunaan Doubly Linked List untuk mengatur antrian pemutaran.
* **Auto-Load Lagu:** Aplikasi otomatis memuat lagu dari folder `music` di direktori proyek.
* **Fitur Player:** Play, Pause, Next, Previous, Shuffle, dan Pencarian.

## Cara Menjalankan Aplikasi

### Persyaratan
1.  Python 3.x
2.  Library `pygame` (untuk memutar musik).
3.  Library `mutagen` (untuk membaca metadata lagu).

### Instalasi Library
Buka Terminal/CMD di direktori proyek Anda dan jalankan perintah ini:
```bash
pip install pygame mutagen
```

## Eksekusi Program
Kemudian bisa jalankan aplikasinya
```bash
python MARS.py
```
