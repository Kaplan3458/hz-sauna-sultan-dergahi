# Aynı Gelen Kutusuna Yönlenen E-posta Takma Adları

## Hedef yapı

Ana posta kutusu:

- `yardim@saunasultan.com`

Bu adrese yönlenecek takma adresler:

- `iletisim@saunasultan.com`
- `gonullu@saunasultan.com`
- `bilgi@saunasultan.com`

## Genel kurulum adımları

1. Alan adını veya kurumsal e-postayı aldığınız firmanın yönetim paneline
   giriş yapın.
2. **E-posta**, **E-posta hesapları**, **Aliases / Takma adlar**,
   **Forwarders / Yönlendiriciler** veya **Email Routing** başlıklı bölümü açın.
3. Yeni bir takma adres ya da yönlendirici oluşturun.
4. Kaynak adres olarak önce `iletisim@saunasultan.com`, hedef adres olarak
   `yardim@saunasultan.com` girin ve kaydedin.
5. Aynı işlemi `gonullu@saunasultan.com` ve
   `bilgi@saunasultan.com` için tekrarlayın.
6. Haricî bir Gmail veya Outlook hesabından üç adrese de ayrı ayrı test
   iletisi gönderin.
7. Üç iletinin de `yardim@saunasultan.com` gelen kutusuna ulaştığını
   doğrulayın.

Takma adres desteği varsa bu yapı için üç ayrı ücretli posta kutusu satın
almanız genellikle gerekmez.

## Takma adres adına yanıt vermek

Yönlendirme yalnızca gelen postayı aynı kutuya taşır. Yanıtların
`iletisim@`, `gonullu@` veya `bilgi@` adresinden görünmesini istiyorsanız
sağlayıcı panelinde **Farklı gönder / Send as**, **gönderici kimliği** veya
SMTP takma adresi özelliğini de kurun. Bu özellik yoksa yanıt
`yardim@saunasultan.com` adresinden gider.

## Güvenlik notları

- İstemeden çok fazla spam almamak için **catch-all / tümünü yakala**
  seçeneğini açmayın.
- Yönlendirme sonrası test iletisini ve mümkünse SPF, DKIM ve DMARC
  doğrulamalarını kontrol edin.
- Panelde parola, doğrulama kodu veya kurtarma anahtarı ekran görüntüsü
  paylaşmayın.

Menü adları sağlayıcıya göre değişir. E-postayı aldığınız firmanın adını
(ör. cPanel, Hostinger, Google Workspace, Zoho, Titan veya Microsoft 365)
belirtirseniz tam tıklama yolunu ayrıca hazırlayabiliriz.
