# TugasFlutter_MakeNewsPortal_2208107010060
# 📰 MakeNewsPortal

Aplikasi ini merupakan contoh sederhana dari aplikasi berbasis **Flutter** yang menampilkan **berita teknologi**, **kategori interaktif**, dan **halaman profil pengguna** dengan fitur login/logout menggunakan **SharedPreferences**. Proyek ini dibuat mengikuti modul untuk memenuhi tugas mata kuliah Pemrograman Berbasis Mobile

---

## 📱 Fitur Utama

### 1. **Home Page (Portal Berita)**

* Menampilkan daftar berita dari API [NewsAPI](https://newsapi.org/)
* Menyediakan informasi seperti **judul**, **tanggal terbit**, **gambar**, dan **deskripsi berita**
* Klik berita akan membuka halaman detail

### 2. **Kategori Page**

* Menampilkan berbagai kategori ikon seperti **General**, **Entertainment**, dan **Transportasi**
* Menekan ikon akan menampilkan toast yang menunjukkan kategori yang dipilih

### 3. **Profil Page**

* Menampilkan status login pengguna
* Jika belum login, pengguna diarahkan ke halaman login atau registrasi
* Jika sudah login, ditampilkan username dan tombol logout
* Menggunakan `SharedPreferences` untuk menyimpan sesi login secara lokal

---

## 🛠️ Teknologi yang Digunakan

* [Flutter](https://flutter.dev/)
* [Dart](https://dart.dev/)
* [NewsAPI](https://newsapi.org/) untuk data berita
* `shared_preferences` untuk manajemen sesi login
* `fluttertoast` untuk notifikasi toast

---

## 🔧 Instalasi dan Menjalankan Proyek

1. **Clone repo ini:**

```bash
git clone https://github.com/alhusnaahanifah/TugasFlutter_MakeNewsPortal_2208107010060.git
cd TugasFlutter_MakeNewsPortal_2208107010060
```

2. **Install dependencies:**

```bash
flutter pub get
```

3. **Jalankan aplikasi:**

```bash
flutter run
```

---

## 📝 Catatan

* Untuk menggunakan berita dari **NewsAPI**, Anda perlu mendaftar dan mengganti `apiKey` di `linkAPI` pada file `homepage.dart`.
* Aplikasi ini masih dalam tahap pengembangan dan dapat dikembangkan lebih lanjut, seperti:

  * Menambahkan autentikasi backend
  * Menyimpan data berita favorit
  * Menambahkan tema gelap/terang

---

## 📷 Preview

![image](https://github.com/user-attachments/assets/d268ba0b-6f4c-4abc-9fe5-95ab8eb81d43)
![image](https://github.com/user-attachments/assets/1b191b4e-a1a0-4a5a-bf6d-7c8a47baa997)
![image](https://github.com/user-attachments/assets/66e99ee6-eca2-45e9-afdb-3ce4a0625f51)




---
