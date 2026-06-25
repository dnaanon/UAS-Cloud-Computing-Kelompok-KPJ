# Cloud Computing Project - Kelompok Kepanjen
---

```bash
Minggu 1 - Setup WordPress, MariaDB, Network Isolation
Services :
- WordPress
- MariaDB

Networks :
- frontend-net
- backend-net

Run :
docker compose up -d
```

```bash
Minggu 2 - Redis Container & MinIO Integration
Penambahan Services
- Redis (cache layer untuk WordPress)
- MinIO (object storage)

Fitur yang Ditambahkan
- Implementasi Redis Object Cache untuk meningkatkan performa WordPress  
- Integrasi Redis ke WordPress sebagai caching system  
- Setup MinIO container sebagai storage media  
- Pembuatan bucket MinIO: `wordpress-media`

Update Project
- Menambahkan service Redis pada docker-compose  
- Menambahkan service MinIO pada docker-compose  
- Konfigurasi WordPress agar terhubung dengan Redis  
- Membuat bucket `wordpress-media` di MinIO  
- Push perubahan ke GitHub
```

```bash
Minggu 3 - Security Hardening & Environment Configuration
Peningkatan Keamanan
- Implementasi file .env untuk menyimpan credential layanan
- Pemisahan informasi sensitif dari docker-compose.yml

Fitur yang Ditambahkan
- Penggunaan environment variables pada konfigurasi WordPress
- Penggunaan environment variables pada konfigurasi MariaDB
- Penggunaan environment variables pada konfigurasi MinIO

Update Project
- Membuat file .env untuk menyimpan credential database dan MinIO
- Memindahkan credential dari docker-compose.yml ke file .env
- Memperbarui konfigurasi docker-compose.yml agar menggunakan environment variables
- Melakukan pengujian ulang WordPress setelah perubahan konfigurasi
- Memastikan WordPress dapat berjalan normal setelah penerapan security hardening
- Push perubahan ke GitHub