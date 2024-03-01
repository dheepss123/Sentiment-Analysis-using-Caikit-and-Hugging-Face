# -Voice-Assistant-with-OpenAI-s-GPT-3-and-IBM-Watson

## Nama Pengumpul: Dheo Putranta Pandia
## Nama Tugas: Create a Voice Assistant with OpenAI's GPT-3 and IBM Watson
## Learning Path: Advance AI (Infinite Learning)

### Langkah 1: Persiapan Proyek
1. Buat struktur direktori untuk proyek Anda.
2. Instal Docker jika belum terpasang di sistem Anda.

### Langkah 2: Pengaturan Environment
1. Dapatkan API key untuk layanan OpenAI's GPT-3.
2. Dapatkan kredensial untuk layanan IBM Watson Speech-to-Text dan Text-to-Speech.

### Langkah 3: Menyiapkan Kode
- Buat file Dockerfile untuk mengonfigurasi kontainer Docker.
- Buat file server.py untuk menangani permintaan HTTP dan mengintegrasikan layanan OpenAI dan IBM Watson.
- Buat file worker.py untuk mengelola logika pemrosesan teks dan suara menggunakan layanan OpenAI dan IBM Watson.
- Buat file index.html, style.css, dan script.js untuk front-end responsif.

### Langkah 4: Membangun dan Menjalankan Kontainer Docker
```bash
docker build . -t voice-chatapp-powered-by-openai
docker run -p 8000:8000 voice-chatapp-powered-by-openai
