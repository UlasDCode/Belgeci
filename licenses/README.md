# Üçüncü taraf lisansları

`kira-sozlesmesi.html` dosyası, oluşturulan belgenin (ve PDF'in) her cihazda aynı görünmesi için iki yazı tipini **gömülü** olarak (base64 WOFF2) içerir. Her iki yazı tipi de [SIL Open Font License 1.1](https://openfontlicense.org) ile dağıtılır.

| Uygulamadaki adı | Kaynak yazı tipi | Telif | Lisans metni | Kullanıldığı yer |
|---|---|---|---|---|
| `Arimo` | [Arimo](https://github.com/googlefonts/arimo) | Copyright The Arimo Project Authors | [Arimo-OFL.txt](Arimo-OFL.txt) | Sözleşmenin 1, 2, 3 ve 5. sayfaları |
| `BelgeEkYazi` | [Carlito](https://github.com/googlefonts/carlito) | Copyright 2013 The Carlito Project Authors | [Carlito-OFL.txt](Carlito-OFL.txt) | 4. sayfa (demirbaş listesi) |

## Yapılan değişiklikler

- **Alt küme (subset):** Dosya boyutunu küçük tutmak için iki yazı tipinden de yalnızca gereken karakterler alındı: Temel Latin, Latin-1, Türkçe harfler (`ğ Ğ ş Ş ı İ`) ve bazı noktalama işaretleri (`– — ‘ ’ “ ” … •` ve `₺`).
- **Yeniden adlandırma:** Carlito'nun lisansında *Reserved Font Name* ("Carlito") maddesi vardır. Bu madde, değiştirilmiş sürümlerin bu adı kullanmasını yasaklar. Alt küme bir değişiklik sayıldığı için yazı tipinin aile adı `BelgeEkYazi` olarak değiştirildi. Telif ve lisans bilgileri yazı tipinin içinde özgün hâliyle korunmuştur.
- Arimo'nun lisansında *Reserved Font Name* maddesi yoktur; özgün adıyla kullanılmıştır.

Arayüzde kullanılan **Manrope** yazı tipi gömülü değildir; çalışma anında Google Fonts üzerinden yüklenir (SIL OFL 1.1). İnternet yoksa sistem yazı tipi kullanılır, belge çıktısı etkilenmez.
