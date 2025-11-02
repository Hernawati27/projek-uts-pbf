 📌 Projek UTS PBF (Pemrograman Berbasis Framework)

Dokumentasi ini dibuat untuk memenuhi tugas mata kuliah **Pemrograman Berbasis Framework (PBF)**.  
Project ini berisi aplikasi berbasis web dengan fitur CRUD dan beberapa fitur tambahan seperti export PDF/Excel.

---

👩‍💻 **Identitas Penyusun**
| Keterangan        | Isi                             |
|-------------------|----------------------------------|
| Nama              | Hernawati                       |
| NIM               | 202412031                       |
| Kelas             | Pagi                            |
| Mata Kuliah       | Pemrograman Berbasis Framework  |
| Dosen Pengampu    | FIKY ANGGARA, S.kom, M.Kom      |

---

📖 **Deskripsi Singkat Proyek**
Aplikasi ini dibuat menggunakan **PHP Laravel Framework** dan bertujuan untuk melakukan:
- Pengelolaan data (CRUD – Create, Read, Update, Delete).
- Export data ke **PDF** dan **Excel**.
- Tampilan UI responsif dan mudah digunakan.

---

⚙️ **Teknologi yang Digunakan**
- **Laravel** (PHP Framework)
- **MySQL / phpMyAdmin**
- **Bootstrap / Tailwind CSS**
- **XAMPP / Apache**
- **Git & GitHub (Version Control)**

---

 🚀 **Cara Menjalankan Proyek di Lokal (Localhost)**

```bash
# 1. Clone repository ini:
git clone https://github.com/Hernawati27/projek-uts-pbf.git

# 2. Masuk ke folder project:
cd projek-uts-pbf

# 3. Install dependency Laravel:
composer install

# 4. Copy file .env
cp .env.example .env

# 5. Atur koneksi database di file .env
DB_DATABASE=nama_database_kamu
DB_USERNAME=root
DB_PASSWORD=

# 6. Generate key Laravel:
php artisan key:generate

# 7. Migrasi database + seeder (jika ada)
php artisan migrate --seed

# 8. Jalankan server:
php artisan serve
```

---

## ✅ **Fitur-Fitur Aplikasi**
- ✅ Login (opsional jika ada)
- ✅ CRUD (Tambah, Edit, Hapus, Detail Data)
- ✅ Export **PDF**
- ✅ Export **Excel**
- ✅ Pencarian & Pagination Data
- ✅ Tampilan responsif (Bootstrap/Tailwind)

---
 🗂️ **Struktur Folder Utama Laravel**
```
projek-uts-pbf/
│
├── app/          # Controller, Model, dll.
├── resources/    # Views (Blade Template)
├── routes/       # web.php (Routing)
├── public/       # File frontend
└── database/     # Migrations dan Seeder
```


📷 **Screenshot Tampilan**

<img width="654" height="184" alt="image" src="https://github.com/user-attachments/assets/a6c7516e-72da-4197-9c6e-bdb07127a904" />
<img width="661" height="232" alt="image" src="https://github.com/user-attachments/assets/5059c723-1d16-4705-ac6a-7f33a00ad6fc" />
<img width="682" height="239" alt="image" src="https://github.com/user-attachments/assets/0cc1acb5-d700-4b8a-b03e-b0765da48706" />
<img width="524" height="110" alt="image" src="https://github.com/user-attachments/assets/26456d2b-61bc-46f3-85b6-3777be6c2cd0" />

<img width="1359" height="625" alt="image" src="https://github.com/user-attachments/assets/31425d22-5ee8-4de2-a6f7-d04621a5f89a" />
[mahasiswa.pdf](https://github.com/user-attachments/files/23293537/mahasiswa.pdf)
[mahasiswa.xlsx](https://github.com/user-attachments/files/23293540/mahasiswa.xlsx)
<img width="1352" height="668" alt="image" src="https://github.com/user-attachments/assets/cc53b9cf-d2e5-4dcd-884b-e5838cb78e01" />
<img width="1346" height="649" alt="image" src="https://github.com/user-attachments/assets/e170434e-1179-4107-a1d0-b4805beb17bf" />



---

💬 Kontak

📧 Email: hernaeren27@gmail.com

💻 GitHub: https://github.com/Hernawati27

---

