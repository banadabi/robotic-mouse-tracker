
## 🎮 Etkileşimler

Robotla şu şekillerde etkileşime geçebilirsiniz:

- **Selam Ver Butonu:** Robot el sallar
- **Adım At Butonu:** Robot adım atar
- **Dans Et Butonu:** Robot dans eder
- **Fareyi Takip Et Butonu:** Robot fare hareketlerini takip etmeye başlar
- **Fare Başın Üzerinde:** Fareyi robotun başının üzerine getirdiğinizde, robot fareyi yakalamaya çalışır

## 🧩 Kod Yapısı

- `components/ui/splite.tsx`: Ana Spline bileşeni ve robot etkileşimleri
- `components/ui/spotlight.tsx`: Spot ışık efekti
- `components/ui/card.tsx`: Kart bileşeni

## 🎨 Özelleştirme

Robotu özelleştirmek için:

1. Spline sahne URL'sini değiştirin
2. Animasyon parametrelerini ihtiyacınıza göre ayarlayın
3. CSS ve sınıfları düzenleyin

## 📚 API Referansı

### SplineScene Props

| Prop | Tip | Açıklama |
|------|-----|----------|
| scene | string | Spline sahnesinin URL'si |
| className | string (opsiyonel) | Bileşene eklenecek CSS sınıfları |

## 🔗 Kaynaklar

- [Spline Dokümantasyonu](https://docs.spline.design/)
- [React Spline](https://www.npmjs.com/package/@splinetool/react-spline)
- Orijinal çalışma: [https://21st.dev/serafimcloud/splite/default](https://21st.dev/serafimcloud/splite/default)

## 🤝 Katkıda Bulunma

1. Bu depoyu forklayın
2. Özellik dalınızı oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add some amazing feature'`)
4. Dalınıza push edin (`git push origin feature/amazing-feature`)
5. Bir Pull Request açın

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır.
