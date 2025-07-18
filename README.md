# 🤖 OpenAI Chatbot Starter Kit

Starter kit chatbot sederhana menggunakan OpenAI API yang siap pakai.

## ✨ Fitur

- **Interface Modern**: Desain yang clean dan responsive
- **Real-time Chat**: Percakapan langsung dengan OpenAI GPT
- **Penyimpanan Lokal**: API key tersimpan di browser
- **Mobile Friendly**: Responsif di semua perangkat
- **Easy Setup**: Tidak perlu server, langsung bisa digunakan
- **Bahasa Indonesia**: Support penuh bahasa Indonesia

## 🚀 Cara Menggunakan

### 1. Clone Repository
```bash
git clone https://github.com/jbagustw/openai-chatbot-starter.git
cd openai-chatbot-starter
```

### 2. Buka di Browser
- Double-click file `index.html`
- Atau serve menggunakan live server

### 3. Masukkan API Key
- Daftar di [OpenAI Platform](https://platform.openai.com/)
- Buat API key baru
- Masukkan API key ke dalam aplikasi

### 4. Mulai Mengobrol!
Ketik pesan dan tekan Enter atau klik tombol kirim.

## 📁 Struktur File

```
openai-chatbot-starter/
├── index.html          # File utama aplikasi
├── README.md           # Dokumentasi ini
├── LICENSE             # Lisensi MIT
└── .gitignore          # Git ignore file
```

## 🔧 Kustomisasi

### Mengubah Model AI
Edit bagian ini di `index.html`:
```javascript
model: 'gpt-3.5-turbo',  // Ganti dengan 'gpt-4' untuk model yang lebih canggih
```

### Mengubah System Prompt
Edit bagian ini untuk mengubah perilaku AI:
```javascript
{
    role: 'system',
    content: 'Anda adalah asisten AI yang helpful, harmless, dan honest. Jawab dalam bahasa Indonesia kecuali diminta lain.'
}
```

### Mengubah Tema Warna
Edit variabel CSS di bagian `<style>`:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

## 🛠️ Pengembangan Lanjutan

### Menambah Fitur
- **File Upload**: Tambahkan kemampuan upload gambar
- **Voice Input**: Integrasi speech-to-text
- **Export Chat**: Simpan percakapan ke file
- **Multiple Models**: Pilihan model AI yang berbeda

### Integrasi Backend
Untuk production, pertimbangkan:
- Proxy API key melalui backend
- Database untuk menyimpan percakapan
- Rate limiting dan monitoring
- Authentication pengguna

## 🔒 Keamanan

⚠️ **Penting**: 
- Jangan commit API key ke repository
- Gunakan environment variables untuk production
- Implementasi rate limiting
- Validasi input pengguna

## 📱 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 🤝 Kontribusi

Kontribusi sangat diterima! Silakan:

1. Fork repository ini
2. Buat branch feature (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

## 📄 Lisensi

Project ini menggunakan lisensi MIT. Lihat file `LICENSE` untuk detail lengkap.

## 🙏 Acknowledgments

- [OpenAI](https://openai.com/) untuk API yang luar biasa
- Komunitas developer Indonesia
- Semua contributor yang telah membantu

## 📞 Support

Jika ada pertanyaan atau butuh bantuan:
- Buat issue di repository ini
- Email: bagus@innobi.id