# Tank Savaşı

Tarayıcıda oynanan, yukarıdan bakışlı, dalga tabanlı bir tank oyunu. Kurulum gerektirmez; tek bir `index.html` dosyasından oluşur.

## Oynanış

- Dalgalar halinde gelen düşman tanklarını yok et, her dalga bir öncekinden zorlu.
- Beton duvarlar yıkılmaz; ahşap kutular vurularak yıkılabilir.
- Düşmanlardan ve kutulardan güçlendirmeler düşer:
  - **Yeşil kutu:** zırh onarımı
  - **Mavi kutu:** 10 saniyelik üçlü atış
- Düşman türleri: standart (kırmızı), hızlı (turuncu), ağır çift namlulu (bordo).
- Dalga temizlenince 3 güçlendirmeden birini seç: motor, zırh, namlu, atış hızı, taret. Her biri 4 kez yükseltilebilir.
- Üç tank var: **Standart** (dengeli), **Hafif** (hızlı, zırhı ince), **Ağır** (yavaş, çok zırhlı, güçlü top).
- Üç harita var: **Çöl Vadisi**, **Şehir Harabesi**, **Orman Açıklığı**.
- En iyi skor tarayıcıda saklanır.

## Kontroller

| | Klavye + fare | Dokunmatik |
|---|---|---|
| Sürüş | `W` `A` `S` `D` / ok tuşları | Sol başparmak |
| Nişan | Fare | Sağ başparmağı sürükle (sürüklemezsen en yakın düşmana kilitlenir) |
| Ateş | Sol tık / `Boşluk` | Sağ başparmağı basılı tut |
| Duraklat | `P` / `Esc` | Sağ üstteki düğme |

## Çalıştırma

`index.html` dosyasını bir tarayıcıda aç ya da GitHub Pages üzerinden oyna.
