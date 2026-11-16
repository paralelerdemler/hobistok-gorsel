# hobistok-gorsel

Hobistok ürün görsellerinin herkese açık barındırma deposu.

ikas ve Trendyol ürün görselini yalnızca **adres** ile kabul ediyor, dosya yükleme uçları yok.
Bu depo o adresleri sağlar. İki kanal da görseli indirip kendi CDN'ine kopyalar
(`cdn.myikas.com`, `cdn.dsmcdn.com`), yani yayına alındıktan sonra bu depo yalnızca kaynak kalır.

## rafya/
Rafya İp 40 rengi. Her renk için:

- `R<kod>-1-bobin.jpg` — bobin, beyaz zemin (1400x1400)
- `R<kod>-2-canta.jpg` — çantalı kolaj (1400x1400)
- `KATALOG-1.jpg`, `KATALOG-2.jpg` — 40 renklik kartela (1400x1400)
