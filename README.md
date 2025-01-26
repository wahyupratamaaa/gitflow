# 📚 Tutorial Singkat Git

## 🚀 Pengantar

Git adalah sistem kontrol versi yang digunakan untuk melacak perubahan dalam file dan folder. Dalam tutorial ini, kita akan membahas tentang tiga branch utama yaitu `main`, `wahyupratama`, dan `feature/new-login`, serta cara menggunakan perintah dasar Git.

## 🌳 Branch

- **Branch `main`**: Branch utama yang berisi kode stabil.
- **Branch `wahyupratama`**: Branch untuk pengembangan fitur atau perubahan.
- **Branch `feature/new-login`**: Contoh branch untuk fitur baru.

## 🛠️ Perintah Dasar Git

### 1. **Git Clone**

Membuat salinan lokal dari repositori remote.

bash
git clone

### 2. **Git Status**

Menampilkan status repositori lokal.

bash
git status

### 3. **Git Add**

Menambahkan perubahan ke staging area.

bash
git add

atau untuk menambahkan semua file
git add .

### 4. **Git Commit**

Menyimpan perubahan yang telah ditambahkan ke staging area.

bash
git commit -m "Pesan commit yang menjelaskan perubahan"

### 5. **Git Push**

Mengirimkan perubahan dari lokal ke remote.

bash
git push origin

### 6. **Git Pull**

Mengambil dan menggabungkan perubahan dari remote ke lokal.

bash
git pull origin

### 7. **Git Merge**

Menggabungkan perubahan dari satu branch ke branch lainnya.

bash
git checkout main
git merge wahyupratama

### 8. **Git Branch**

Menampilkan daftar branch dan membuat branch baru.

bash
git branch
git branch

### 9. **Git Checkout**

Berpindah antara branch.

bash
git checkout

### 10. **Git Log**

Menampilkan riwayat commit.

bash
git log

### 11. **Git Remote**

Mengelola remote repository.

bash
git remote -v
git remote add

### 12. **Git Fetch**

Mengambil perubahan dari remote tanpa menggabungkannya.

bash
git fetch origin

## 📌 Contoh Penggunaan dalam Tiga Branch

### 1. **Membuat Branch Baru**

Misalkan kita ingin membuat branch baru bernama `feature/new-login`.

bash
git branch feature/new-login

### 2. **Beralih ke Branch Baru**

bash
git checkout feature/new-login

### 3. **Melakukan Perubahan dan Commit**

Misalkan kita membuat perubahan pada file `login.js`.

bash
git add login.js
git commit -m "Menambahkan fitur login baru"

### 4. **Push Perubahan ke Remote**

bash
git push origin feature/new-login

### 5. **Beralih ke Branch `main`**

bash
git checkout main

### 6. **Pull Perubahan Terbaru dari Remote**

bash
git pull origin main

### 7. **Merge Branch `feature/new-login` ke `main`**

bash
git merge feature/new-login

### 8. **Push Perubahan ke Remote**

bash
git push origin main

### 9. **Beralih ke Branch `wahyupratama`**

bash
git checkout wahyupratama

### 10. **Pull Perubahan Terbaru dari Remote**

bash
git pull origin wahyupratama

### 11. **Merge Branch `main` ke `wahyupratama`**

bash
git merge main

### 12. **Push Perubahan ke Remote**

bash
git push origin wahyupratama

## 🎉 Penutup

Dengan memahami dan menggunakan perintah-perintah ini, Anda dapat lebih efektif dalam mengelola proyek Git Anda. Jika ada pertanyaan lebih lanjut atau butuh penjelasan lebih detail, silakan beri tahu!  

