# C++ Order Planning & Logistics Simulation

Bu proje, **Bilişim Sistemleri Mühendisliği** "Programlamaya Giriş" dersi kapsamında, C++ dilinin bellek yönetimi ve dosya işleme yeteneklerini pekiştirmek amacıyla geliştirilmiştir. Rastgele sipariş oluşturma, en düşük/yüksek tutar analizi ve dağıtım rotası simülasyonu yapar.

## 🚀 Özellikler

* **Pointer Aritmetiği:** Diziler üzerinde pointerlar (`int*`) kullanılarak bellek adresleri üzerinden işlem yapıldı.
* **Dosya İşlemleri (File I/O):** Oluşturulan sipariş listesi ve raporlar `siparişler.txt` dosyasına otomatik olarak kaydedilir.
* **Renkli Konsol Çıktısı:** ANSI kaçış kodları kullanılarak en düşük ve en yüksek siparişler terminalde farklı renklerle vurgulandı.
* **Rastgele Veri Üretimi:** `<random>` kütüphanesi ile modern randomizasyon teknikleri kullanıldı.

## 🛠 Kullanılan Teknolojiler

* C++ (Standart Kütüphaneler: `iostream`, `fstream`, `iomanip`, `random`)

## 💻 Nasıl Çalışır?

Kod derlenip çalıştırıldığında:
1.  100-1000 TL arasında rastgele 10 adet sipariş oluşturur.
2.  Pointerlar yardımıyla en düşük ve en yüksek siparişi bulup renklendirerek listeler.
3.  Siparişleri `siparisler.txt` dosyasına yazar.
4.  Dağıtım rotasını karıştırarak (shuffle) simüle eder.
5.  Sipariş farklarından oluşan bir matrisi ekrana ve dosyaya basar.
