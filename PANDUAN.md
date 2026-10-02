# Panduan Memasang PWA VJS Finance

## 1. Update Apps Script
1. Ganti isi `Code.gs` dengan file `Code.gs` baru.
2. Ganti isi file HTML `Index` dengan `Index_v2.html` baru.
3. Deploy > Manage deployments > Edit > Version: New version > Deploy.
   Pastikan: Execute as **Me**, Who has access **Anyone**.
4. Salin URL Web App (berakhiran `/exec`).

## 2. Isi URL di pembungkus PWA
Buka `index.html` di folder ini, ganti `GANTI_DENGAN_URL_WEB_APP_ANDA/exec`
dengan URL dari langkah 1.

## 3. Upload folder ini ke hosting HTTPS (gratis)
- **Netlify**: buka app.netlify.com/drop, seret folder `pwa`.
- **GitHub Pages**: upload isi folder ke repo, aktifkan Pages.
- **Firebase Hosting / Cloudflare Pages**: juga bisa.

## 4. Instal di Android
Buka URL hosting di Chrome > menu (⋮) > **Instal aplikasi** (atau tombol "Instal Aplikasi" di layar).
