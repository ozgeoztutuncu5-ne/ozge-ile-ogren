# 🎮 Özge ile Öğren

İlkokul çocuklarına çarpım tablosunu eğlenceli ve interaktif bir şekilde öğreten web tabanlı oyun. Topmarks tarzında hızlı pratik ve rahat öğrenme modları ile tasarınlanmıştır.

## 🌟 Özellikler

- **Başlangıç Ekranı:** Oyun modu seçimi (Süreli/Pratik) ve çarpım tablosu seçimi
- **Süreli Mod:** 60 saniye içinde mümkün olduğunca çok soruya cevap verme
- **Pratik Modu:** Süresiz, rahat öğrenme ortamı
- **Çocuk Dostu Arayüz:** Canlı renkler, büyük fontlar, kolay anlaşılır tasarım
- **Anlık Geri Bildirim:** Doğru/yanlış cevaplara görsel ve işitsel geri bildirim
- **Skor Sistemi:** Doğru ve yanlış cevap sayısı, başarı oranı
- **Responsive Tasarım:** Masaüstü, tablet ve mobil cihazlarda mükemmel görünüm
- **1-10 Arası Çarpım Tabloları:** Kullanıcı seçimine göre farklı çarpım tablolarında pratik yapma

## 🚀 Hızlı Başlangıç

### Gereksinimler

- Node.js 18+ ve npm/pnpm
- Modern web tarayıcısı

### Kurulum

```bash
# Repository'yi klonla
git clone https://github.com/yourusername/ozge-ile-ogren.git
cd ozge-ile-ogren

# Bağımlılıkları yükle
pnpm install

# Geliştirme sunucusunu başlat
pnpm dev
```

Tarayıcınızda `http://localhost:3000` adresine gidin.

### Üretim İçin Derleme

```bash
# Üretim versiyonunu derle
pnpm build

# Derlenmiş dosyaları sunmak için
pnpm preview
```

## 📖 Nasıl Oynanır?

1. **Oyun Modunu Seç:** Süreli (60 saniye) veya Pratik (Süresiz) modunu seç
2. **Çarpım Tablolarını Seç:** Pratik yapmak istediğin çarpım tablolarını seç (örneğin: 3x, 5x, 7x)
3. **Oyunu Başlat:** "Oyunu Başlat" düğmesine tıkla
4. **Soruları Cevapla:** Gösterilen çarpma işleminin doğru cevabını seç
5. **Sonuçları Gör:** Oyun bittiğinde başarı oranını ve istatistikleri gör
6. **Tekrar Oyna:** "Tekrar Oyna" düğmesi ile yeni bir oyun başlat

## 🎨 Tasarım Özellikleri

- **Renk Paleti:** Mor ve indigo gradyanı arka plan, beyaz kartlar, canlı buton renkleri
- **Tipografi:** Okunaklı, çocuk dostu fontlar
- **Animasyonlar:** Sorudan soruya geçişte yumuşak animasyonlar, cevap geri bildirimi
- **Mobil Uyumluluk:** Tüm ekran boyutlarında optimal görünüm

## 🛠️ Teknoloji Stack

- **Frontend:** React 19 + TypeScript
- **Styling:** CSS3 (Responsive Design)
- **Build Tool:** Vite
- **Audio:** Web Audio API (Geri bildirim sesleri)

## 📁 Proje Yapısı

```
carpim-tablosu-oyunu/
├── client/
│   ├── src/
│   │   ├── pages/
│   │   │   └── Game.tsx          # Ana oyun bileşeni
│   │   ├── styles/
│   │   │   └── game.css          # Oyun stilleri
│   │   ├── App.tsx               # Ana uygulama bileşeni
│   │   ├── main.tsx              # Giriş noktası
│   │   └── index.css             # Global stiller
│   ├── public/                   # Statik dosyalar
│   └── index.html                # HTML şablonu
├── README.md                     # Bu dosya
└── package.json                  # Proje bağımlılıkları
```

## 🎯 Eğitim Hedefleri

Bu oyun aşağıdaki eğitim hedeflerini destekler:

- Çarpım tablosunun hızlı ve doğru şekilde hatırlanması
- Zihinsel matematik becerilerinin geliştirilmesi
- Eğlenceli öğrenme ortamında matematiksel güven kazanılması
- Tekrarlı pratik yoluyla kalıcı öğrenme

## 📱 Cihaz Uyumluluğu

- ✅ Masaüstü (Chrome, Firefox, Safari, Edge)
- ✅ Tablet (iPad, Android tabletler)
- ✅ Mobil (iPhone, Android telefonlar)

## 🔊 Ses Özellikleri

Oyun, doğru ve yanlış cevaplara anlık işitsel geri bildirim sağlar:

- **Doğru Cevap:** Yüksek ton (800 Hz) - 0.2 saniye
- **Yanlış Cevap:** Düşük ton (300 Hz) - 0.3 saniye

## 📊 Skor Sistemi

Oyun sonunda şu istatistikler gösterilir:

- Doğru cevap sayısı
- Yanlış cevap sayısı
- Toplam soru sayısı
- Başarı oranı (%)

## 🐛 Bilinen Sorunlar

Şu anda bilinen bir sorun yoktur. Sorun bulursanız, lütfen bir issue açın.

## 🤝 Katkıda Bulunma

Katkılarınız hoş geldiniz! Lütfen şu adımları izleyin:

1. Repository'yi fork edin
2. Feature branch'i oluşturun (`git checkout -b feature/AmazingFeature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add some AmazingFeature'`)
4. Branch'i push edin (`git push origin feature/AmazingFeature`)
5. Pull Request açın

## 📄 Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Ayrıntılar için [LICENSE](LICENSE) dosyasına bakın.

## 👨‍💻 Geliştirici

Çarpım Tablosu Oyunu, ilkokul öğrencilerine matematiksel beceriler kazandırmak amacıyla geliştirilmiştir.

## 📞 İletişim

Sorularınız veya önerileriniz için lütfen bir issue açın veya bize e-posta gönderin.

---

**Eğlenceli öğrenme için oyunu oynayın! 🎮✨**

