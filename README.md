# 🫒 Midilli Zeytinyağı Galeri Sayfası

Bu proje, **Midilli Zeytinyağı ürünlerini** sergilemek için hazırlanmış **modern ve mobil uyumlu bir galeri sayfasıdır**.  
Her ürünün altında **WhatsApp ile sipariş** butonu bulunur.

---

## 🌐 Canlı Galeri

[Galeri Sayfası](https://midillizeytinyagii.github.io/Midilli-Zeytinyagi/galeri.html)

---

## ✨ Özellikler

- 🎨 Renkli ve modern tasarım  
- 📱 Mobil uyumlu, alt alta veya grid şeklinde ürün gösterimi  
- 💬 WhatsApp ile hızlı sipariş  
- 🖼 Responsive resimler (taşma veya kırpılma yok)  
- 🛠 Kolay ürün ekleme: `<div class="gallery-item">...</div>` kullanabilirsiniz  

---

## 🛠 Ürün Eklemek

```html
<div class="gallery-item">
  <img src="ÜRÜN_FOTO_URL" alt="ÜRÜN_ADI">
  <div class="product-title">ÜRÜN_ADI</div>
  <div class="product-price">₺FİYAT</div>
  <a href="https://wa.me/905XXXXXXXXX?text=Merhaba,%20ÜRÜN_ADI%20istiyorum" class="whatsapp-btn" target="_blank">WhatsApp’tan Sipariş</a>
</div>
