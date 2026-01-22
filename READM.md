# — LunchUp App

## 📌 Deskripsi Singkat
**LunchUp** adalah aplikasi pemesanan makanan yang memiliki beberapa role utama seperti **Admin**, **User/Pelanggan**, dan **Kurir/Jastiper**. Aplikasi menyediakan fitur autentikasi, pemesanan, manajemen menu, serta dashboard pendapatan.

---

## 🚀 Fitur Utama

### 1) Autentikasi (Authentication)
#### ✅ Login
- Splash/Login screen dengan branding **LunchUp**
- Form login:
  - Email / Username
  - Password
- Tombol **Sign in**
- State login contoh (email & password terisi)

#### ✅ Register
- Halaman pendaftaran akun baru
- Form register:
  - Username
  - Email
  - Password
- Tombol **Sign in** (submit daftar)
- Link navigasi:
  - “Already have account? Sign in”

---

## 👤 Role & Modul

## 🛠️ 2) Admin Module (Dashboard & Kelola Menu)

### ✅ Admin Dashboard (Home)
- Header “Admin Dashboard”
- Ringkasan statistik:
  - Total pendapatan (contoh: Rp 1.250.000)
  - Total pesanan (contoh: 42 Order)
- Quick menu:
  - **Menu**
  - **Pesanan**
- Daftar pesanan terbaru:
  - Menampilkan nama pesanan
  - Status (Pending / Done / Proses)

### ✅ Kelola Menu (CRUD Menu)
- Halaman “Kelola Menu”
- Search menu (cari menu kantin)
- List menu dengan detail:
  - Nama makanan
  - Harga (Rp)
  - Status ketersediaan (Tersedia / Habis)
- Aksi pada menu:
  - Edit (ikon pensil)
  - Delete (ikon tempat sampah)
- Floating button **Tambah Menu (+)**

---

## 🍔 3) User / Pelanggan Module

### ✅ Beranda / Daftar Produk
- List makanan dengan gambar
- Ada kategori atau section list (contoh burger)
- Navigasi bottom bar

### ✅ Detail Produk
- Foto makanan ukuran besar
- Nama produk + deskripsi
- Tombol **Add to Cart**

### ✅ Keranjang / Order Details
- List item makanan yang dipilih
- Kontrol jumlah item (+ / -)
- Ringkasan total harga

### ✅ Pembayaran (Payment)
- Halaman total pembayaran (contoh background merah)
- Komponen pembayaran:
  - Total
  - Payment method
  - Location (alamat)
  - Notes
- Tombol aksi:
  - **LET’S PAY**

### ✅ Status Pembayaran Berhasil
- Halaman success (tanda centang ✅)

### ✅ Profile User
- Foto profil user
- Data user:
  - Nama
  - Kelas/jurusan (contoh: XI RPL)
  - Gender (contoh: Laki-Laki)
- Tombol:
  - **Edit**
  - **Log out**

---

## 🛵 4) Kurir Module

### ✅ Beranda Kurir (New Requests)
- Menampilkan daftar order masuk
- Tiap order menampilkan:
  - Nama tempat / restoran
  - Rating
  - Total harga
  - Tombol **Accept**
- Ada indikator status:
  - Online

### ✅ Detail Order Kurir
- Informasi order:
  - Distance (contoh: 3.5 km)
  - Est. Time (contoh: 22 min)
- Route Details:
  - Pickup point
  - Customer location
- Order items (list makanan)
- Tombol **Accept Order**

### ✅ Profil Kurir
- Foto profil
- Nama kurir
- Tombol:
  - **Edit Profile**
  - **Go Offline**
  - **Log out**

### ✅ Pendapatan Kurir (Earnings)
- Ringkasan total pendapatan minggu ini
- Recent Activity / riwayat transaksi
- Menampilkan list order yang sudah selesai beserta nominal

---

## 🧭 Navigasi (Bottom Navigation)
Aplikasi menggunakan bottom navigation dengan beberapa tab seperti:
- Home
- Order/Cart
- Profile

*(ikon terlihat pada UI: home, cart/order, user/profile)*
