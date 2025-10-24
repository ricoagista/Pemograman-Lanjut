# 🧮 Kalkulator Sederhana (JavaFX)

Proyek ini adalah aplikasi **Kalkulator Sederhana** berbasis **JavaFX**, dibuat menggunakan **IntelliJ IDEA**.  
Aplikasi ini dapat melakukan operasi aritmatika dasar seperti **penjumlahan, pengurangan, perkalian, dan pembagian**.  
Didesain dengan tampilan sederhana menggunakan FXML dan kontrol antarmuka JavaFX.

---

## 📁 Struktur Proyek

```
Kalkulator/
├── src/
│   └── main/
│       ├── java/
│       │   └── com/
│       │       └── kalkulator/
│       │           ├── HelloApplication.java   # Kelas utama JavaFX
│       │           ├── HelloController.java    # Logika kalkulator
│       │           └── module-info.java        # Deklarasi modul
│       └── resources/
│           └── com/
│               └── kalkulator/
│                   └── hello-view.fxml         # Tampilan antarmuka (UI)
├── pom.xml                                    # Konfigurasi Maven
└── README.md
```

---

## 🚀 Cara Menjalankan

### 1️⃣ Prasyarat
Pastikan kamu sudah menginstal:
- **Java JDK 17+**
- **JavaFX SDK**
- **IntelliJ IDEA** (disarankan Community/Ultimate)
- **Maven** (sudah otomatis terpasang jika memakai IntelliJ)

### 2️⃣ Langkah Menjalankan
1. Buka proyek di **IntelliJ IDEA**.
2. Pastikan `JavaFX SDK` sudah diatur di:
   ```
   File → Project Structure → Libraries → Add → JavaFX SDK
   ```
3. Jalankan file `HelloApplication.java`:
   ```
   Klik kanan → Run 'HelloApplication'
   ```
4. Aplikasi kalkulator akan muncul dalam jendela GUI.

---

## 🧠 Fitur Aplikasi

| Fitur | Deskripsi |
|-------|------------|
| ➕ Tambah | Menambahkan dua atau lebih angka |
| ➖ Kurang | Mengurangkan dua atau lebih angka |
| ✖ Kali | Mengalikan dua atau lebih angka |
| ➗ Bagi | Membagi dua angka |
| 🧹 Clear (C) | Menghapus input dan mengatur ulang tampilan |
| 🟰 Equal (=) | Menampilkan hasil perhitungan |

---

## 🧩 Penjelasan File Utama

### `HelloApplication.java`
Berfungsi sebagai **entry point** aplikasi.  
Menginisialisasi FXML dan menampilkan tampilan utama.

### `HelloController.java`
Berisi **logika kalkulator** seperti:
- Event handler untuk tombol angka dan operasi.
- Fungsi evaluasi ekspresi matematika sederhana.
- Validasi dan penanganan error (contoh: pembagian dengan nol).

### `hello-view.fxml`
File antarmuka pengguna (GUI) menggunakan **FXML** dan **GridPane** untuk menata tombol serta label hasil.

---

## 🖼️ Tampilan Antarmuka

```
+---------------------+
|       123+45        | ← Label Display
+---------------------+
| 7 | 8 | 9 | / |
| 4 | 5 | 6 | * |
| 1 | 2 | 3 | - |
| 0 | C | = | + |
+---------------------+
```

---

## 🧾 Lisensi
Proyek ini dibuat untuk keperluan **pembelajaran dan praktikum pemrograman Java**.  
Bebas digunakan dan dimodifikasi untuk tujuan non-komersial.

---

## 👨‍💻 Pengembang
**Nama:** Rico Agista  
**Institusi:** Universitas Muhammadiyah Malang  
**Mata Kuliah:** Pemrograman Lanjut  
**Tahun:** 2025

---

### ⭐ Jika kamu menggunakan proyek ini untuk belajar, jangan lupa beri bintang di repo GitHub-mu 😄
