# 📘 README – Video Downloader Premium

## 🚀 Overview

Video Downloader Premium adalah aplikasi web modern untuk mengunduh video dari berbagai platform:

* YouTube (dengan **yt-dlp**, 100% stabil)
* TikTok (No Watermark)
* Instagram
* Facebook

Backend berbasis **Node.js + Express**, frontend menggunakan tampilan **Glassmorphism Premium UI** yang responsif.

---

## ✨ Features

* 🔥 Download YouTube 144p–4K + Audio
* 🔥 TikTok No Watermark (via TikWM API)
* 🔥 Instagram Reels / Video support
* 🔥 Facebook HD downloader
* 🌙 Light/Dark Mode Toggle
* 🎨 Premium modern animations
* 📱 Fully Mobile Optimized
* 🚀 Extremely fast extraction engine

---

## 📁 Project Structure

```
/project
│── public/
│    └── index.html (UI Premium)
│── server.js (backend API)
│── package.json
```

---

## 🛠 Installation

```
npm install
```

---

## ▶️ Start Server

```
node server.js
```

Server berjalan di:

```
http://localhost:3000
```

---

## 🚀 Deploy (Gratis) via Render.com

1. Push kode ke GitHub
2. Buka [https://render.com](https://render.com)
3. **New → Web Service**
4. Connect repo kamu
5. Build command:

```
npm install
```

6. Start command:

```
node server.js
```

7. Pilih **Free Tier**, lalu deploy.

---

# 🌐 SEO Metadata

Gunakan ini pada `<head>` file HTML landing page kamu:

```html
<meta name="title" content="Premium Video Downloader | YouTube, TikTok, Instagram, Facebook">
<meta name="description" content="Download video dari YouTube, TikTok (No Watermark), Instagram, dan Facebook dengan cepat, gratis, dan tanpa batas. Resolusi hingga 4K.">
<meta name="keywords" content="video downloader, download youtube, download tiktok no watermark, download instagram, download facebook, yt downloader, tiktok downloader, reels downloader">
<meta name="robots" content="index, follow">
<meta property="og:title" content="Premium Video Downloader">
<meta property="og:description" content="Downloader tercepat & gratis untuk YouTube, TikTok, Instagram, Facebook.">
<meta property="og:image" content="/thumbnail.png">
<meta property="og:type" content="website">
<meta name="theme-color" content="#000000">
```

---

# 🎨 Landing Page Premium (index.html)

Berikut adalah landing page modern yang bisa kamu jadikan halaman depan sebelum masuk ke aplikasi downloader.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Premium Video Downloader</title>

  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #000, #1b1b1b);
      color: white;
      overflow-x: hidden;
    }

    .hero {
      text-align: center;
      padding: 120px 20px;
      animation: fadeIn 1s ease;
    }

    h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    p {
      opacity: 0.8;
      font-size: 1.2rem;
      margin-bottom: 35px;
    }

    .btn {
      padding: 15px 25px;
      background: linear-gradient(135deg, #ff00cc, #3333ff);
      color: white;
      border-radius: 14px;
      font-size: 1.1rem;
      font-weight: 600;
      text-decoration: none;
      transition: 0.3s;
    }

    .btn:hover {
      transform: scale(1.05);
      box-shadow: 0 0 20px rgba(255, 0, 221, 0.5);
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <div class="hero">
    <h1>Premium Video Downloader</h1>
    <p>Download YouTube, TikTok, IG & Facebook dalam kualitas terbaik.</p>
    <a class="btn" href="/public/index.html">Mulai Download</a>
  </div>

</body>
</html>
```

---

# 🎯 Semua selesai!

Jika kamu ingin:

* Membuat versi PWA (bisa install jadi aplikasi)
* Menambah analytics
* Custom domain + SSL

Cukup bilang saja **"tambahkan fitur lanjutan"**.
