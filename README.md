# 📊 Günün Sorusu - Farcaster Mini App

Farcaster için basit ve şık bir günlük oylama uygulaması. Tek HTML dosyası, sıfır konfigürasyon!

## ✨ Özellikler

- 🎯 **Tek dosya** - Kurulum gerektirmez
- 👤 **Farcaster entegrasyonu** - Kullanıcı adı ve FID gösterir
- 📊 **Canlı sonuçlar** - Animasyonlu grafik barlar
- 📱 **Mobil uyumlu** - Her cihazda mükemmel görünüm
- 🎨 **Modern tasarım** - Gradient ve animasyonlar
- 🔗 **Paylaşım** - Sonuçları direkt Farcaster'da paylaş

## 🚀 Nasıl Kullanılır?

### 1. GitHub'dan Deploy Et

Bu repo'yu fork'la veya direkt Vercel'e deploy et:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/KULLANICI_ADINIZ/farcaster-daily-question)

### 2. Manuel Deploy

1. Bu repo'yu clone'la veya download et
2. [vercel.com](https://vercel.com) 'a git
3. "Import Project" ile bu klasörü seç
4. Deploy'a bas
5. Bitti! 🎉

### 3. Farcaster'da Test Et

1. [farcaster.xyz/~/settings/developer-tools](https://farcaster.xyz/~/settings/developer-tools) adresine git
2. "Developer Mode"u aç
3. Vercel URL'ini Farcaster'da aç
4. Cast olarak paylaş!

## 🎨 Özelleştirme

`index.html` dosyasını düzenleyerek uygulamayı özelleştirebilirsiniz:

### Soruyu Değiştir

```html
<div class="question">
    <span class="question-emoji">🤔</span>
    Buraya kendi sorunuzu yazın
</div>
```

### Seçenekleri Değiştir

```html
<button class="option" onclick="vote(0)">
    ✅ İlk seçenek
</button>

<button class="option" onclick="vote(1)">
    😊 İkinci seçenek
</button>

<button class="option" onclick="vote(2)">
    ❌ Üçüncü seçenek
</button>
```

### Renkleri Değiştir

CSS'te gradient renklerini değiştirebilirsiniz:

```css
/* Ana arka plan */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Buton rengi */
background: linear-gradient(135deg, #667eea, #764ba2);
```

## 📁 Proje Yapısı

```
.
├── index.html          # Ana uygulama dosyası (tüm kod burada)
└── README.md          # Bu dosya
```

## 🔧 Teknik Detaylar

- **Framework:** Vanilla JavaScript (framework yok!)
- **SDK:** @farcaster/miniapp-sdk
- **Styling:** Pure CSS (Tailwind yok!)
- **Hosting:** Vercel öneriliyor
- **Boyut:** ~15KB (çok hafif!)

## 💡 Geliştirme Fikirleri

- [ ] Her gün otomatik yeni soru
- [ ] Cevapları database'de sakla
- [ ] Kullanıcı geçmişi
- [ ] NFT badge sistemi
- [ ] Leaderboard ekle
- [ ] Çoklu dil desteği
- [ ] Dark mode
- [ ] Emoji reaksiyonlar

## 🐛 Sorun Giderme

### Uygulama açılmıyor
- Tarayıcı console'unu kontrol edin (F12)
- Vercel URL'inin doğru olduğundan emin olun
- Cache'i temizleyip yeniden deneyin

### Farcaster bilgileri gelmiyor
- Developer Mode'un açık olduğunu kontrol edin
- Uygulamanın Farcaster client içinde açıldığından emin olun
- SDK yüklenmese bile uygulama demo modunda çalışır

### Vercel deploy hatası
- `index.html` dosyasının repo'nun root'unda olduğundan emin olun
- Vercel'de "Framework Preset" olarak "Other" seçin

## 📱 Demo

[Canlı demo'yu buradan deneyin →](#) (Deploy sonrası buraya URL ekle)

## 🤝 Katkıda Bulunma

Pull request'ler memnuniyetle karşılanır! Büyük değişiklikler için lütfen önce bir issue açın.

1. Fork'layın
2. Feature branch oluşturun (`git checkout -b feature/harika-ozellik`)
3. Commit'leyin (`git commit -m 'Harika özellik eklendi'`)
4. Push'layın (`git push origin feature/harika-ozellik`)
5. Pull Request açın

## 📄 Lisans

MIT License - İstediğiniz gibi kullanın, değiştirin, paylaşın!

## 🌟 Yıldız Vermeyi Unutmayın!

Bu proje işinize yaradıysa ⭐ vermeyi unutmayın!

## 📞 İletişim

Sorularınız için:
- Farcaster:
- Twitter: 
- Email:

---

Made with ❤️ for Farcaster Community

🔗 [Farcaster](https://farcaster.xyz) | 📚 [Docs](https://docs.farcaster.xyz) | 💬 [Discord](https://discord.gg/farcaster)
