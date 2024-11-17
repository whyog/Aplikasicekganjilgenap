# 🚀 Aplikasi GUI Cek Nomor Genap/Ganjil

Selamat datang di proyek ini! 🎉 Proyek ini adalah implementasi GUI berbasis Java untuk memeriksa apakah sebuah angka adalah bilangan genap/ganjil, dilengkapi dengan fitur tambahan seperti validasi input, pengecekan bilangan prima, dan pembersihan input secara otomatis.

---

## 👨‍💻 Tentang Saya

Halo! Nama saya **Nur Yoga Andika** 👋  
- 📚 **NPM:** 2210010652  
- 🎓 **Jurusan:** Teknologi Informasi  
- 🌟 Saya selalu berusaha belajar hal-hal baru dan berbagi apa yang saya pelajari.  

💬 Jangan ragu untuk menghubungi saya untuk berdiskusi lebih lanjut tentang proyek ini atau topik lainnya! 🚀  

---

## 📝 Deskripsi Program

Aplikasi ini memungkinkan pengguna:
1. Memasukkan **angka** melalui `JTextField`.
2. Menekan tombol:
   - **Cek:** Untuk memvalidasi angka dan menampilkan hasil apakah angka tersebut genap/ganjil serta bilangan prima.
   - **Hapus:** Untuk menghapus input dan memulai dari awal.
   - **Keluar:** Untuk menutup aplikasi dengan mudah.

Aplikasi ini juga menggunakan fitur tambahan seperti:
- Validasi input untuk memastikan hanya angka yang dapat dimasukkan.
- **JOptionPane** untuk menampilkan pesan hasil atau kesalahan.

---

## 💻 Komponen GUI

Berikut adalah komponen utama yang digunakan dalam aplikasi ini:
- **JFrame:** Sebagai jendela utama aplikasi.
- **JPanel:** Mengatur tata letak komponen GUI.
- **JLabel:** Menampilkan label teks.
- **JTextField:** Untuk memasukkan angka.
- **JButton:** Untuk melakukan tindakan seperti cek, hapus, dan keluar.

---

## 🔍 Logika Program

1. **Kondisional (if-else):**
   - Menentukan apakah angka yang dimasukkan adalah bilangan genap atau ganjil.
   - Menentukan apakah angka tersebut bilangan prima.
2. **Validasi input:**
   - Menggunakan `KeyAdapter` untuk membatasi input hanya angka.
3. **Fitur tambahan:**
   - **JOptionPane** untuk menampilkan pesan hasil dan kesalahan.
   - **FocusListener** untuk membersihkan `JTextField` saat mendapatkan fokus.

---

## 🎯 Events yang Diimplementasikan

1. **ActionListener:**  
   - Untuk tombol **Cek**, memproses validasi dan pengecekan angka.  
   - Untuk tombol **Hapus**, menghapus input yang dimasukkan.
   - Untuk tombol **Keluar**, menutup aplikasi.

2. **KeyAdapter:**  
   - Membatasi input di `JTextField` hanya untuk angka.

3. **FocusListener:**  
   - Membersihkan `JTextField` saat mendapatkan fokus.

---

## ✨ Variasi

1. Memberikan informasi tambahan:
   - Apakah angka yang dimasukkan adalah bilangan prima.
   - Informasi genap atau ganjil pada angka tersebut.
2. Validasi input:
   - Menampilkan pesan kesalahan jika input kosong atau tidak valid.
3. Pengalaman pengguna yang lebih baik:
   - Membersihkan input otomatis saat field mendapatkan fokus.

---

## 🔧 Cara Menggunakan Program

1. Masukkan **angka** ke dalam `JTextField`.
2. Tekan tombol:
   - **Cek:** Lihat hasil apakah angka tersebut genap/ganjil dan apakah angka tersebut bilangan prima.
   - **Hapus:** Bersihkan input dan mulai dari awal.
   - **Keluar:** Tutup aplikasi dengan mudah.
3. Pesan hasil akan ditampilkan dalam dialog menggunakan `JOptionPane`.

---

## 📂 Struktur Proyek

