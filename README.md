Bu web sitesi Nextjs üzerine inşa edilmiştir. Her sayfa içeriği farklı
platformlardan beslenerek güncelliğini korumaktdır.
Performans konusu öncelikli olduğu için next'in statik sayfa üretme özelliği
kullanılmıştır. Ziyaretçi sayfaya erişmek istediğinde, daha önceden statik
olarak üretilmiş dosyaya kendisine en yakın bölgedeki CDN'den çeker ve
görüntüler (powered by vercel).

## Kullanmak için

1. `.env.example` dosyasının adını `.env` olarak değiştirin.

> Burada beklenilen tüm değerleri karşılamaz zorundasınız.

2. Bağımlılıkları yükleyin ve çalıştırın

```bash
yarn
```

```bash
yarn dev
```

3. Tarayıcınızdan [http://localhost:3000](http://localhost:3000)'e girin

## İçerikler ve Bağımlılıklar

### Ekipman & Uygulama

Bu sayfanın içerikleri Airtable hesabımdan geliyor.

### Yer İmi

İçerikler Raindrop hesabımdan geliyor.
