# Hava Durumu Uygulaması

Bu uygulama, OpenWeather API'sini kullanarak dünya genelindeki şehirlerin hava durumu bilgilerini görüntülemenizi sağlar. Şehir adı girerek hava durumu bilgilerine ulaşabilir ve ülke genelindeki hava durumu ortalamalarını görebilirsiniz.

## Özellikler

- Şehir bazında hava durumu bilgileri
- Ülke genelinde hava durumu ortalamaları
- Hava durumu simgeleri ve detayları
- Kullanıcı dostu arayüz

## Ara Yüz

### Arama Çubuğu

Kullanıcılar, şehir veya ülke adını arama çubuğuna girerek hava durumu bilgilerini hızlıca sorgulayabilirler.

![Arama Çubuğu Ekran Görüntüsü](https://github.com/user-attachments/assets/dac7ce38-a282-4b5d-98cd-4013e4d92fd2)

### Hava Durumu Sonuçları

Arama yapıldığında, hava durumu detayları, simgeler ve hava durumu bilgileri görüntülenir.

![Ekran görüntüsü 2024-08-15 122017](https://github.com/user-attachments/assets/b3b65783-0099-408b-8955-9c65a4902776)
![Ekran görüntüsü 2024-08-15 122311](https://github.com/user-attachments/assets/2334a685-91a4-41a1-80c9-e90ec12ae20f)

## API Anahtarı

Uygulamanın çalışabilmesi için OpenWeather API anahtarına ihtiyacınız var. Kendi API anahtarınızı almak için şu adımları takip edin:

1. [OpenWeather API Anahtarları Sayfasına](https://openweathermap.org/api_keys) gidin.
2. Kayıt olun veya giriş yapın.
3. API anahtarınızı oluşturun ve kopyalayın.
4. `index.js` dosyasındaki `apiKey` değişkenini kendi API anahtarınızla güncelleyin:
   ```javascript
   const apiKey = 'YOUR_API_KEY';
