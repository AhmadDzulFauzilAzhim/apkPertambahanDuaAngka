# Aplikasi Pertambahan Dua Angka

Aplikasi ini adalah program sederhana berbasis Java menggunakan **Swing** untuk membuat GUI. Aplikasi ini berfungsi untuk melakukan operasi penjumlahan antara dua angka yang dimasukkan oleh pengguna. Program ini memiliki fitur validasi input, penghapusan data, dan konfirmasi keluar.

---

## Fitur
1. **Penjumlahan Angka**
   - Pengguna dapat memasukkan dua angka pada kolom yang tersedia.
   - Hasil penjumlahan akan ditampilkan menggunakan kotak dialog (*JOptionPane*).

2. **Validasi Input**
   - Program hanya menerima angka sebagai input. Jika pengguna mencoba memasukkan karakter non-angka, maka pesan kesalahan akan ditampilkan.

3. **Hapus Data**
   - Pengguna dapat menghapus input dengan menekan tombol "Hapus".
   - Program juga akan menampilkan pesan konfirmasi bahwa data telah dihapus.

4. **Keluar dari Program**
   - Tombol "Keluar" memungkinkan pengguna untuk keluar dari aplikasi.
   - Sebelum keluar, program akan meminta konfirmasi dari pengguna.

---

## Cara Penggunaan
1. Jalankan aplikasi dengan menjalankan file `.jar` atau langsung menjalankan file `.java` melalui IDE.
2. Masukkan angka pertama pada kolom input **angka1**.
3. Masukkan angka kedua pada kolom input **angka2**.
4. Klik tombol **Hitung** untuk melihat hasil penjumlahan.
5. Gunakan tombol **Hapus** untuk menghapus angka yang dimasukkan.
6. Tekan tombol **Keluar** untuk menutup aplikasi (konfirmasi akan diminta).

---

## Struktur Program
1. **GUI**:
   - Menggunakan komponen seperti `JPanel`, `JButton`, `JTextField`, dan `JLabel` untuk membangun antarmuka pengguna.

2. **Validasi Input**:
   - Memastikan input dari pengguna adalah angka menggunakan metode `KeyTyped` pada `JTextField`.

3. **Event Handling**:
   - Menggunakan `ActionListener` untuk menangani aksi pengguna pada tombol-tombol tertentu.

---

## Teknologi yang Digunakan
- Bahasa Pemrograman: **Java**
- Library: **Swing** untuk GUI

---

## Pengembangan Lebih Lanjut
Beberapa ide pengembangan aplikasi ini:
1. Tambahkan fitur operasi matematika lain seperti pengurangan, perkalian, dan pembagian.
2. Buat tampilan GUI yang lebih menarik menggunakan library seperti **JavaFX**.
3. Simpan riwayat perhitungan menggunakan file atau database.

---

## Catatan
- Pastikan Anda memiliki JDK terinstal untuk menjalankan program ini.
- Gunakan editor seperti **NetBeans**, **IntelliJ IDEA**, atau **Eclipse** untuk mengedit dan menjalankan kode.

---

## Pembuat Aplikasi
Ahmad Dzul Fauzil Azhim - 2210010389

## Demo

![App Screenshot](https://github.com/AhmadDzulFauzilAzhim/apkPertambahanDuaAngka/blob/main/img/demo%20aplikasi%20pertambahan%20dua%20angka.gif)
