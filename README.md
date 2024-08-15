# Hava Durumu Uygulaması

Bu proje, OpenWeather API kullanarak dünya genelindeki şehirlerin ve ülkelerin hava durumunu hızlı ve verimli bir şekilde sorgulamanızı sağlayan bir hava durumu uygulamasıdır. Kullanıcı dostu arayüzü sayesinde, herhangi bir şehir veya ülke adını aratarak, anlık hava durumu bilgilerine ve ülke bazında hava durumu ortalamalarına ulaşabilirsiniz.

## Özellikler

- **Şehir Hava Durumu:** Şehir adı girerek anlık hava durumu, sıcaklık, nem oranı ve hava durumu açıklamalarını görüntüleyin.
- **Ülke Ortalama Hava Durumu:** Belirli bir ülkenin genel hava durumu ortalamalarını öğrenin.
- **Kullanıcı Dostu Arayüz:** Kolay kullanımlı arama çubuğu ve net görsel düzen.
- **Hızlı ve Güvenilir:** OpenWeather API aracılığıyla hızlı veri çekimi ve güncelleme.

## Teknolojiler

- **HTML:** Sayfa yapısı ve içerik düzenlemesi için kullanılmıştır.
- **CSS:** Stil ve düzenleme işlemleri için kullanılmıştır.
- **JavaScript:** API'dan veri çekme ve kullanıcı arayüzünü dinamik olarak güncelleme işlemleri için kullanılmıştır.
- **OpenWeather API:** Hava durumu verilerini sağlamak için kullanılan API.

## Kullanım

1. **API Anahtarını Alın:**
   [OpenWeather](https://openweathermap.org/api_keys) web sitesine gidin ve bir API anahtarı alın. API anahtarınızı almak için siteye kaydolmanız gerekebilir. 

2. **API Anahtarınızı Yapılandırın:**
   `index.js` dosyasındaki `apiKey` değişkenini kendi API anahtarınızla güncelleyin:
   ```javascript
   const apiKey = 'YOUR_API_KEY';
