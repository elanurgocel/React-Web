# Meram Belediyesi Tanıtım Sitesi

React ile geliştirilmiş, Konya Meram ilçesini ve belediye hizmetlerini tanıtan çok sayfalı bir web sitesi.

> **Not:** Bu proje, React öğrenme sürecinde hazırlanmış bir **öğrenci projesidir**. Meram Belediyesi'nin resmi web sitesi değildir ve belediyeyle herhangi bir bağlantısı yoktur.

## Özellikler

- **Çok sayfalı yapı:** Anasayfa, Hakkımızda, Hizmetlerimiz ve İletişim sayfaları
- **Sayfa yönlendirme:** React Router ile sayfa yenilenmeden geçiş
- **Otomatik fotoğraf slaytı:** Anasayfada belirli aralıklarla değişen görseller ve elle geçiş noktaları
- **Duyarlı menü:** Mobil ekranlarda açılır menüye dönüşen gezinme çubuğu
- **İletişim formu arayüzü:** İsim, e-posta, konu ve mesaj alanları içeren form tasarımı
- **Bileşen tabanlı mimari:** Navbar, Hero, Footer gibi tekrar kullanılabilir React bileşenleri

## Kullanılan Teknolojiler

- React 18
- React Router 6
- JavaScript (ES6+)
- CSS
- Font Awesome ikonları

## Proje Yapısı

```
src/
├── components/   # Navbar, Hero, Footer, Trip, Destination, ContactForm vb.
├── routes/       # Home, About, Service, Contact sayfaları
├── assets/       # Logo ve görseller
├── App.js        # Sayfa yönlendirmeleri
└── index.js      # Uygulamanın giriş noktası
```

## Çalıştırma

Bilgisayarınızda [Node.js](https://nodejs.org) kurulu olmalıdır.

```bash
# Bağımlılıkları yükleyin
npm install

# Geliştirme sunucusunu başlatın
npm start
```

Ardından tarayıcıda [http://localhost:3000](http://localhost:3000) adresini açın.

## Görseller

Sitede kullanılan fotoğraflar ve logo, tanıtım amacıyla Meram Belediyesi'nin herkese açık kaynaklarından alınmıştır. Tüm hakları sahiplerine aittir.
