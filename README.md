# Bernhardt Resort Booking (GitHub Pages)

Static booking form for **Bernhardt Resort**, deployed on **GitHub Pages** and connected to a Google Apps Script Web App.

## 🔗 Live URL
After enabling GitHub Pages, access:
```
https://USERNAME.github.io/REPO-NAME/SW.BERNHARDT HOUSE  
```

## ⚙️ Configure
1) In `index.html`, replace:
```
const API_URL = 'https://script.google.com/macros/s/AKfycbwIB4y8a16zqKdfzq4FUvupwXmQynSupQU-Fk-ybHnDQIWKFfZR7JcYPhNY8ZxXDZKS/exec';
```
with your Apps Script Web App URL (Deploy `BookingAPI.gs` → Web App).

2) Ensure your Apps Script allows access:
- **Execute as:** Me
- **Who has access:** Anyone with the link

## 🚀 Deploy on GitHub Pages
- Repo → **Settings → Pages**
- **Source:** Deploy from a branch
- **Branch:** main / **Folder:** /(root)
- Save and wait ~1–3 minutes.

## 🧪 Test
Submit the form → A new row should be appended into **Receipts** sheet and a confirmation email sent.

## 📁 Files
- `index.html` – Booking form (single-file, inline CSS/JS)
- `.nojekyll` – Avoid Jekyll processing on GitHub Pages
- `README.md` – This guide

---

© 2025 Bernhardt Resort
