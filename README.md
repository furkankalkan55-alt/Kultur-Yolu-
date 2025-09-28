# Kültür Yolu — OFFLINE/NO‑CDN

Bu sürüm tamamen yerel dosyalarla çalışır (CDN/Babel yok). Android WebView'da siyah ekran problemini önlemek için sade, vanilla JS ile yazıldı.

## Yapı
- `www/index.html` — tek dosya uygulama (CSS + JS gömülü)
- `www/data/*.csv` — gömülü CSV'ler
- `www/icons/*` — ikonlar
- `.github/workflows/build-android.yml`, `package.json`, `capacitor.config.json`

## APK alma
Actions → **Build Android APK**. Bittiğinde artifact'tan indir.

## Not
Önceki sürüm yüklüyse cihazda **uygulama verisini temizleyin veya kaldırıp** yeni APK'yı kurun.
