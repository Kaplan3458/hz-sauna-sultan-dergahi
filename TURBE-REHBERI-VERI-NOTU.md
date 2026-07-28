# Türbe Rehberi Veri ve Yayın Notu

## Kapsam

Rehber, kullanıcı tarafından sağlanan `turbe-rehberi-main.zip` projesindeki
29 ziyaret noktasını kullanır. Kaynak projedeki adlar, adresler, ziyaret
notları ve İstanbul kayıtlarına ait toplu taşıma bağlantısı mantığı korunmuştur.

Rehber iki grupta sunulur:

- 1–14 numaralı kayıtlar: Uşşâkî–Nâzenî Silsilesi
- 15–29 numaralı kayıtlar: Anadolu Gönül Sultanları

## Yayından önce doğrulanması gerekenler

- Türbe veya ziyaret noktasının güncel açık adresi
- Google Haritalar hedefinin doğru giriş kapısına yönlendirmesi
- Mezarlık kapısı, yol ayrımı veya yürüme mesafesine ilişkin özel notlar
- Ziyarete açık gün ve saatler
- Tadilat, taşınma veya geçici kapanma bilgileri
- Fotoğrafların yayımlama hakkı ve gerektiğinde kaynak/izin bilgisi
- Kişi adlarının imlası ve kullanılan unvanlar

Adres ve ziyaret şartları zaman içinde değişebileceğinden sayfada bilgilendirme
notu gösterilmektedir. Güncelleme yapılırken hem `turbe-data.js` verisi hem de
ilgili `assets/turbeler` fotoğrafı birlikte kontrol edilmelidir.

## Teknik yapı

- Fotoğraflar `assets/turbeler/1.webp`–`29.webp` adlarıyla saklanır.
- Veriler `turbe-data.js` dosyasında bulunur.
- Rehber araması isim, açık adres, şehir ve ilçe metinlerinde çalışır.
- Google Haritalar bağlantıları adres metninden dinamik olarak oluşturulur.
- Herhangi bir ücretli harita servisi veya API anahtarı kullanılmaz.
