# 📊 Akıllı Fatura / Gider Takipçisi

Faturalarınızı fotoğraflayın, veriler otomatik çıkarılsın, harcamalarınızı takip edin.

🔗 **Canlı Demo:** [ardamiracseckin.github.io/fatura-takip](https://ardamiracseckin.github.io/fatura-takip)

---

## ✨ Özellikler

- 📷 **OCR ile Fatura Okuma** — Tesseract.js kullanarak fatura fotoğrafından firma, tarih ve tutar otomatik çıkarılır
- 🏷️ **Otomatik Kategori Tespiti** — 10 kategori ve 100+ anahtar kelime ile akıllı sınıflandırma (Market, Yemek, Akaryakıt, Fatura, Sağlık vb.)
- 📈 **Grafik Dashboard** — Kategori bazlı doughnut grafik ve toplam/ortalama istatistikleri
- ⬇️ **Excel (.xlsx) Export** — SheetJS ile gerçek Excel dosyası indirme
- ⬇️ **CSV Export** — Tüm kayıtları CSV olarak dışa aktarma
- 🗑️ **Satır Bazlı Silme** — Tek tek kayıt silebilme
- 📱 **PWA Desteği** — Telefon ve masaüstüne uygulama olarak kurulabilir, çevrimdışı çalışır

---

## 🚀 Kurulum (Yerel)

```bash
# Repoyu klonla
git clone https://github.com/ardamiracseckin/fatura-takip.git
cd fatura-takip

# Yerel sunucu başlat (Python)
python -m http.server 8000
```

Tarayıcıda `http://localhost:8000` adresini aç.

> ⚠️ OCR ve PWA özellikleri `file://` protokolünde çalışmaz, mutlaka bir sunucu üzerinden açın.

---

## 📱 Uygulamayı Yükleme

| Platform | Adımlar |
|----------|---------|
| **iPhone** | Safari → Paylaş → Ana Ekrana Ekle |
| **Android** | Chrome → "Uygulamayı Yükle" bildirimine tıkla |
| **Mac** | Safari → File → Add to Dock |
| **Windows** | Chrome → Adres çubuğu sağındaki ⊕ ikonuna tıkla |

---

## 🛠️ Kullanılan Teknolojiler

| Kütüphane | Amaç |
|-----------|------|
| [Tesseract.js](https://github.com/naptha/tesseract.js) | Tarayıcı tabanlı OCR |
| [Chart.js](https://www.chartjs.org/) | Grafik ve görselleştirme |
| [SheetJS (xlsx)](https://sheetjs.com/) | Excel dosyası oluşturma |
| Service Worker | PWA / çevrimdışı destek |

---

## 📁 Dosya Yapısı

```
fatura-takip/
├── index.html      # Ana uygulama (tek dosya)
├── manifest.json   # PWA manifest
├── sw.js           # Service Worker
└── README.md
```

---

## 🗂️ Desteklenen Kategoriler

🛒 Market · 🍔 Yemek & Restoran · ⛽ Akaryakıt · 💡 Fatura · 💊 Sağlık · 🚌 Ulaşım · 👗 Giyim · 🎮 Eğlence · 📚 Eğitim · 💻 Teknoloji · 📦 Diğer

---

## 📄 Lisans

MIT License — dilediğiniz gibi kullanabilirsiniz.
