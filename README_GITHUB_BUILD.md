# Animal World Kids V17.1 — GitHub APK Build

Bu paket, APK'yı GitHub Actions üzerinde resmi Flutter/Android build araçlarıyla oluşturmak için hazırlanmıştır.

## En kolay kullanım

1. GitHub'da boş bir repository oluşturun.
2. Bu ZIP'in içindekileri repository'nin kök dizinine yükleyin.
3. Değişiklikleri `main` dalına kaydedin.
4. GitHub'da **Actions** sekmesine girin.
5. **Build Android APK** workflow'unu açın.
6. **Run workflow** düğmesine basın.
7. Build tamamlanınca sayfanın altındaki **Artifacts** bölümünden `Animal-World-Kids-V17-1-APK` dosyasını indirin.
8. ZIP artifact içindeki `Animal_World_Kids_V17_1.apk` dosyasını Android telefona kurun.

Workflow ayrıca `main/master` dalına kod push edildiğinde otomatik çalışır.

## Build sırasında yapılanlar

- Java 17 kurulur.
- Flutter stable kurulur.
- Android platform klasörü resmi `flutter create` komutuyla üretilir.
- Uygulama adı `Animal World Kids` olarak ayarlanır.
- `minSdk` 23 olarak ayarlanır.
- `flutter pub get` çalıştırılır.
- `flutter analyze` ile kod kontrol edilir.
- `flutter build apk --release` ile release APK oluşturulur.
- APK GitHub artifact olarak yüklenir.

## Uygulama sürümü

`pubspec.yaml`: `1.7.1+171`

Bu nedenle Android `versionCode` değeri 171 olur.
