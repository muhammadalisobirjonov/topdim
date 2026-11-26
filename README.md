# Topdim

Rezyumesiz mediya ish va mutaxassis e'lonlari (UZ / RU / EN, qora va yorug' tema). Bitta sahifa (`index.html`), ma'lumotlar Firebase Firestore'da.

- `index.html` — butun sayt
- `firestore.rules` — Firestore xavfsizlik qoidalari (Firebase Console > Firestore > Rules ga qo'yiladi)
- `manifest.json`, `sw.js`, `icon*.png`, `apple-touch-icon.png` — telefonga ilova (PWA) sifatida o'rnatish uchun
- `og.png` — Telegram/ijtimoiy tarmoqlarda havola ko'rinishi (1200x630)

Firebase web config `index.html` ichidagi `window.FIREBASE_CONFIG` da (loyiha `topdim-5a516`). Config `null` bo'lsa sayt demo rejimda ishlaydi.
