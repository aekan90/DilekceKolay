# DilekceKolay

DilekceKolay.sln                # Ana solution dosyası
│
├── DilekceKolay.Web            # Sunum katmanı (Web Uygulaması)
│
├── DilekceKolay.Business       # İş mantığı katmanı
│
├── DilekceKolay.Data           # Veri erişim katmanı
│
├── DilekceKolay.Core           # Ortak kodlar ve yardımcı sınıflar
│
├── DilekceKolay.API            # API katmanı (Opsiyonel)
│
└── DilekceKolay.Tests          # Test katmanı



**DilekceKolay**, Türkiye'deki kullanıcılar için trafik cezası ve diğer hukuki dilekçeleri hızlı, kolay ve anlaşılır bir şekilde hazırlamanızı sağlayan bir platformdur. Bu uygulama, kullanıcıların çeşitli hukuki işlemlerini pratik bir şekilde çözmelerine yardımcı olmayı amaçlamaktadır.

## Proje Özeti

DilekceKolay, hukuki işlemleri karmaşık ve zaman alıcı olmaktan çıkararak, kullanıcıların sadece temel bilgileri girerek, otomatik olarak oluşturulan dilekçe şablonlarıyla hızlıca başvuruda bulunmalarını sağlar. Uygulama, kullanıcıların deneyimini her aşamada basit ve erişilebilir tutar.

**Özellikler:**
- Trafik cezalarına itiraz dilekçeleri oluşturma.
- Farklı hukuki dilekçe türleri için şablonlar.
- Kullanıcı dostu arayüz ile hızlı ve etkili işlem yapabilme.
- Hem şahıs hem de araç sahipleri için dilekçe hazırlama.
- Gelecekte farklı hukuki işlemler için genişletilebilir yapı.

## Katman Yapısı

Bu proje, **Clean Architecture** ve **Layered Architecture** prensipleri doğrultusunda katmanlara ayrılmıştır:
- **Web Katmanı**: Kullanıcıların arayüzle etkileşime girdiği alan.
- **Business Katmanı**: Uygulamanın iş mantığının bulunduğu katman.
- **Data Katmanı**: Veritabanı işlemlerinin yapıldığı katman.
- **Core Katmanı**: Paylaşılan ve ortak kullanılan bileşenler.
- **API Katmanı**: (Opsiyonel) Mobil veya üçüncü taraf entegrasyonları için API servisi.
- **Tests Katmanı**: Birim ve entegrasyon testlerinin bulunduğu katman.

## Kurulum

Projeyi lokalinizde çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

1. **Git** ile projeyi klonlayın:
   ```bash
   git clone https://github.com/kullaniciadi/DilekceKolay.git
