# Araç Defteri — kural dosyaları

Araç Defteri uygulamasının okuduğu mevzuat verileri. Uygulama açılışta
`index.json`'a bakar, elindekinden yüksek bir `rulesVersion` görürse ilgili
dosyayı indirir.

Buradaki tutarlar **resmi kaynaklardan** otomatik güncellenir; muayene
ücretleri [TÜVTÜRK fiyat listesinden](https://www.tuvturk.com.tr/arac-muayene-fiyat-listesi.aspx)
çekilir. Bilgiler yol göstericidir, bağlayıcı değildir — kesin tutar için
resmi kaynaklara başvurun.

## Yapı

- `index.json` — yayınlanan sürümlerin listesi
- `tr_vN.json` — kural dosyaları (en yüksek N geçerlidir)

Bu depo yalnızca veri içerir; uygulama kaynak kodu ayrı ve özeldir.
