# 🍹 Aplikasi Pemesanan Minuman (Java Swing)

Aplikasi desktop berbasis Java Swing GUI yang digunakan untuk memproses transaksi pemesanan minuman secara otomatis. Aplikasi ini menghitung total biaya berdasarkan jenis minuman, ukuran gelas, serta topping yang dipilih, lalu menampilkan hasilnya dalam bentuk struk pemesanan.

---

## 📸 Tampilan Aplikasi

| Form Pemesanan | Struk Transaksi |
| :---: | :---: |
| Antarmuka input pilihan minuman, ukuran, tingkat gula, dan topping | Dialog pop-up berisi ringkasan pemesanan dan total bayar |

---

## ✨ Fitur Utama

* **Pilihan Jenis Minuman**: Pilih antara Kopi, Teh, atau Jus menggunakan `JRadioButton`.
* **Pilihan Ukuran Gelas**: Opsi *Small*, *Medium* (+Rp 3.000), dan *Large* (+Rp 5.000) menggunakan `JComboBox`.
* **Kustomisasi Tingkat Gula**: Pilihan *Tanpa Gula*, *Sedikit Gula*, atau *Gula Normal*.
* **Topping Tambahan**: Pilihan topping seperti *Bubble*, *Jelly*, *Cream*, *Keju* (+Rp 4.000) atau *Tanpa Topping*.
* **Validasi Pemesanan**: Menampilkan pesan peringatan jika pengguna belum memilih jenis minuman.
* **Cetak Struk Pemesanan**: Menghitung kalkulasi harga total dan menampilkan struk pemesanan lengkap via `JOptionPane`.
* **Reset Form**: Tombol untuk mengembalikan semua pilihan ke kondisi awal (default).

---

## 💰 Struktur Pricing / Harga

| Komponen | Pilihan | Tambahan Harga |
| :--- | :--- | :--- |
| **Minuman** | Kopi<br>Teh<br>Jus | Rp 15.000<br>Rp 10.000<br>Rp 18.000 |
| **Ukuran** | Small<br>Medium<br>Large | +Rp 0<br>+Rp 3.000<br>+Rp 5.000 |
| **Topping** | Tanpa Topping<br>Lainnya (Bubble, Jelly, Cream, Keju) | +Rp 0<br>+Rp 4.000 |

---

## 🛠️ Teknologi & Tools

* **Bahasa Pemrograman**: Java (JDK 17/21+)
* **GUI Library**: Java Swing (`javax.swing`)
* **IDE**: Apache NetBeans 30+

---

## 🚀 Cara Menjalankan Proyek

1. **Clone Repositori**
   ```bash
   git clone [https://github.com/username-kamu/PemesananMinumApp.git](https://github.com/username-kamu/PemesananMinumApp.git)
