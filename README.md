📦  Akıllı Kargo Güvenliği ve Takip Sistemi
 Lojistik ve kargo süreçlerinde paketlerin taşıma güvenliğini artırmak amacıyla geliştirilmiş, gerçek zamanlı eğim ve duruş takibi yapan otonom bir mühendislik çözümüdür. Bu proje, Gökhan Beyaz'ın (Cand.) akademik ve endüstriyel çalışmalarının bir parçası olarak tasarlanmıştır.

🚀 Proje Hakkında
Hassas yüklerin (elektronik cihazlar, tıbbi malzemeler vb.) taşınması sırasında oluşabilecek hatalı istifleme veya devrilme durumlarını anlık olarak tespit eder. Sistem, kritik eşik değeri olan 25 derece aşıldığında görsel uyarı mekanizmasını aktif hale getirir.

✨ Temel Özellikler
Gerçek Zamanlı Takip: 6 eksenli ivmeölçer verileriyle milisaniyelik analiz.

Otonom Uyarı: Kritik açılarda donanım tabanlı (LED) ve yazılım tabanlı (UART) geri bildirim.

Endüstriyel Protokoller: Kararlı veri iletişimi için I2C ve UART entegrasyonu.

Düşük Güç Tüketimi: STM32L0 serisi mikrodenetleyici ile optimize edilmiş enerji kullanımı.

🛠️ Teknik Altyapı
Sistem mimarisi aşağıdaki bileşenler üzerine kurgulanmıştır:

Mikrodenetleyici: STM32L031K6 (ARM Cortex-M0+).

Sensör: MPU6050 (3-Axis Accelerometer & Gyroscope).

Geliştirme Ortamı: STM32CubeIDE & HAL Kütüphaneleri.

Algoritma: Trigonometrik açı hesaplama (Pitch & Roll) ve dinamik eşik karşılaştırma.

📂 Kurulum ve Kullanım
Projeyi klonlayın: git clone [https://github.com/gokhanbeyaz/otonommatik-kargo.git](https://github.com/gokhanbeyaz/otonommatik-kargo.git)

STM32CubeIDE ile projeyi açın.

Core/Src/main.c dosyasındaki donanım konfigürasyonlarını kontrol edin.

Derleyin (Build) ve hedef donanıma yükleyin.

📈 Gelecek Planları (Roadmap)
[ ] IoT Entegrasyonu: Verilerin bulut sistemine aktarılması.

[ ] Mobil Uygulama: Flutter ile kargo durum takip arayüzü.

[ ] Datalogger: Geçmişe dönük sarsıntı ve eğim kayıtlarının tutulması.
