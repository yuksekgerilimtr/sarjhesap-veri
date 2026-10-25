# ŞarjHesap fiyat verisi

ŞarjHesap uygulamasının okuduğu güncel fiyatlar: `prices.json`.

- **updated:** son güncelleme tarihi (YYYY-AA-GG). Uygulama yalnızca elindekinden daha yeni tarihli dosyayı alır.
- **fuel:** İstanbul pompa fiyatları (TL/litre)
- **homeElectricity:** ev elektriği, üst kademe, vergiler dahil (TL/kWh)
- **operators:** şarj firmaları. `ac` ve `dc` listeleri TL/kWh. Tek değer sabit fiyat, iki değer fiyat aralığıdır. Boş liste o şarj türünün olmadığını gösterir.

Fiyatlar firmaların yayımladığı tarifelerden derlenir, bilgi amaçlıdır.
Kaynak: [Yüksek Gerilim](https://yuksekgerilim.com)
