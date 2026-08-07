# Alan Adı ve Kurumsal E-posta Yapısı

## Kullanılan marka ve alan adı

- **Sitede görünen kısa marka:** Hz. Sauna Sultan Dergâhı
- **Kurumsal kısa ad:** Sauna Sultan
- **Resmî unvan:** Sauna Sultan Manevi Değerleri Yaşatma ve Yardımlaşma Derneği
- **Alan adı:** `saunasultan.com`
- **Kısa ifade:** Maneviyat · Merhamet · Dayanışma

## Aktif ana posta kutusu

- `yardim@saunasultan.com` — yardım, gönüllülük ve genel iletişim

İlk aşamada tek bir gerçek posta kutusunun kullanılması yeterlidir. Aşağıdaki
adresler ayrı posta kutusu yerine ana posta kutusuna yönlenen takma adres
(alias/forwarder) olarak oluşturulabilir:

- `iletisim@saunasultan.com` → `yardim@saunasultan.com`
- `gonullu@saunasultan.com` → `yardim@saunasultan.com`
- `bilgi@saunasultan.com` → `yardim@saunasultan.com`

İleride ihtiyaç oluşursa `yonetim@saunasultan.com`,
`basin@saunasultan.com` ve `kvkk@saunasultan.com` adresleri eklenebilir.

## Önemli fark: alma ve gönderme

Bir yönlendirme veya takma adres, o adrese gelen iletilerin
`yardim@saunasultan.com` gelen kutusuna ulaşmasını sağlar. Ancak bu adres
adına e-posta göndermek için sağlayıcınızın **“Farklı gönder / Send as”**,
**gönderici kimliği** veya SMTP takma adresi özelliğini ayrıca etkinleştirmeniz
gerekebilir. Bu özellik kurulmazsa yanıtlar `yardim@saunasultan.com`
adresinden gider.
