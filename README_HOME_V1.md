# Animal World Kids — HomeScreen V1

Bu sürüm, oluşturduğumuz jungle ana sayfa referansının gerçek Flutter widget'larına çevrilmiş halidir.

## Bu sürümde gerçek kod olan bölümler
- Jungle arka plan asset'i
- Minik Kaşif profil kartı
- Level ve XP progress bar
- Yıldız / elmas sayaçları
- Ayarlar düğmesi
- Kod ile çizilen 3D hissi veren ANIMAL WORLD KIDS logo
- Maskot alanı
- Basma animasyonlu MACERAYA BAŞLA düğmesi
- Günlük görev / progress / reward kartı
- DÜNYANI SEÇ paneli
- 4 kategori kartı
- Responsive telefon genişliği desteği

## Backend'e bağlanacak değerler
HomeScreen constructor parametreleri üzerinden şimdiden dinamik:
- playerName
- level
- currentXp
- nextLevelXp
- stars
- gems
- dailyProgress
- dailyTarget

Sonraki adımda bu değerler AppController/API modelinden doğrudan beslenecek.
