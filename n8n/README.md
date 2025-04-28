# n8n

* Home Project: [https://n8n.io/](https://n8n.io/)
* Github: [https://github.com/n8n-io/n8n](https://github.com/n8n-io/n8n)

n8n adalah proyek pengembangan otomasi alur kerja berbasis AI yang
mendukung fleksibilitas. Dibangun untuk pengembang yang hanya butuh
drag-n-drop, namun butuh menguasai penuh teknologi dan kemerdekaan
dalam menerapkan berbagai agen AI serta integrasi dengan berbagai
aplikasi.

## Instalasi

**Pastikan Anda sudah memasang _docker_ dengan fitur _docker compose_.**

Bila Anda belum mengunduh proyek ini silakan jalankan:

```{sh}
git clone https://github.com/yht/ai-on-docker.git
cd n8n
```

Bila sebelumnya sudah, silakan masuk ke folder proyek dan jalankan:

```{sh}
cd n8n
docker compose --profile cpu pull
```

Tunggu sampai semua _docker image_ yang dibutuhkan terunduh dan jalankan:

```{sh}
docker compose create
docker compose --profile cpu up
```

### Laman n8n

Laman _n8n_ yang sudah terpasang dapat diakses melalui [http://localhost:5678/](http://localhost:5678/)

## Referensi

* [n8n-io/self-hosted-ai-starter-kit](https://github.com/n8n-io/self-hosted-ai-starter-kit)
