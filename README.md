# Sidekick Android Navigasyon Uygulaması

Sidekick, kullanıcıların sesli komutlarla rota belirleyip hedeflerine kolayca ulaşmalarını sağlayan, Mapbox ile entegre edilmiş bir Android navigasyon uygulamasıdır.

## Özellikler

- **Sesli Komut ile Adres Girişi**: Kullanıcılar sesli komut kullanarak adres girebilir ve rota oluşturabilir.
- **Gerçek Zamanlı Konum Takibi**: Kullanıcının konumunu gerçek zamanlı izler ve kamerayı buna göre günceller.
- **Sesli Yönlendirmeler**: Rota boyunca kullanıcıya sesli yönlendirmeler sunar.
- **Mapbox Entegrasyonu**: Güçlü harita ve navigasyon servisleri sağlar.
- **İzin Yönetimi**: Dinamik olarak gerekli izinleri talep eder ve yönetir.

## Kurulum ve Yapılandırma

### Gereksinimler

- Android Studio Arctic Fox veya üstü
- Android 9.0 (API level 28) veya üstü
- Mapbox API Anahtarı

### Adımlar

1. **Projeyi Klonlayın**:
   ```bash
   git clone https://github.com/aydogdu25/sidekick-navigasyon-uygulamasi.git
   cd sidekick-navigasyon-uygulamasi

2. **API Anahtarınızı Girin**:
    - `app/src/main/res/values` klasöründe bulunan `developer-config.xml` dosyasında belirtilen yere Mapbox API anahtarınızı kopyalayın.
    - `gradle.properties` dosyasında belirtilen yere Mapbox API anahtarınızı kopyalayın.

3. **Kullanım**
 - Emülatörde veya bir mobil cihazda çalıştırmak için uygulamayı derleyin ve başlatın.
