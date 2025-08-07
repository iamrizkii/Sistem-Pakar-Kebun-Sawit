
# 🌴 Sistem Pakar Kebun Sawit

Aplikasi Android untuk membantu petani mendiagnosis penyakit pada tanaman kelapa sawit berdasarkan gejala yang terlihat, menggunakan pendekatan sistem pakar dengan metode Certainty Factor.

---

## 📲 Panduan Instalasi (Developer)

### 1. Clone Repository
Pastikan kamu sudah install Git dan Android Studio.

```bash
git clone https://github.com/iamrizkii/Sistem-Pakar-Kebun-Sawit.git
````

### 2. Buka di Android Studio

* Buka Android Studio
* Klik **File → Open** dan pilih folder hasil clone
* Tunggu sampai **Gradle build** selesai

### 3. Jalankan Aplikasi

* Hubungkan perangkat Android atau jalankan emulator
* Klik tombol ▶️ (Run)
* Aplikasi akan berjalan di perangkat/emulator

---

## 🛠️ Teknologi yang Digunakan

| Komponen | Deskripsi                                     |
| -------- | --------------------------------------------- |
| Bahasa   | Kotlin                                        |
| SDK      | minSdk 21, compileSdk 34                      |
| DB       | SQLite (lokal)                                |
| UI       | Material Design + XML layout                  |
| Logika   | Sistem Pakar berbasis Rule + Certainty Factor |

---

## 📁 Struktur File Penting

* `MainActivity.kt` → Tampilan menu utama
* `KonsultasiActivity.kt` → Memilih gejala
* `HasilDiagnosaActivity.kt` → Menampilkan hasil diagnosa
* `assets/db_sp_sawit.db` → Database penyakit dan gejala
* `AndroidManifest.xml` → Daftar activity
* `layout/*.xml` → Desain antarmuka aplikasi

---

## 👥 Kontributor

* [@iamrizkii](https://github.com/iamrizkii)
* Kelompok Sistem Pakar Diagnosa Penyakit Kebun Sawit
* Anggota : Saeful Rizky - 221001011
*           Tia Jannatul Marwanda - 221001024
*           Asmawati - 221001022

---

## 📌 Catatan

* Aplikasi ini **bekerja secara offline**.
* Data penyakit dan aturan pakar tersimpan langsung di database lokal (`SQLite`).

```

---

