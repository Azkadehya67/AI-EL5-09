# Search Algorithm: Penyelesaian Labirin

## 1. Pendahuluan

Proyek Search Algorithm mendemonstrasikan penggunaan teknik pencarian dalam kecerdasan buatan untuk menyelesaikan permasalahan navigasi pada labirin.

Program merepresentasikan labirin sebagai ruang pencarian yang terdiri atas titik awal, titik tujuan, dan rintangan. Algoritma pencarian akan menelusuri jalur-jalur yang tersedia untuk menentukan apakah titik tujuan dapat dicapai.

Proyek ini mengimplementasikan Breadth-First Search (BFS) dan Depth-First Search (DFS) untuk menunjukkan perbedaan strategi dalam menelusuri keadaan dan menemukan jalur.

## 2. Persyaratan

Persyaratan untuk menjalankan proyek ini meliputi:

- Python versi 3.10 atau lebih baru (disarankan).
- Editor kode, seperti Visual Studio Code.
- Terminal atau Command Prompt.
- Berkas sumber program main.py.

Implementasi dasar dapat dijalankan menggunakan pustaka standar Python, kecuali jika terdapat dependensi tambahan pada kode program.

## 3. Cara Menggunakan

### Langkah 1: Membuka Direktori Proyek

bash
cd 02_Search_Algorithm


### Langkah 2: Menjalankan Program

bash
python main.py


### Langkah 3: Memilih atau Memeriksa Algoritma Pencarian

Ikuti instruksi program untuk menjalankan metode pencarian yang tersedia. Jika pemilihan algoritma dilakukan langsung melalui kode sumber, periksa konfigurasi yang sesuai sebelum menjalankan program.

### Langkah 4: Mengamati Proses Pencarian

Perhatikan keluaran program untuk mengetahui jalur yang ditelusuri algoritma dan apakah jalur menuju titik tujuan berhasil ditemukan.

## 4. Hasil

Program mendemonstrasikan cara algoritma pencarian menelusuri labirin untuk menemukan jalur dari titik awal menuju titik tujuan.

- *Breadth-First Search (BFS):* Menelusuri keadaan yang berdekatan secara bertingkat. Pada labirin tanpa bobot, BFS dapat menemukan jalur terpendek jika jalur tersebut tersedia.
- *Depth-First Search (DFS):* Menelusuri satu jalur sedalam mungkin sebelum kembali ke percabangan sebelumnya. DFS dapat menemukan jalur, tetapi tidak menjamin jalur terpendek.

Hasil program menunjukkan perbedaan kedua strategi dalam urutan penelusuran, penemuan jalur, dan proses penyelesaian masalah.

## Screenshot
![Hasil Running Search_Algorithm](screenshoot/02Running.jpeg)
