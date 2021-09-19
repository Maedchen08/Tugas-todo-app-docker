# Todo Apps : Ini adalah homework docker containerizing todo apps

Dicontainerize oleh Eka Nur.

Docker Image : docker pull 3k4nurr/todoapp:1

Link Docker Hub : <https://hub.docker.com/repository/docker/3k4nurr/todoapp>

Image ini tak akan berjalan tanpa environment yang sudah ditentukan buka file .env untuk mengaturnya yang terpenting adalah pada docker compose. dan bawah ini adalah envorenment yang dibutuhkan untuk menjalankan aplikasinya.

```yaml
- DB_URI=URI_MONGO_DB 
- DB_NAME=NAMA_DATABASE_MONGO 
- DB_COLLECTION_NAME=NAMA_COLLECTION_DATABASE 
```

namun jika belum ada punya database, kalian bisa pakai docker-compose.yaml yang ada. dan jangan lupa untuk menyesuaikan file .env yang ada, sesuaikan dengan preferensi kalian masing masing atau jangan ubah apapun. lalu jalankan dengan periintah ```docker-compose up``` nb: aplikasi ini hanya bisa dijalankan menggunakan docker-compose.yaml  

## License MIT License Copyright (c)

2019 Shubham Chadokar Copyright  
(c) 2021 Eka N  
