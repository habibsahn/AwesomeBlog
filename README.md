# Awesome Blog

Awesome Blog, modern ve temiz bir blog sitesi arayüzü sunan statik bir web projesidir. Ana sayfa, blog listesi ve iletişim sayfası gibi temel bölümlerden oluşur. Proje, Bootstrap tabanlı tasarım ile geliştirilmiş olup sade ve mobil uyumlu bir görünüm sunar.

## Özellikler

- Ana sayfa / giriş ekranı
- Blog listeleme sayfası
- İletişim formu ve harita bölümü
- Mobil uyumlu responsive tasarım
- Bootstrap 5 kullanımı
- Font Awesome ikonları
- Statik HTML ve CSS yapısı

## Proje Yapısı

```text
AwesomeBlog/
├── index.html        # Ana sayfa
├── blogs.html        # Blog listesi sayfası
├── contact.html      # İletişim sayfası
├── style.css         # Özel stiller
├── img/              # Görseller
├── README.md         # Proje açıklaması
└── .gitignore        # İsteğe bağlı git ayarları (varsa)
```

## Kullanılan Teknolojiler

- HTML5
- CSS3
- Bootstrap 5.1.3
- Font Awesome 6
- Google Maps Embed

## Çalıştırma

Projeyi yerelde çalıştırmak için iki yöntemden birini kullanabilirsiniz:

### 1) Doğrudan açma

- `index.html` dosyasını tarayıcıda açın.

### 2) Yerel sunucu ile çalıştırma

Terminalde proje klasörüne geçip şu komutu çalıştırın:

```bash
python3 -m http.server 8000
```

Ardından tarayıcıda aşağıdaki adrese gidin:

```text
http://localhost:8000
```

## Sayfalar

### Ana Sayfa
- Blog sitesinin tanıtım ve içerik önizleme bölümünü gösterir.
- Üst menü, çağrı butonları ve görsel kart düzeni içerir.

### Bloglar
- Farklı içerik kategorilerini listeleyen bir düzen sunar.
- Klasik blog kartları ve sayfalama bileşeni bulunur.

### İletişim
- Kullanıcıların iletişim kurabilmesi için form içerir.
- Harita yerleşimi ile konum bilgisi gösterilir.

## Geliştirme Notları

Bu proje statik bir tasarım örneğidir. Daha sonraki aşamada aşağıdaki özellikler eklenebilir:

- Dinamik blog içerikleri
- Veritabanı bağlantısı
- Yorum sistemi
- Admin paneli
- Arama ve filtreleme
- SEO iyileştirmeleri

## Lisans

Bu proje için özel bir lisans belirtilmemiştir. Kendi kullanımınıza göre düzenleyebilirsiniz.

## Katkı

Geliştirme süreçlerine katkıda bulunmak isterseniz, dosyaları düzenleyip pull request açabilirsiniz.
