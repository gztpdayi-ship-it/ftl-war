# FTL WAR v0.9

Bu sürüm iki ana konuya odaklanır: savaş kayıplarının düzeltilmesi ve klasik tarayıcı-strateji görünümüne daha büyük geçiş.

## Savaş motoru düzeltmesi
- Kazanan taraf artık sabit %18 kayıp vermez.
- Kayıplar saldırı gücü / savunma gücü oranından hesaplanır.
- Ezici üstünlükte saldıran taraf 0 kayba kadar düşebilir.
- Yakın güçlerde iki taraf da daha ciddi kayıp verir.
- Yağma saldırılarında kazanan tarafın kaybı normal saldırıya göre daha düşüktür.
- Savaş raporuna güç oranı bilgisi eklendi.

Örnek:
- Saldırı gücü 154.184.100
- Savunma gücü 90
- Güç oranı 1.000x'in çok üzerindedir
- Saldıran taraf kaybı 0 olur.

## Görsel dönüşüm
Kullanıcının sağladığı ekran görüntülerindeki genel yerleşim mantığından esinlenilerek FTL WAR'a özgü bir arayüz hazırlandı:
- Üstte büyük yuvarlak ana menü ikonları
- Kompakt üst kaynak çubuğu
- Sol tarafta parşömen/ahşap oyuncu panelleri
- Büyük, çevresel kaynak arazisi
- Ortasında yerleşim bulunan köy merkezi
- Nehirli/yeşil köy görünümü
- Büyük kareli dünya haritası
- Parşömen tarzı savaş raporları
- Sağ tarafta saatlik üretim özeti

Başka oyuna ait resim veya grafik dosyaları kullanılmamıştır; görünüm CSS ve FTL WAR öğeleriyle özgün olarak oluşturulmuştur.

## Ekonomi
- Genel hız: x10.000.000
- Bina/asker/kaynak alanı maliyetleri: 1x
- Süreler: x10.000.000 hız mantığı
- Dünya Harikası: 1x

## Korunan sistemler
- Kışla/Ahır seviyesine bağlı eğitim süresi
- Çok yüksek hızda matematiksel eğitim tamamlama
- Kalıcı rakip asker kayıpları
- Saldıran ve savunan detaylı raporları
- Ayrı odun/kil/demir/tahıl ganimetleri
