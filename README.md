[README (1).md](https://github.com/user-attachments/files/27009644/README.1.md)
# 🥩 Triple-F Store — Premium Meat E-Commerce

![PLATFORM](https://img.shields.io/badge/PLATFORM-WEB-2563eb?style=for-the-badge)
![TAILWIND](https://img.shields.io/badge/🌊_TAILWIND-CSS-06b6d4?style=for-the-badge)
![JAVASCRIPT](https://img.shields.io/badge/JS-JAVASCRIPT_ES6+-f7df1e?style=for-the-badge&logo=javascript&logoColor=black)
![STORAGE](https://img.shields.io/badge/STORAGE-LOCALSTORAGE-f97316?style=for-the-badge)

---

## 📝 Deskripsi Project

**Triple-F Store** adalah platform *e-commerce* premium yang berfokus pada penjualan **daging segar berkualitas tinggi** (Sapi, Kambing, Ayam, dan Produk Olahan). Proyek ini dirancang untuk mempermudah pelanggan dalam memilih dan membeli produk daging pilihan secara online dengan mudah, cepat, dan aman.

Sistem ini dibangun sebagai proyek **Full Client-Side** menggunakan arsitektur ringan namun bertenaga. Seluruh pengelolaan data (User, Produk, Keranjang, dan Transaksi) dilakukan menggunakan **Vanilla JavaScript** dengan pemanfaatan **LocalStorage** sebagai media penyimpanan database lokal yang persisten.

---

## ✨ Fitur Unggulan

### 🛒 Pengalaman Belanja Modern
- **Product Catalog:** Tampilan 12 produk daging lengkap dengan gambar, harga, rating, dan deskripsi dari data JSON dummy.
- **Smart Cart:** Manajemen keranjang belanja dinamis dengan fitur tambah/kurang/hapus item dan kalkulasi total harga otomatis.
- **Advanced Search & Filter:** Pencarian produk berdasarkan nama, filter berdasarkan kategori (Sapi, Kambing, Ayam, Olahan) dan range harga, serta pengurutan.
- **Wishlist:** Simpan produk daging favorit untuk dikunjungi kembali di sesi berikutnya.

### 🎨 Desain & Interaktivitas
- **Responsive Layout:** Antarmuka elegan yang sepenuhnya adaptif (Mobile, Tablet, Desktop) menggunakan Tailwind CSS.
- **Dark & Light Mode:** Dukungan tema visual yang dapat disesuaikan dengan preferensi kenyamanan mata pengguna.
- **Dynamic Rating:** Sistem penilaian bintang produk yang tampil secara dinamis.
- **Toast Notification:** Notifikasi pop-up yang informatif untuk setiap aksi pengguna.

### 🔐 Keamanan & Autentikasi
- **Auth System:** Simulasi fitur Login, Register, dan Logout dengan validasi lengkap (email unik, password minimal 6 karakter).
- **Checkout & Order:** Form checkout dengan validasi nama, alamat, dan nomor HP, serta generate ID transaksi unik otomatis.
- **Order History:** Riwayat pembelian lengkap per pengguna dengan detail transaksi.
- **Persistence Data:** Data tetap tersimpan aman di browser meskipun halaman dimuat ulang.

---

## 🚀 Teknologi yang Digunakan

| Layer | Teknologi |
|---|---|
| **Frontend UI** | [Tailwind CSS](https://tailwindcss.com) |
| **Programming Language** | JavaScript (ES6+) |
| **Database / Storage** | Web Storage API (LocalStorage) |
| **Deployment** | GitHub Pages |
| **Data Format** | JSON (JavaScript Object Notation) |

---

## 🌐 Demo Aplikasi

Aplikasi telah berhasil dideploy dan dapat diakses secara publik melalui tautan berikut:

👉 **[Live Demo Triple-F Store di GitHub Pages](#)*https://fakhrivsc.github.io/Fakhri_miftahul_khairi_UTS_Web2/* ← *(ganti dengan link GitHub Pages kamu)*

---

## 💻 Cara Menjalankan Lokal

### 1. Clone Repository
```bash
git clone https://github.com/username/NamaDepan_NamaBelakang_UTS_Web2.git
```

### 2. Masuk ke Direktori
```bash
cd NamaDepan_NamaBelakang_UTS_Web2
```

### 3. Buka di Browser
Cukup buka file `index.html` langsung di browser:
```
Klik dua kali file index.html
```
> Tidak memerlukan server atau instalasi tambahan apapun. Langsung jalan! ✅

---

## 📁 Struktur Project

```
NamaDepan_NamaBelakang_UTS_Web2/
│
├── index.html        # File utama (seluruh aplikasi dalam 1 file)
└── README.md         # Dokumentasi project
```

---

## 🗂️ Fitur Lengkap (Checklist UTS)

### Fitur Wajib
- [x] **Authentication** — Register & Login dengan validasi email unik dan password min. 6 karakter
- [x] **Data disimpan di LocalStorage** — User, Cart, Orders, Wishlist, Session
- [x] **Product Management** — Menampilkan list produk dari JSON dummy data
- [x] **Detail Produk** — Halaman detail dengan deskripsi lengkap
- [x] **Search & Filter** — Cari produk by nama, filter by kategori & harga
- [x] **Cart (Keranjang)** — Tambah, hapus, update qty, total otomatis
- [x] **Checkout** — Form nama, alamat, no HP + generate ID transaksi
- [x] **Order History** — Riwayat pembelian per user
- [x] **Responsive UI** — Mobile & Desktop dengan Tailwind CSS
- [x] **State Management** — LocalStorage untuk session, cart, order

### Fitur Bonus
- [x] **Dark Mode** — Toggle tema gelap/terang
- [x] **Wishlist** — Simpan produk favorit
- [x] **Rating Produk** — Tampilan bintang dinamis
- [x] **Toast Notification** — Notifikasi custom untuk setiap aksi

---

## 👨‍💻 Developer

| Info | Detail |
|---|---|
| **Nama** | Fakhri miftahul khairi |
| **NIM** | 2411070089 |
| **Kelas** | kelas malam |
| **Mata Kuliah** | Pemrograman Web 2 |
| **Semester** | 4 |

---

*© 2026 Triple-F Store — UTS Pemrograman Web 2*
