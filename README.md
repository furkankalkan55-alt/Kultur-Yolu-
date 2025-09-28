# Kültür Yolu (APK + PWA)

Bu depo, yerel CSV'ler gömülü tam çalışan quiz uygulamasıdır.

## İçerik
- `www/` — PWA dosyaları (index, manifest, service worker, ikonlar, **data/** klasöründe CSV'ler)
- `.github/workflows/build-android.yml` — GitHub Actions ile **APK** üretir
- `package.json` ve `capacitor.config.json` — Capacitor yapılandırması (Android sarmalayıcı)

## APK nasıl alınır?
1. Bu repo içeriğini GitHub'a yükle.
2. **Actions → Build Android APK → Run workflow**.
3. Koşu bitince sayfanın altındaki **Artifacts → kultur-yolu-debug-apk**'dan APK'yı indir.

## Soruları kalıcı yapmak
Sorular `www/data/kolay.csv | orta.csv | zor.csv` içindedir. İçeriğini kendi sorularınla değiştir.
CSV başlıkları zorunlu: `Alan,Seviye,Soru,A,B,C,D,Doğru Cevap`

## Web’de yayın (opsiyonel)
`www/` klasörünü Netlify/Vercel/Pages’e yükleyerek PWA olarak kullanabilirsin.
