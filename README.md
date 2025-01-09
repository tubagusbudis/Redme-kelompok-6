# Final Proyek Pemrograman Berorientasi Obyek 1
<ul>
  <li>Mata Kuliah: Pemrograman Berorientasi Obyek 1</li>
  <li>Dosen Pengampu: <a href="https://github.com/Muhammad-Ikhwan-Fathulloh">Muhammad Ikhwan Fathulloh</a></li>
</ul>

## Kelompok
<ul>
  <li>Kelompok: kelompok 6</li>
  <li>Proyek: Aplikasi GoResto</li>
  <li>Anggota:</li>
  <ul>
    <li>Ketua: <a href="">Tubagus Budi Sampurno</a></li>
    <li>Anggota 1: <a href="">Ra’jza Muhammad Yasyfa Fajri Sidiq</a></li>
    <li>Anggota 2: <a href="">Liesna Nur’aeni Apriliani</a></li>
  </ul>
</ul>

## Judul Studi Kasus
<p>Aplikasi GoResto Pemesanan Makanan Restoran.</p>

## Penjelasan Studi Kasus
<p>GoResto adalah aplikasi pemesanan makanan yang dirancang untuk mempermudah pelanggan memesan makanan dari restoran secara online. Aplikasi ini juga menyediakan sistem pengelolaan menu, pesanan, dan pembayaran yang efisien untuk admin restoran.</p>

## Penjelasan 4 Pilar OOP dalam Studi Kasus

### 1. Inheritance
<p>Kelas User kelas induk dari semua pengguna, <br>
Kelas Costumer dan Admin turunan dari kelas User.</p>

### 2. Encapsulation
<p>Data seperti password hanya dapat diakses melalui metode getPassword atau setPassword.</p>

### 3. Polymorphism
<p>Metode viewMenu() bisa memberikan daftar menu yang berbeda untuk pelanggan dan admin.</p>

### 4. Abstract
<p>Metode processPayment() yang diimplementasikan oleh kelas turunan seperti CreditCardPayment dan EWalletPayment.</p>

## Struktur Tabel Aplikasi
<p>1. Tabel Users
<br>
role, name, password.
<br>
<br>
2. Tabel menu_items
<br>
item_id, name, description, price, category.
<br>
<br>
3. Tabel orders
<br>
order_id, user_id, total_price.
<br>
<br>
4. Tabel order_items
<br>
order_item_id, order_id, quantity, sub_total.
<br>
<br>
5. Tabel payments
<br>
payment_id, order_id, amount, payment_status, payment_date.
<br>
<br>
6. Tabel categories
<br>
category_id, name, description, created_at.</p>

## Tampilan Aplikasi
<p>Halaman Utama (Home)
Komponen:
  
Logo aplikasi
Menu navigasi: "Home", "Menu", "My Orders", "Profile", dan "Logout"</p>
<br>

Halaman Menu
Komponen:

Daftar Kategori (seperti tab di bagian atas).
Card Menu:
Gambar, nama, harga, deskripsi singkat.
Tombol "Add to Cart".
Cart Summary (floating button atau sidebar):
Total item di keranjang.
Tombol "View Cart".
<br>
<br>

Halaman Checkout
Komponen:

Informasi Pengiriman:
Nama, alamat, nomor telepon.
Metode Pembayaran:
Opsi: "Credit Card", "E-Wallet", "COD".
Rincian Pesanan:
Total harga dan total pembayaran.
Tombol Konfirmasi: "Place Order".
<br>
<br>

Halaman My Orders
Komponen:

Daftar Pesanan:
Nomor pesanan, status, tanggal, total harga.
Tombol "View Details" untuk melihat detail pesanan.
<br>
<br>

Halaman Profil
Komponen:

Informasi pengguna: Nama, email, alamat, nomor telepon.
Tombol "Edit Profile" dan "Change Password".
## Demo Proyek
<ul>
  <li>Github: <a href="">Github</a></li>
  <li>Youtube: <a href="">Youtube</a></li>
</ul>
