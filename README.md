# AMT Investment Manager — Deployment Guide

## 📱 Cara Install di Android (Tanpa Coding!)

### Step 1: Host App (Gratis)
Pilih salah satu:

**Option A — Netlify (Paling Gampang)**
1. Buka https://app.netlify.com/drop
2. Drag & drop folder `pwa-invest` ke halaman Netlify
3. Done! Kamu dapat URL seperti: `https://random-name.netlify.app`

**Option B — Vercel**
1. Buka https://vercel.com (sign up gratis pakai GitHub)
2. Upload folder `pwa-invest`
3. Deploy — dapat URL

**Option C — GitHub Pages**
1. Buat repo baru di GitHub
2. Upload semua file
3. Settings → Pages → Deploy from main branch

### Step 2: Convert ke APK
1. Buka https://www.pwabuilder.com/
2. Paste URL dari Step 1
3. Klik "Package for stores" → pilih "Android"
4. Download APK file
5. Selesai! Share APK via WhatsApp/Telegram/file transfer

### Step 3: Install APK
1. Transfer file APK ke HP Android
2. Buka file APK
3. Jika diminta "Install from unknown sources" → Allow
4. Install selesai — app muncul di home screen

---

## 🔑 Setiap User Perlu:
- Anthropic API Key (dari https://console.anthropic.com)
- Biaya: ~$3-15/bulan tergantung penggunaan
- Key diinput saat pertama buka app

---

## 📁 File Structure
```
pwa-invest/
├── index.html        ← Main app (semua logic di sini)
├── manifest.json     ← PWA configuration
├── sw.js             ← Service worker (offline support)
├── icons/
│   ├── icon-192.png  ← App icon small
│   └── icon-512.png  ← App icon large
└── README.md         ← File ini
```

---

## ✨ Fitur
- 💬 Chat dengan Claude AI (AMT Framework v3.4 embedded)
- 🇺🇸🇮🇩 Dual Portfolio: US & IDX toggle
- 🏥 Shortcut: health, rebal, watchlist, market update, allocate
- 📁 Portfolio input form
- 🧮 Quick allocation calculator
- 🕒 Chat history
- 📊 Markdown rendering (tabel, code blocks, headers)
- 📱 Installable PWA → convertible ke APK
- 🌙 Dark terminal aesthetic

---

## ⚠️ Disclaimer
Bukan financial advice. Keputusan investasi adalah tanggung jawab investor.
