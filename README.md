
# Midilli Zeytinyağı Galeri Sayfası

Bu proje, **Midilli Zeytinyağı ürünlerini sergilemek için** hazırlanmış basit ve mobil uyumlu bir galeri sayfasıdır.  
Sayfa tamamen **responsive** (mobil, tablet ve desktop uyumlu) ve ürünlerin altına **WhatsApp üzerinden sipariş** verme imkanı sağlar.

## Özellikler

- Mobil uyumlu, alt alta veya grid şeklinde ürün gösterimi
- Her ürün için başlık, fiyat ve WhatsApp sipariş butonu
- Taşmayı önleyen responsive resimler
- Kolay ürün ekleme: sadece HTML içine `<div class="gallery-item">...</div>` eklemek yeterli
- Eski CSS veya slider ile çakışmaz

## Kullanım

1. Bu projeyi GitHub Pages üzerinde çalıştırabilirsiniz.
2. `galeri.html` dosyasını tarayıcıda açarak galeriyi görüntüleyebilirsiniz.
3. Ürün eklemek için `<section class="gallery">` içine yeni ürün kartları ekleyin:

```html
<div class="gallery-item">
  <img src="ÜRÜN_FOTO_URL" alt="ÜRÜN_ADI">
  <div class="product-title">ÜRÜN_ADI</div>
  <div class="product-price">₺FİYAT</div>
  <a href="https://wa.me/905XXXXXXXXX?text=Merhaba,%20ÜRÜN_ADI%20istiyorum" class="whatsapp-btn" target="_blank">WhatsApp’tan Sipariş</a>
</div>
