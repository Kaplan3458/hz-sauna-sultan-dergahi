# Alan Adı ve Kurumsal E-posta Yapısı

## Kullanılan marka ve alan adı

- **Sitede görünen kısa marka:** Hz. Sauna Sultan Dergâhı
- **Kurumsal kısa ad:** Sauna Sultan
- **Resmî unvan:** Sauna Sultan Manevi Değerleri Yaşatma ve Yardımlaşma Derneği
- **Alan adı:** `hzsaunasultan.com`
- **Kısa ifade:** Maneviyat · Merhamet · Dayanışma

## Aktif ana posta kutusu

- `yardim@hzsaunasultan.com` — yardım, gönüllülük ve genel iletişim

İlk aşamada tek bir gerçek posta kutusunun kullanılması yeterlidir. Aşağıdaki
adresler ayrı posta kutusu yerine ana posta kutusuna yönlenen takma adres
(alias/forwarder) olarak oluşturulabilir:

- `iletisim@hzsaunasultan.com` → `yardim@hzsaunasultan.com`
- `gonullu@hzsaunasultan.com` → `yardim@hzsaunasultan.com`
- `bilgi@hzsaunasultan.com` → `yardim@hzsaunasultan.com`

İleride ihtiyaç oluşursa `yonetim@hzsaunasultan.com`,
`basin@hzsaunasultan.com` ve `kvkk@hzsaunasultan.com` adresleri eklenebilir.

## Önemli fark: alma ve gönderme

Bir yönlendirme veya takma adres, o adrese gelen iletilerin
`yardim@hzsaunasultan.com` gelen kutusuna ulaşmasını sağlar. Ancak bu adres
adına e-posta göndermek için sağlayıcınızın **“Farklı gönder / Send as”**,
**gönderici kimliği** veya SMTP takma adresi özelliğini ayrıca etkinleştirmeniz
gerekebilir. Bu özellik kurulmazsa yanıtlar `yardim@hzsaunasultan.com`
adresinden gider.
