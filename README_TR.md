# Animal World Kids — Jungle Theme Flutter Frontend

Bu proje, oluşturduğumuz çocuk dostu Animal World görsellerindeki tasarım dilini gerçek Flutter bileşenlerine dönüştürür.

## Kodlanan tema

- Orman / gökyüzü arka planı
- Yaprak ve çiçek dekorları
- Ahşap başlık panoları
- Krem renkli kabartmalı kartlar
- Parlak renkli kategori kartları
- Yıldız, elmas ve XP göstergeleri
- Minik Kaşif profil alanı
- Büyük yeşil “Maceraya Başla” butonu
- Günlük görev kartları
- 4 seçenekli quiz ekranı
- Doğru / yanlış cevap renkleri
- Quiz sonuç ve ödül ekranı
- Profil, rozet ve günlük seri ekranı
- Çocuk temalı ahşap alt menü
- Telefon/tablet genişliğine uyumlu responsive düzen

## Çalıştırma

Flutter SDK kurulu bilgisayarda proje klasöründe:

```bash
flutter create --platforms=android,ios .
flutter pub get
flutter run
```

Not: `flutter create` komutu varsayılan `lib/main.dart` oluşturursa bu paketteki `lib/` klasörünü tekrar geri kopyalayın. En güvenlisi boş platform projesi oluşturup bu paketin `lib/` ve `pubspec.yaml` dosyalarını üzerine almaktır.

## Backend bağlama

Şu an ekranlar `lib/data/demo_data.dart` ile çalışır. Daha önce hazırlanan FastAPI backend bağlanırken bu dosya yerine repository/API katmanı kullanılabilir. Tasarım widget'ları (`lib/widgets`) değişmeden kalır.

## Tasarım referansları

`design_reference/` klasöründe hazırladığımız 4 referans ekran bulunur. Bunlar yalnızca tasarım karşılaştırması içindir; uygulama tam ekran görselleri sahte arayüz olarak kullanmaz.

## V9 – Hızlı Resim
Yeni Hızlı Resim modu eklendi. Hayvan adını görüp dört görsel arasından süre dolmadan doğru resmi seç. Süre her turda azalır; seri ve hız bonusları ödülleri artırır.

## V12 ekleri
- 6 dinamik rozet ve başarım
- Başarılar & Koleksiyon ekranı
- Seviye atlama kutlama penceresi
- Seviye 12–18 arasında açılan 8 hayvan
- Profil ekranında canlı rozet ve koleksiyon sayaçları
