JEJAK ASN – Workflow n8n untuk Penginputan Aktivitas Kinerja ASN

Deskripsi Singkat:
JEJAK ASN (Jejaring Elektronik Jurnal Aktivitas Kinerja Aparatur Sipil Negara) adalah sistem pencatatan kinerja harian yang mengintegrasikan 4 platform utama dalam satu alur kerja otomatis, yaitu Telegram sebagai antarmuka pengguna untuk melakukan input aktivitas pegawai melalui chat, n8n sebagai workflow automation engine yang mengatur alur pemrosesan data, AI Agent untuk melakukan analisis terhadap aktivitas pegawai (keselarasan dengan proses bisnis, pohon kinerja organisasi, dan nilai dasar ASN BerAKHLAK), serta Google Workspace (Sheets & Drive) sebagai penyedia database dan storage. Pegawai cukup mengirim pesan singkat di Telegram seperti chatting biasa, kemudian sistem secara otomatis memvalidasi, menganalisis, dan memberikan feedback real-time dalam waktu lebih kurang 15 detik tentang relevansi pekerjaan mereka terhadap proses bisnis, kinerja organisasi, dan nilai dasar ASN. Solusi ini menjawab akar masalah mengenai lemahnya akuntabilitas kinerja ASN dengan menyediakan mekanisme dokumentasi yang praktis, sederhana, namun mampu mendukung pengelolaan dan penilaian kinerja ASN berbasis bukti dan data.

Tujuan Proyek : 
Mendukung digitalisasi kinerja ASN dengan sistem yang transparan, efisien, dan terotomasi, sejalan dengan semangat Smart Governance dan nilai BerAKHLAK ASN.

Fitur Utama :
🗓️ Input Aktivitas Otomatis: ASN dapat menginput aktivitas harian melalui bot chat dengan integrasi spreadsheet.
🧠 Analisis Kinerja: Setiap aktivitas dianalisis otomatis untuk mencocokkan indikator BerAKHLAK dan kesesuaian dengan Proses Bisnis dan Pohon Kinerja Instansi menggunakan AI Agent.
📊 Rekap dan Laporan: Data aktivitas dikelompokkan dan diekspor menjadi laporan kinerja (Spreadsheet).
🔗 Integrasi Fleksibel: Terhubung dengan Google Sheets sesuai kebutuhan instansi.
🔔 Notifikasi Otomatis: Pengingat atau ringkasan aktivitas dapat dikirim otomatis ke chat platform (misalnya Telegram).

Teknologi & Tools
- n8n Workflow Automation
- Google Sheets API
- Telegram API Integration
- AI Assistant (Agent) Integration (JEJAK ASN)

📘 Alur Utama Workflow
1. User Input: ASN mengisi aktivitas melalui chatbot.
2. Validasi Data: Workflow memeriksa kelengkapan dan kesesuaian data.
3. Analisis AI : Aktivitas dianalisis otomatis untuk menentukan indikator BerAKHLAK dan relevansi terhadap probis dan pokin instansi.
4. Penyimpanan & Rekap: Data disimpan ke spreadsheet.
5. Laporan Otomatis: Workflow menghasilkan laporan mingguan/bulanan dalam format sheet.

Cara Instalasi
1️⃣ Import Workflow
- Buka n8n.
- Buat Workflow Baru
- Klik Import Form FIle pad ... di pojok kanan atas.
- Unggah file JejakASN.json.

2️⃣ Konfigurasi Kredensial
Pastikan kamu sudah menyiapkan kredensial berikut:
- Google Sheets API
- Google Docs API
- Telegram Bot API (BotFather)
- API AI Agen (ChatGPT, Gemini, Claude dll)
