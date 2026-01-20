# SOP Dashboard ZUMA Group

Dashboard untuk mengelola dan mengakses Standard Operating Procedures (SOP).

## Fitur

- Kategori SOP berdasarkan departemen
- Pencarian SOP
- PDF Viewer
- AI Chatbot Assistant
- Voice Input & Output
- Responsive Design

## Kategori Departemen

- HRGA
- Operasional
- R&D
- FATAL
- CNM
- Online
- Wholesale
- Warehouse

## Tech Stack

- HTML, CSS, JavaScript (Vanilla)
- Web Speech API (Voice)
- SpeechSynthesis API (TTS)
- Hosting: GitHub Pages

## SOP yang Tersedia

| No | Kode SOP | Judul | Kategori |
|----|----------|-------|----------|
| 1 | ZUMA-SOP-HO-06 | SOP Return Barang Wholesale | Wholesale |
| 2 | CV-UBB-SOP-HO-01 | SOP Perdagangan Wholesale | Wholesale |

## URLs

- **Frontend**: https://database-zuma.github.io/sop-dashboard/
- **API Backend**: https://sop-dashboard-api-production.up.railway.app

## Cara Upload SOP Baru

1. Upload PDF ke Google Drive
2. Set sharing ke "Anyone with link"
3. Ambil file ID dari URL
4. Gunakan format: `https://drive.google.com/file/d/{FILE_ID}/preview`
5. Tambahkan ke array `sopData` di `index.html`

## AI Features

- **Chatbot**: Tanya jawab tentang SOP
- **Voice Input**: Klik icon mic untuk berbicara
- **Voice Output**: AI membacakan jawaban
- **Search Pintar**: Pencarian berbasis AI

## Changelog

### v1.0.0 (20 Jan 2026)
- Initial release dengan AI Assistant
- 2 SOP Wholesale tersedia
- Voice input/output
