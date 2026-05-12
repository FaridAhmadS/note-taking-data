
````markdown
# 📝 Aplikasi Catatan Pribadi

Aplikasi desktop sederhana berbasis Python menggunakan Tkinter untuk membuat, mengelola, dan menghapus catatan pribadi dengan fitur kategori dan riwayat perubahan.

---

## 📌 Fitur Utama

- ➕ Menambahkan catatan baru
- 🗂️ Menambahkan kategori pada catatan
- 📅 Menampilkan catatan berdasarkan urutan waktu
- 🔤 Menampilkan catatan berdasarkan urutan abjad
- 🗑️ Menghapus catatan
- 🔄 Menyimpan riwayat perubahan menggunakan Ring Buffer
- 🎨 Tampilan GUI sederhana dan user-friendly

---

## 🛠️ Teknologi yang Digunakan

- Python 3
- Tkinter (GUI)
- Collections `deque`
- Datetime

---

## 📂 Struktur Program

### 1. Class `Memo`
Digunakan untuk menyimpan data catatan:
- ID memo
- Judul
- Isi
- Kategori
- Tanggal dibuat

### 2. Class `Kategori`
Digunakan untuk mengelompokkan memo berdasarkan kategori tertentu.

### 3. Class `RingBuffer`
Menggunakan `deque` untuk menyimpan riwayat perubahan terbaru.

### 4. Class `AplikasiCatatan`
Class utama yang mengatur:
- Tampilan GUI
- Penambahan catatan
- Penghapusan catatan
- Sorting catatan
- Riwayat perubahan

---

## ▶️ Cara Menjalankan Program

### 1. Clone Repository
```bash
git clone (https://github.com/FaridAhmadS/note-taking-data)
````

### 2. Masuk ke Folder Project

```bash
cd note-taking-data
```

### 3. Jalankan Program

```bash
python note taking data struktur system.py
```

---

## 📸 Tampilan Aplikasi

Fitur utama aplikasi:

* Form input catatan
* Daftar catatan
* Tombol sorting
* Riwayat perubahan
* Hapus catatan


---

## 📖 Konsep yang Digunakan

Project ini menerapkan beberapa konsep pemrograman dan struktur data:

* Object Oriented Programming (OOP)
* List
* Dictionary
* Queue / Ring Buffer
* GUI Programming
* Sorting

---

## 🎯 Tujuan Project

Project ini dibuat untuk:

* Belajar Python GUI menggunakan Tkinter
* Memahami konsep OOP
* Mengimplementasikan struktur data sederhana
* Membuat aplikasi desktop sederhana

---

## 👨‍💻 Author

Dibuat oleh: Farid Ahmad Santoso
NIM : 25091397050
Kelas : 2025B

Mahasiswa D4 Manajemen Informatika

## 📄 License

Project ini bebas digunakan untuk pembelajaran.

```
```
