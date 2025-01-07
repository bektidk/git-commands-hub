# Pusat Perintah Git

[![Bahasa Indonesia](https://img.shields.io/badge/lang-Indonesia-red)](README.id.md)  
[![English](https://img.shields.io/badge/lang-English-blue)](README.md)

Repository ini berfungsi sebagai sumber referensi perintah-perintah Git penting untuk digunakan secara cepat.

## Memulai

Sebelum menggunakan perintah Git, pastikan Anda sudah menginstal Git di sistem Anda. Anda dapat mengunduhnya dari [situs resmi Git](https://git-scm.com/).

### 1. Mengonfigurasi Git

Atur nama pengguna dan alamat email Anda untuk commit Git:

```bash
git config --global user.name "Nama Anda"
git config --global user.email "email.anda@contoh.com"
```

Lihat konfigurasi saat ini:

```bash
git config --list
```

### 2. Menginisialisasi Repository

Untuk membuat repository Git baru, pindah ke direktori proyek Anda dan jalankan:

```bash
git init
```

### 3. Mengkloning Repository

Klon repository yang sudah ada dari server remote (contoh: GitHub):

```bash
git clone <repository-url>
```

### 4. Memeriksa Status Repository
Lihat status file dalam repository Anda (dimodifikasi, di-stage, tidak dilacak):

```bash
git status
```

### 5. Menambahkan Perubahan

Stage perubahan untuk commit berikutnya:

```bash
git add <file-name>
```

Untuk menambahkan semua perubahan, gunakan:

```bash
git add .
```

### 6. Melakukan Commit Perubahan

Commit perubahan yang sudah di-stage dengan pesan:

```bash
git commit -m "Your commit message"
```

### 7. Melihat Riwayat Commit

Untuk melihat riwayat commit:

```bash
git log
```

### 8. Mendorong Perubahan

Kirim perubahan yang sudah di-commit ke repository remote (contoh: GitHub):

```bash
git push origin main
```

Ganti main dengan nama branch Anda jika berbeda.

### 9. Menarik Perubahan

Ambil dan gabungkan perubahan dari repository remote:

```bash
git pull origin main
```

### 10. Membuat Cabang (Branch)

Buat branch baru:

```bash
git branch <branch-name>
```

Pindah ke branch yang berbeda:

```bash
git checkout <branch-name>
```

Buat dan pindah ke branch baru secara bersamaan:

```bash
git checkout -b <branch-name>
```

### 11. Menggabungkan Cabang (Branch)

Gabungkan branch ke branch yang sedang aktif:

```bash
git merge <branch-name>
```

### 12. Menyimpan Perubahan Sementara

Simpan sementara perubahan yang belum siap di-commit:

```bash
git stash
```

Untuk menerapkan perubahan yang disimpan:

```bash
git stash apply
```

### 13. Melihat Repository Remote

Daftar repository remote yang terkonfigurasi untuk repository lokal Anda:

```bash
git remote -v
```

### 14. Hapus file dari repository Anda dan stage penghapusan:

Hapus file dari repository Anda dan stage penghapusan:

```bash
git rm <file-name>
```

### 15. Mereset Perubahan

Batalkan stage perubahan (memindahkan dari staged ke unstaged):

```bash
git reset <file-name>
```

Untuk mereset seluruh direktori kerja Anda:

```bash
git reset --hard
```

### Kesimpulan

Ini adalah beberapa perintah Git penting yang sering Anda gunakan. Memahami dan menguasai perintah-perintah ini akan membantu Anda mengelola basis kode dengan lebih efisien.
