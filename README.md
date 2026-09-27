# Olimpiyat Defteri

5. sınıf (ortaokul 1. sınıf) matematik olimpiyatı seçme sınavına hazırlık uygulaması.

**Canlı site:** https://cagrigurbuz.github.io/olimpiyat_2/

## Özellikler
- 11 konu: sayılar ve basamaklar, bölünebilme ve asallar, EBOB–EKOK, örüntüler, sayma, problemler, kesirler, geometri, saat ve takvim, en kötü durum, mantık ve zekâ
- Her konu için özet, olimpiyat taktiği ve çözümlü örnek
- Kolay / orta / zor düzeylerde her seferinde yeniden üretilen sorular ve 24 klasik olimpiyat sorusu
- İpucu ve adım adım çözüm
- Süreli deneme sınavı (isteğe bağlı "4 yanlış 1 doğruyu götürür"), konu bazında sonuç ve puan grafiği
- Yanlışlarım listesi, karalama kâğıdı, puan ve seri takibi
- Tablete/telefona "Ana ekrana ekle" ile uygulama gibi kurulur, internetsiz de açılır

İlerleme, kullanılan cihazın tarayıcısında (localStorage) saklanır.

## Yayınlama (GitHub Pages)
Settings → Pages → Build and deployment → Source: **Deploy from a branch** → Branch: **main**, klasör: **/ (root)** → Save.
Birkaç dakika sonra site yukarıdaki adreste açılır.

## Dosyalar
| Dosya | Görev |
|---|---|
| `index.html` | Uygulamanın tamamı (tek dosya) |
| `sw.js` | Çevrimdışı çalışma için önbellek |
| `manifest.webmanifest`, `icon*.png`, `icon.svg` | Ana ekrana ekleme ve simge |
