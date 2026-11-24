# Pulau Terakhir — Survival Island

Game 2D top-down adventure survival. Bisa dimainkan langsung di browser desktop maupun Android mobile browser. Mendukung instalasi sebagai PWA dan dapat dibungkus menjadi aplikasi Android menggunakan Capacitor.

## Fitur prototype
- Kontrol keyboard (WASD / panah) dan joystick layar sentuh.
- Dunia pulau dengan sumber daya kayu, batu, dan buah beri.
- Status kesehatan, lapar, dan haus.
- Crafting api unggun dan kapak sederhana.
- Siklus hari dan malam.
- Penyimpanan progres lokal di perangkat.
- PWA offline setelah kunjungan pertama.

## Jalankan di web
Buka `index.html`, atau jalankan server lokal:

```bash
python -m http.server 8080
```

Lalu buka `http://localhost:8080`.

## Build Android (APK)
Persyaratan: Node.js, Android Studio, Android SDK.

```bash
npm install
npx cap add android
npx cap sync android
npx cap open android
```

Di Android Studio pilih **Build > Build Bundle(s) / APK(s) > Build APK(s)**. APK debug akan tersedia di folder `android/app/build/outputs/apk/debug/`.

Untuk pembaruan setelah mengubah game:

```bash
npx cap sync android
```

## Publikasi GitHub Pages
Upload isi folder ini ke repository GitHub, aktifkan **Settings > Pages > Deploy from a branch**, lalu pilih branch `main` dan folder `/root`.

## Hak cipta
© Muhammad Hafizd Anshari. All rights reserved.
