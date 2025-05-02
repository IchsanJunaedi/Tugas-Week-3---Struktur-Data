# TUGAS WEEK 3 - STRUKTUR DATA
## Langkah-langkah Menggunakan GitBash ke GitHub

1. **Buka GitBash**  
    Jalankan aplikasi GitBash di komputer Anda.

2. **Navigasi ke Direktori Proyek**  
    Gunakan perintah `cd` untuk berpindah ke direktori proyek Anda:
    ```bash
    cd /path/to/your/project
    ```

3. **Inisialisasi Git**  
    Jika belum diinisialisasi, jalankan perintah berikut:
    ```bash
    git init
    ```

4. **Tambahkan File ke Staging Area**  
    Tambahkan file yang ingin diunggah ke GitHub:
    ```bash
    git add .
    ```

5. **Commit Perubahan**  
    Buat commit dengan pesan deskriptif:
    ```bash
    git commit -m "Pesan commit Anda"
    ```

6. **Hubungkan ke Repository GitHub**  
    Tambahkan URL repository GitHub Anda:
    ```bash
    git remote add origin https://github.com/username/repository.git
    ```

7. **Push ke GitHub**  
    Kirim perubahan ke repository GitHub:
    ```bash
    git push -u origin main
    ```

8. **Verifikasi di GitHub**  
    Buka repository Anda di GitHub untuk memastikan file telah berhasil diunggah.
