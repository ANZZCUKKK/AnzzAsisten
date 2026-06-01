# Panduan Installasi AnzzAsisten

## Langkah Cepat (5 Menit)

### 1. Install Aplikasi
- [Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm)
- [AutoTools](https://play.google.com/store/apps/details?id=com.joaomgcd.autotools)

### 2. Dapatkan API Key Gratis (Gemini)
- Buka https://aistudio.google.com/apikey
- Login dengan Google Account
- Klik "Create API Key"
- Copy key yang muncul (contoh: `AIzaSyDxxxxx`)

### 3. Import ke Tasker
- Buka Tasker
- Long tap tab "Profiles"
- Pilih "Import"
- Pilih file `AnzzAsisten.prf.xml`

### 4. Masukkan API Key
- Buka tab "Tasks"
- Tap task "AnzzAsisten_Processor"
- Cari aksi "HTTP Request"
- Ganti `YOUR_API_KEY_HERE` dengan API key asli

### 5. Test
- Copy teks "Apa itu AI?"
- Tunggu 3-5 detik
- Notifikasi muncul dengan jawaban

## Troubleshooting

| Masalah | Solusi |
|---------|--------|
| API Error 401 | Cek API key benar/tidak expired |
| Tidak ada notifikasi | Cek izin Tasker: Settings → Apps → Tasker → Izin |
