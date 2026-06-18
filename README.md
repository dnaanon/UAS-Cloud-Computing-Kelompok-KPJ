# Cloud Computing Project - Kelompok Kepanjen

## Minggu 1 - Setup WordPress, MariaDB, Network Isolation
Services :
- WordPress
- MariaDB

Networks :
- frontend-net
- backend-net

Run :
```bash
docker compose up -d


## Minggu 2 - Redis Container & MinIO Integration
Penambahan Services
- Redis (cache layer untuk WordPress)
- MinIO (object storage)

Storage / Feature
- Implementasi Redis Object Cache untuk optimasi performa WordPress
- Pembuatan bucket MinIO: wordpress-media untuk penyimpanan media

Update Project
- Integrasi Redis ke WordPress
- Setup MinIO container dan konfigurasi akses
- Push perubahan ke GitHub