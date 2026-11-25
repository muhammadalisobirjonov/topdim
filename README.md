# Topdim

Rezyumesiz mediya ish va mutaxassis e'lonlari (UZ / RU / EN, qora va yorug' tema). Bitta sahifa (`index.html`), ma'lumotlar Firebase Firestore'da.

- `index.html` — butun sayt
- `firestore.rules` — Firestore xavfsizlik qoidalari (Firebase Console > Firestore > Rules ga qo'yiladi)
- `manifest.json`, `icon.svg` — telefonga "ilova" sifatida o'rnatish uchun

`index.html` ichidagi `window.FIREBASE_CONFIG = null;` o'rniga Firebase web config qo'yiladi.
Config bo'lmasa sayt demo rejimda ishlaydi.
