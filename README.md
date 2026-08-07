# Hz. Sauna Sultan Dergâhı — GitHub Pages V5.3

Bu paket, **Sauna Sultan Manevi Değerleri Yaşatma ve Yardımlaşma Derneği**
internet sitesinin örnek içeriklerle zenginleştirilmiş GitHub Pages sürümüdür.
Bu sürüm, özel alan adı bağlanmadan doğrudan GitHub Pages adresinde çalışacak
şekilde hazırlanmıştır. Aktif yardım e-postası ve telefon/WhatsApp bağlantıları
siteye eklenmiştir.
Bu sürümde ana sayfa daha işlevsel hâle getirilmiş; 29 ziyaret noktasına ait
aranabilir Türbe Rehberi, hızlı işlem kartları, sabit WhatsApp bağlantısı,
faaliyet arşivi altyapısı, yeni marka işareti, sosyal paylaşım görseli ve
GitHub Pages teknik dosyaları eklenmiştir.
Gönüllülük bağlantıları, site içinde açılan ve başvuru bilgilerini kullanıcının
onayıyla hazır bir WhatsApp mesajına dönüştüren forma bağlanmıştır. Form,
GitHub Pages üzerinde herhangi bir kişisel veriyi kaydetmez.
Marka işareti, mevcut koyu yeşil ve altın renkler korunarak altın onikigen
içindeki “SS” monogramıyla yenilenmiştir.

## Paketteki dosyalar

- `index.html`: Ana site
- `kuran-rehberi.html`: Türkçe, İngilizce ve Almanca meal arama sayfası
- `quran-data.js`: Kur’an Rehberi veri seti
- `turbe-rehberi.html`: İsim, şehir ve kategori filtreli ziyaret rehberi
- `turbe-data.js`: 29 ziyaret noktasının adres ve açıklama verileri
- `kvkk.html`: Derneğe özel kişisel verilerin korunması ve aydınlatma metni
- `belgeler/sauna-sultan-dernek-tuzugu.pdf`: Şeffaflık bölümünden erişilen dernek tüzüğü
- `assets/`: Yapay zekâ ile üretilmiş temsili faaliyet görselleri
- `assets/turbeler/`: Rehberde kullanılan optimize edilmiş gerçek mekân fotoğrafları
- `assets/logo-mark.svg`: Altın onikigen içindeki SS monogramı, site logosu ve favicon
- `assets/social-preview.png`: WhatsApp ve sosyal medya paylaşım görseli
- `404.html`: Özel sayfa bulunamadı ekranı
- `robots.txt`, `site.webmanifest`: Arama motoru ve mobil web uygulaması dosyaları
- `GORSEL-PROMPTLARI.md`: Temsili görsellerin üretim notları ve promptları
- `TURBE-REHBERI-VERI-NOTU.md`: Rehber verilerinin yayın ve doğrulama notları
- `YAYIN-ONCESI-KONTROL-LISTESI.md`: Yayından önce yapılması gereken kontroller
- `ALAN-ADI-VE-EPOSTA-ONERILERI.md`: Alan adı ve kurumsal e-posta yapısı
- `EPOSTA-TAKMA-AD-KURULUMU.md`: Aynı gelen kutusuna yönlenen takma adreslerin kurulum rehberi
- `README.md`: Yükleme yönergesi

## GitHub'a yükleme

1. GitHub hesabınızda sağ üstteki **+** simgesine, ardından **New repository**
   seçeneğine tıklayın.
2. Repository name alanına `hz-sauna-sultan-dergahi` yazın.
3. **Public** seçeneğini seçip **Create repository** düğmesine tıklayın.
4. Açılan sayfada **uploading an existing file** bağlantısına tıklayın.
5. Bu ZIP dosyasını bilgisayarınızda açın. ZIP'in kendisini değil, içindeki
   **bütün dosya ve klasörleri** yükleme alanına sürükleyin. `assets` klasörünün
   klasör olarak yüklenmesi önemlidir.
6. Sayfanın altındaki **Commit changes** düğmesine tıklayın.

## GitHub Pages'i etkinleştirme

1. Repository içinde **Settings** bölümüne girin.
2. Sol menüden **Pages** seçeneğini açın.
3. **Build and deployment** bölümünde Source seçeneğini
   **Deploy from a branch** olarak ayarlayın.
4. Branch bölümünde `main`, klasör bölümünde `/(root)` seçin.
5. **Save** düğmesine tıklayın.
6. Yayının hazırlanması için birkaç dakika bekleyin.

Site adresiniz aşağıdaki biçimde olacaktır:

`https://KULLANICI-ADINIZ.github.io/hz-sauna-sultan-dergahi/`

Bu pakette `CNAME` dosyası yoktur. GitHub Pages ayarlarındaki **Custom domain**
alanını da boş bırakın. Böylece site GitHub uzantılı adresinde kalır.

## Önemli

- ZIP dosyasını repository'ye tek parça olarak yüklemeyin; önce bilgisayarınızda
  açıp içindeki dosyaları yükleyin.
- `index.html` mutlaka repository'nin ana dizininde bulunmalıdır.
- Eski yüklemede `CNAME` dosyası bulunuyorsa repository içinden silin.
- **Settings → Pages → Custom domain** alanında `hzsaunasultan.com` yazıyorsa
  kaldırıp kaydedin.
- `assets` klasörünü ve `quran-data.js` dosyasını atlamayın; aksi hâlde
  görseller veya Kur’an Rehberi çalışmaz.
- `turbe-data.js` dosyasını ve `assets/turbeler` klasörünü atlamayın; aksi
  hâlde Türbe Rehberi kartları ya da fotoğrafları görüntülenmez.
- Siteye `yardim@hzsaunasultan.com` adresi ve `+90 530 458 93 83`
  telefon/WhatsApp hattı eklenmiştir. Bu bilgiler değişirse `index.html`
  içindeki iletişim bağlantıları birlikte güncellenmelidir.
- Gönüllü formu gönderildiğinde bilgiler `+90 530 458 93 83` numarasına
  yönlendirilen hazır WhatsApp mesajına dönüştürülür; sitede veri saklanmaz.
- Açık adres, sosyal medya ve resmî banka/bağış bilgileri kesinleştiğinde
  ilgili “Yakında” alanları güncellenmelidir.
- Ana sayfadaki faaliyet sayıları örnek veridir; yayımdan önce doğrulanmış
  faaliyet kayıtlarıyla değiştirilmelidir.
- Galerideki görseller yapay zekâ ile üretilmiş temsili sahnelerdir ve site
  üzerinde bu şekilde etiketlenmiştir.
- Galeride kullanılan dosyalar `yardim-paketleme.webp`,
  `gonullu-koordinasyonu.webp` ve `egitim-destegi.webp` adlarıyla `assets`
  klasöründe bulunmalıdır.
- Türbe Rehberi adresleri ve ziyaret koşulları yayımdan önce doğrulanmalıdır.
- Türbe fotoğraflarının yayımlama hakları ve kaynak izinleri site yöneticisi
  tarafından kontrol edilmelidir.
- Kur’an Rehberi halka açık yayımlanmadan önce veri setindeki her meal için
  kullanım ve yeniden yayımlama izinleri kontrol edilmelidir.
- İhtiyaç sahiplerine ait fotoğraflar, açık rıza ve mahremiyet kontrolü
  yapılmadan yayımlanmamalıdır.
