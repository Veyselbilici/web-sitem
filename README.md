# Web Sitem

Veysel Bilici'nin kişisel sitesi. İsim ve alan adı henüz kesinleşmedi, "Web Sitem" geçici addır.

## İçerik

- `index.html`: Tek dosyalık site (HTML, CSS ve JavaScript bir arada). Türkçe ve İngilizce.
- `assets/`: Uygulama ikonları, mağaza ekran görüntüleri ve tanıtım videoları.

## Yerelde açmak

Bir klasörden basit bir sunucu başlatıp tarayıcıda açın:

```bash
python3 -m http.server 8080
# http://localhost:8080
```

## Sayfalar

- `/` ana sayfa: giriş, ürünler, mühendislik, süreç, ekranlar, iletişim
- `#hakkimda`: hakkımda, deneyim, eğitim
- `#camella`, `#tadfit`, `#periyodoz`, `#zartzurt`, `#falio`: uygulama detayları

## Notlar

- Hakkımda sayfasındaki "Kod aktivitesi" ve "Teknoloji dağılımı" grafikleri örnek veriyle çalışıyor ("temsili" etiketli). Yayından önce gerçek verilerle değiştirilmeli. İlgili veriler `index.html` içinde `MIX` sabitinde ve `renderDash` fonksiyonunda.
- Ctrl+K / ⌘K hızlı menüyü açar.
- Henüz yayında değil.
