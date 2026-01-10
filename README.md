# Magic Chess Go Go Enemy Predictor

Sebuah alat prediksi musuh otomatis untuk game strategi turn-based seperti Auto Chess. Alat ini membantu pemain memprediksi lawan yang akan dihadapi di ronde-ronde berikutnya berdasarkan sistem eliminasi.

## Fitur Utama

- ✅ Input daftar musuh ronde 1-7 (dapat menggunakan nama bebas atau default Player 1-8)
- ✅ Sistem prediksi otomatis untuk ronde 8+
- ✅ Penandaan pemain yang kalah/eliminasi
- ✅ Tabel interaktif untuk melacak status musuh
- ✅ Penyimpanan data lokal (localStorage) - tetap tersimpan setelah refresh
- ✅ Responsif dan ramah mobile
- ✅ Tanpa framework - hanya HTML, CSS, JavaScript murni

## Teknologi yang Digunakan

- HTML5
- CSS3 (Flexbox/Grid)
- Vanilla JavaScript
- localStorage API

## Cara Pemakaian

### 1. Pengaturan Awal
- Masukkan nama musuh untuk ronde 1-7 di kolom input
- Klik tombol **"Simpan Musuh"** untuk menyimpan daftar awal

### 2. Prediksi Ronde Berikutnya
- Klik tombol **"Prediksi Ronde Berikutnya"** untuk menampilkan musuh ronde 8+
- Sistem akan otomatis memilih musuh berdasarkan daftar aktif yang tersisa

### 3. Menandai Pemain yang Kalah
- Klik tombol **"Kalah"** di sebelah musuh yang telah dikalahkan
- Pemain tersebut akan dieliminasi dari rotasi prediksi selanjutnya

### 4. Reset Data
- Gunakan tombol **"Reset"** untuk membersihkan semua data dan memulai ulang

## Logika Prediksi

- Ronde 1-7 diisi manual oleh pengguna
- Ronde 8+ menggunakan sistem rotasi berdasarkan daftar musuh aktif
- Jika ada pemain yang kalah, sistem akan melewati mereka dan melanjutkan ke pemain berikutnya
- Rotasi berjalan secara siklus (loop) antar pemain aktif

## Instalasi Lokal

1. Clone atau download repository ini
2. Buka file `index.html` di browser
3. Aplikasi siap digunakan tanpa perlu server

## Kontribusi

Kontribusi sangat diterima! Silakan buat pull request untuk:
- Bug fixes
- Penambahan fitur
- Peningkatan UI/UX
- Optimasi performa

## Lisensi

Proyek ini bersifat open-source dan bebas digunakan untuk keperluan pribadi maupun komersial.
