# open-webui-ollama

Home Project: [https://openwebui.com/](https://openwebui.com/)
Github: [https://github.com/open-webui/open-webui](https://github.com/open-webui/open-webui)

Open-WebUI adalah proyek UI yang memudahkan pengguna untuk menerapkan 
LLM berbasis lokal. Tampilan yang mirip dengan openAI dan penyedia LLM
sejenis menjadikannya sangat familiar untuk pengguna yang sudah terbiasa.

## Instalasi

**Pastikan Anda sudah memasang _docker_ dengan fitur _docker compose_.**

Bila Anda belum mengunduh proyek ini silakan jalankan:

```{sh}
git clone https://github.com/yht/ai-on-docker.git
cd ai-on-docker
```

Bila sebelumnya sudah, silakan masuk ke folder proyek dan jalankan:

```{sh}
cd open-webui-ollama
docker compose pull
```

Tunggu sampai semua _docker image_ yang dibutuhkan terunduh dan jalankan:

```{sh}
docker compose build
docker compose up 
```

### Laman Open-WebUI

Laman _open-webui_ yang sudah terpasang dapat diakses melalui [http://localhost:10080](http://localhost:10080)

## Referensi

* [docker-compose.yml](https://github.com/open-webui/open-webui/blob/main/docker-compose.yaml)
