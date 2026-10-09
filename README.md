# 📱 Quest Tugas Layout 2 - Jetpack Compose

Proyek aplikasi Android ini dibuat menggunakan **Jetpack Compose** untuk menampilkan daftar kartu informasi mahasiswa secara modular, responsif, dan *reusable*. Proyek ini dibangun dengan menerapkan praktik terbaik (*best practices*) pengembangan Android, seperti penggunaan *resources* terpisah (`strings.xml`, `colors.xml`) tanpa *hardcode* teks/warna pada UI.

---
## Identitas 
Nama : Zahwa Rezi Fadhilah Yasyfi'
Nim : 20240140237

## 🎨 Tampilan Aplikasi
<img width="418" height="807" alt="image" src="https://github.com/user-attachments/assets/ed3f2060-d35b-4636-a8e7-a7cd46eb94fe" />


---

## ✨ Fitur Utama

- **Reusability Component**: Komponen `DetailCard` dirancang dinamis untuk menampilkan data dengan berbagai penyesuaian (font, warna latar belakang, dan visibilitas nomor HP)[cite: 1, 2].
- **Clean Architecture & Code Separation**: Seluruh string teks dan warna disimpan di dalam XML resource terpisah.
- **Flexible Layouting**: Menggunakan perpaduan `Box`, `Column`, `Row`, `Card`, serta penataan posisi (*Alignment* & *Arrangement*) yang rapi[cite: 1, 2].
- **Edge-to-Edge Design**: Menggunakan `Scaffold` dan `enableEdgeToEdge()` agar antarmuka terlihat modern.

---

## 🛠️ Teknologi & Library

- **Language**: Kotlin 100%[cite: 1]
- **UI Framework**: Jetpack Compose
- **Design System**: Material 3[cite: 1]
- **Minimum SDK**: Android 7.0 (API Level 24) / disesuaikan

---

## 📁 Struktur Proyek

```text
app/src/main/
├── java/com/example/tugas3_composablelayout2/
│   ├── MainActivity.kt        # Entry point aplikasi[cite: 1]
│   └── ActivitasPertama.kt    # Layar utama & komponen DetailCard[cite: 1, 2]
└── res/
    ├── drawable/
    │   └── logoumy.png        # Asset logo[cite: 1, 2]
    └── values/
        ├── colors.xml         # Definisi warna aplikasi & kartu[cite: 1]
        └── strings.xml        # Definisi string teks[cite: 1]
