# n8n Workflows Collection

📌 Repository ini berisi kumpulan **workflow n8n** yang digunakan sebagai eksperimen, dokumentasi, dan contoh implementasi integrasi berbagai layanan.  
Semua workflow di sini merupakan pendamping dari artikel Medium yang saya tulis.  

---

## 🚀 Getting Started

### 1. Install n8n
Ikuti panduan instalasi n8n dengan Docker:  
👉 [How to deploy n8n with Docker](https://medium.com/@andriantriputra/n8n-how-to-deploy-n8n-with-docker-96c43fa8ade0)

Setelah n8n terpasang, Anda bisa mengimpor file JSON workflow dari repository ini langsung ke dalam **n8n Editor**.

---

## 📂 Workflows

| No | Workflow | Deskripsi | Artikel |
|----|----------|-----------|---------|
| 1 | **Telegram + AI Agent** | Integrasi Telegram dengan AI Agent di n8n | [Baca artikel](https://medium.com/@andriantriputra/n8n-getting-started-with-ai-agent-at-telegram-a64fe95e5c3d) |
| 2 | **MQTT Starter** | Getting started dengan MQTT dan n8n | [Baca artikel](https://andriantriputra.medium.com/n8n-getting-started-with-mqtt-bdbffc32a609) |
| 3 | **Discord Webhook + AI Agent** | Integrasi Discord Webhook dengan AI Agent | [Baca artikel](https://medium.com/@andriantriputra/n8n-integrated-n8n-discord-webhooks-and-ai-in-action-0117f437874c) |
| 4 | **RabbitMQ + Discord** | Integrasi RabbitMQ dengan Discord | [Baca artikel](https://medium.com/@andriantriputra/n8n-how-to-integrate-rabbit-and-discord-7dfb382de25e) |
| 5 | **Coin Gecko** | Menggunakan Node CoinGecko untuk data harga crypto | [Baca artikel](https://andriantriputra.medium.com/n8n-getting-started-with-node-coin-gecko-51bdad4aea12) |
| 6 | **Postgres Starter** | Getting started integrasi n8n dengan PostgreSQL | [Baca artikel](https://andriantriputra.medium.com/n8n-getting-started-with-n8n-postgres-c70671baf5dd) |
| 7 | **Comedy Journal** | Automasi jurnal komedi dengan Telegram + Google Docs + GenAI | [Baca artikel](https://andriantriputra.medium.com/n8n-automating-comedy-bit-journaling-with-telegram-gen-ai-and-google-docs-fa4a9146fea5) |
| 8 | **Inventory with Google Sheets** | Inventory sederhana dengan Google Sheets | [Baca artikel](https://andriantriputra.medium.com/n8n-getting-started-with-google-sheet-for-simple-inventory-ea7bbf09c557) |
| 9 | **Inventory with PostgreSQL** | Inventory dengan integrasi AI Agent + PostgreSQL | [Baca artikel](https://andriantriputra.medium.com/n8n-inventory-integrasi-ai-dan-postgresql-2e3d513edee9) |
| 10 | **Personal Assistant (Google Calendar)** | Personal assistant sederhana dengan Google Calendar | [Baca artikel](https://andriantriputra.medium.com/n8n-simple-personal-assistant-with-google-calendar-95f8a6e7338a) |

---

## 📥 Import Workflow ke n8n

1. Buka **n8n Editor**.  
2. Klik menu **Import** (ikon ⬆️ di pojok kanan atas).  
3. Pilih file JSON dari repository ini.  
4. Simpan, lalu jalankan workflow. 🚀  

---

## ⚠️ Catatan Penting

- Jangan commit **API key**, **token**, atau **password** ke dalam workflow JSON.  
- Gunakan **Environment Variables** (`.env`) atau **Credentials Manager** n8n untuk menyimpan data sensitif.  
- Jika menemukan credential di workflow ini, segera **regenerate** token/password terkait.

---

## 📜 Lisensi

MIT License – silakan gunakan, modifikasi, dan eksperimen dengan workflow ini.
