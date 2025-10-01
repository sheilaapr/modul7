# 📱 Modul VII – Navigasi Antar Halaman Flutter (MaterialPageRoute & Named Route)

## 🎯 Tujuan Praktikum
1. Memahami konsep **navigasi antar halaman (routing)** pada Flutter.  
2. Mengimplementasikan navigasi menggunakan **Navigator.pushNamed()** dan **Navigator.pop()**.  
3. Mengimplementasikan navigasi menggunakan **Navigator.push(MaterialPageRoute())** dan **Navigator.pop()**.  
4. Mendemonstrasikan hasil navigasi antar halaman pada aplikasi Flutter sederhana.  

---

## 📖 Dasar Teori
- **Navigator** di Flutter berfungsi untuk mengelola perpindahan antar halaman (routes).  
- Mekanisme kerjanya mirip **stack (tumpukan)**: halaman baru akan ditaruh di atas halaman lama.  
- Fungsi utama:
  - `Navigator.push()` → membuka halaman baru.  
  - `Navigator.pop()` → menutup halaman saat ini dan kembali ke halaman sebelumnya.  
- Dua cara utama navigasi:
  1. **MaterialPageRoute** → langsung memanggil halaman tanpa mendaftarkan route.  
  2. **Named Route** → halaman didefinisikan di `MaterialApp.routes`, lalu dipanggil dengan nama route.  

---

## ⚙️ Alat & Bahan
- Komputer/laptop dengan **Flutter SDK** ter-install.  
- **VS Code** atau **Android Studio**.  
- Emulator Android/iOS atau smartphone untuk uji coba aplikasi.  

---
