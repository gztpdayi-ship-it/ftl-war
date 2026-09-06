# FTL WAR v0.7

FTL WAR tarayıcı tabanlı PvP strateji oyununun yedinci prototip sürümü.

## v0.7 ana düzeltmesi: gerçek x10.000.000 asker eğitim hızı
- Birlik eğitim süresi artık önce 1x sunucu süresinden hesaplanır.
- Sonra Kışla / Ahır seviye katsayısı uygulanır.
- Son olarak süre x10.000.000 sunucu hızına bölünür.
- Tokmakçı örneği:
  - Kışla Seviye 1: 1x = 90 saniye → x10.000.000 = 0,000009 saniye / birlik.
  - Kışla Seviye 20: 1x = 45 saniye → x10.000.000 = 0,0000045 saniye / birlik.
- Çok yüksek hızlarda tarayıcı her mikro saniyede ekran çizmez. Geçen zaman içinde tamamlanan birlik sayısı matematiksel olarak hesaplanıp orduya eklenir.
- Bu nedenle 100.000 veya daha yüksek eğitim kuyrukları tarayıcıyı zorlamadan doğru hızda tamamlanabilir.
- Kışla / Ahır seviyesi yükseldikçe eğitim süresi azalır.
- v0.6'dan kalan aktif eğitim kuyruğu v0.7 hız modeline otomatik geçirilir.

## v0.7 savunma ve rapor geliştirmeleri
- Test rakiplerinin gerçek birlik dağılımı vardır:
  - Muhafız
  - Mızraklı
  - Süvari
- Rakibin savunma gücü kalan askerlerine göre yeniden hesaplanır.
- Rakip asker kayıpları kalıcıdır ve sonraki saldırılara yansır.
- Saldırı ekranında hedefin mevcut savunma birlikleri ve tahmini savunma gücü gösterilir.
- Yeni savaş raporlarında savunan taraf için:
  - Başlangıç asker sayısı
  - Kayıp asker sayısı
  - Kalan asker sayısı
- Saldıran taraf için katılan / kayıp / kalan birlik detayları korunur.
- Odun, Kil, Demir ve Tahıl ganimetleri ayrı ayrı gösterilmeye devam eder.
- Sağ taraftaki saatlik hammadde üretim paneli korunur.

## Sunucu kuralları
- Genel hız: x10.000.000
- Merkez köy kaynak alanları: maksimum 30
- Diğer köyler: maksimum 20
- Dünya Harikası: 1x

## Önemli
Bu sürüm GitHub Pages üzerinde çalışan tarayıcı prototipidir. Gerçek çok oyunculu dünya için sonraki aşamalarda backend ve veritabanı gerekir.
