[github_readme.md](https://github.com/user-attachments/files/33504910/github_readme.md)
# Sistem Karyawan - Pemrograman Berorientasi Objek (PBO)

Aplikasi konsol berbasis C# ini dikembangkan untuk memenuhi tugas mata kuliah Pemrograman Berorientasi Objek (PBO) Kelas C. Proyek ini mendemonstrasikan penerapan konsep utama PBO seperti **Inheritance (Pewarisan)**, **Method Overriding**, dan **Polymorphism**.

## 🏗️ Struktur Kelas (Class Diagram)

Sistem ini dirancang menggunakan hierarki kelas berikut:
- **`Karyawan`** (Base Class: properti `Nama`, `Gaji`; method `Kerja()`, `InfoKaryawan()`)
  - **`Tetap`** (properti `Tunjangan`, method `HitungGajiTotal()`)
    - **`Manager`** (method `Memimpin()`)
    - **`Staff`** (method `KerjakanTugas()`)
  - **`Kontrak`** (properti `Durasi`, method `CekKontrak()`)
    - **`Magang`** (method `Belajar()`)
    - **`Freelancer`** (method `AmbilProyek()`)
- **`Perusahaan`** (Koleksi `List<Karyawan>`, method `TambahKaryawan()`, `DaftarKaryawan()`)

---

## 🛠️ Fitur Utama
1. **Pewarisan (Inheritance):** Penurunan properti dan method dari kelas induk (`Karyawan`) ke berbagai sub-kelas turunan.
2. **Polymorphism & Overriding:** Implementasi method `Kerja()` yang berbeda di setiap subclass serta demonstrasi dynamic polymorphism melalui array `Karyawan`.
3. **Manajemen Perusahaan:** Menambah dan menampilkan seluruh informasi data karyawan secara dinamis.

---

## 💻 Cara Menjalankan Program

1. Pastikan Anda telah menginstal **Visual Studio** atau **.NET SDK** di komputer Anda.
2. Clone repository ini ke perangkat Anda:
   ```bash
   git clone https://github.com/username/KELAS_NIM_TASKPBO.git
   ```
3. Buka file solution (`.sln`) atau proyek menggunakan Visual Studio.
4. Jalankan program dengan menekan tombol **Start** (F5) pada Visual Studio atau melalui terminal:
   ```bash
   dotnet run
   ```

---

## 👤 Identitas Pengguna
- **Nama:** [Nama Anda]
- **NIM:** [NIM Anda]
- **Kelas:** C
