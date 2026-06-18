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
```
Run :
```bash
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