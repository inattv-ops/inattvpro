# İnat TV PRO Güncel Durum: İnat BOX v16 APK İndirme ve Sürüm Rehberi

Bu repo “İnat TV PRO” adıyla arama yapan kullanıcıların eski ve güncel dosyaları birbirine karıştırmaması için açık bir sürüm rehberi sunar. Daha önce yer alan `inat-tv-pro-v21.apk` ve `inat-box-v15.apk` dosyaları güncel olmadıkları için kaldırılmıştır. Depoda indirilebilir durumda olan tek Android paketi **İnat BOX v16** dosyasıdır.

> **Önemli:** Bu sayfadaki dosya İnat TV PRO v21 değildir. APK’nın doğrulanmış uygulama adı **İnat BOX**, sürüm adı **16.0** ve paket kimliği `com.bp.box` değeridir.

## Güncel APK dosyasını indir

### [İnat BOX v16 APK indir](https://github.com/inattv-ops/inattvpro/raw/refs/heads/main/inat-box-v16.apk)

İndirme bağlantısı bu depodaki `inat-box-v16.apk` dosyasına doğrudan gider. Kullanıcıyı başka bir indirme alan adına veya reklam yönlendirme sayfasına göndermez.

## İnat TV PRO yerine hangi dosya sunuluyor?

| Konu | Güncel durum |
|---|---|
| Repo adı | `inattvpro` |
| Eski PRO dosyası | `inat-tv-pro-v21.apk` (kaldırıldı) |
| Eski BOX dosyası | `inat-box-v15.apk` (kaldırıldı) |
| Güncel dosya | `inat-box-v16.apk` |
| Gerçek uygulama adı | İnat BOX |
| Sürüm adı / kodu | 16.0 / 16 |
| Paket kimliği | `com.bp.box` |
| Minimum Android | Android 6.0 / API 23 |
| Dosya boyutu | 22.464.949 bayt (yaklaşık 21,42 MiB) |
| Yerel işlemci mimarileri | `arm64-v8a`, `armeabi-v7a`, `x86`, `x86_64` |
| SHA-256 | `B59D3E0925B498DF32EAE9288216BF6EFC2EB0C4A3A2CB63CAAC9211015A346E` |
| İmza sertifikası SHA-256 | `7CC771973665660F0653FCE2E9490E48B92BE8432A88D74F91703A716F6B4692` |

Repo adının `inattvpro` olması, içindeki dosyanın ürün adını veya sürümünü değiştirmez. Arama sonuçlarında yanlış yönlendirme oluşturmamak için güncel paket “İnat TV PRO v16” şeklinde adlandırılmamıştır.

## Eski İnat TV PRO v21 bağlantısı neden kaldırıldı?

Eski bir dosyayı “güncel” gibi sunmak hem kullanıcıların yanlış sürümü indirmesine hem de internette birbiriyle çelişen sürüm bilgilerinin yayılmasına neden olur. Bu depoda eski PRO v21 ve BOX v15 dosyaları tutulmamaktadır. Sayfadaki bağlantılar yalnızca mevcut v16 APK’yı gösterir.

Eski sayfalardan veya arama motoru önbelleğinden `inat-tv-pro-v21.apk` bağlantısına ulaşan kullanıcılar dosyanın artık bu repoda bulunmadığını bilmelidir. Başka bir sitenin aynı isimle sunduğu dosyanın bu proje tarafından yayımlanan eski dosyayla aynı olduğu varsayılamaz.

## İnat BOX v16 ile PRO v21 aynı uygulama mı?

Bu repo, iki paketin aynı uygulama veya birbirinin doğrudan güncellemesi olduğunu iddia etmez. Güncel v16 dosyasının paket kimliği `com.bp.box` olarak doğrulanmıştır; kaldırılan PRO v21 dosyasının mevcut repoda karşılaştırılabilir bir paketi bulunmadığından güncelleme, imza veya veri taşıma uyumluluğu hakkında kesin bir söz verilemez.

Cihazınızda daha önce “İnat TV PRO” adıyla kurulmuş bir uygulama varsa:

1. Mevcut uygulamanın paket ve sürüm bilgisini Android ayarlarından kontrol edin.
2. Yerel uygulama verilerinin kaldırma işleminde silinebileceğini unutmayın.
3. İnat BOX v16’yı kurarken Android’in gösterdiği uygulama adını inceleyin.
4. Sistem imza veya paket çakışması bildirirse mevcut uygulamayı hemen kaldırmak yerine önce verilerinizi değerlendirin.

## İnat BOX v16 dosyasının bütünlüğünü doğrulama

İndirdiğiniz APK’nın bu depodaki dosyayla aynı olduğunu kontrol etmek için SHA-256 hesaplayabilirsiniz.

### Windows

```powershell
Get-FileHash .\inat-box-v16.apk -Algorithm SHA256
```

### Linux

```bash
sha256sum inat-box-v16.apk
```

### macOS

```bash
shasum -a 256 inat-box-v16.apk
```

Beklenen SHA-256:

```text
B59D3E0925B498DF32EAE9288216BF6EFC2EB0C4A3A2CB63CAAC9211015A346E
```

Tek bir karakter bile farklıysa dosya bu repodaki kopyayla aynı değildir. Hash eşleşmesi dosyanın aktarım sırasında değişmediğini doğrular; dosyanın her koşulda güvenli olduğunu veya uygulamanın her cihazda çalışacağını garanti etmez.

Android SDK `apksigner` denetiminde JAR imzası (v1) ve APK Signature Scheme v2 doğrulaması başarılıdır. Paket tek imzalayıcı içerir; imza sertifikasının SHA-256 parmak izi yukarıdaki tabloda verilmiştir.

## Android telefon ve tablette kurulum

1. **İnat BOX v16 APK indir** bağlantısını kullanın.
2. İndirme tamamlandığında `inat-box-v16.apk` dosyasını açın.
3. Android isterse yalnızca kullandığınız tarayıcı veya dosya yöneticisi için uygulama yükleme izni verin.
4. Kurulum ekranında uygulama adını kontrol edin.
5. Kurulum tamamlandıktan sonra bilinmeyen uygulama yükleme iznini tekrar kapatın.

Android 6.0’dan eski cihazlar bu paketin tanımlı minimum sistem seviyesini karşılamaz. Daha yeni Android sürümlerinde güvenlik uyarılarının ve menü adlarının farklı görünmesi normaldir.

## Android TV ve TV Box kurulumu

İnat BOX v16 kaynak yapılandırmasında Android TV başlatıcı desteği bulunur ve dokunmatik ekran zorunlu değildir. APK’yı USB bellek, yerel dosya aktarımı veya cihazın desteklediği güvenilir bir indirme yöntemiyle TV kutusuna taşıyabilirsiniz.

Kurulumdan önce cihazın gerçekten Android TV veya Android tabanlı bir sistem kullandığını kontrol edin. Samsung Tizen, LG webOS ve diğer Android dışı televizyon sistemleri APK paketlerini doğrudan çalıştırmaz.

TV cihazında kurulum başarısız olursa:

- Android sürümünün 6.0 veya üzeri olduğunu kontrol edin.
- İndirme tamamlanmış mı diye dosya boyutuna bakın.
- Eski veya farklı imzalı bir `com.bp.box` paketi bulunup bulunmadığını inceleyin.
- Yeterli boş depolama alanı bırakın.
- Dosyayı yeniden indirip SHA-256 kontrolü yapın.

## Uygulama izinleri hakkında şeffaf bilgi

İnat BOX v16’nın birleşik APK manifestinde şu izin ve sistem bildirimleri tanımlıdır:

- İnternete erişim
- Ağ ve Wi-Fi bağlantısı durumunu okuma
- Cihaz açılışının tamamlandığını algılama
- Bildirim gönderme
- Titreşim kullanma
- Cihazı uyanık tutma ve ön plan hizmeti
- Firebase mesajlarını alma
- Paket kurulum isteğinde bulunma
- Reklam kimliği ve Privacy Sandbox reklam hizmetleri
- Install Referrer hizmetine bağlanma
- Uygulamaya özel dinamik alıcı koruması

Bir iznin manifestte tanımlı olması, her Android sürümünde otomatik olarak verildiği anlamına gelmez. Android bazı izinleri ayrıca kullanıcıya sorar veya sistem ayarlarından yönetir.

Projede Firebase Analytics, Firebase Crashlytics ve Firebase Cloud Messaging bileşenlerinin yanı sıra Unity Ads ve Start.io reklam SDK’ları bulunur. Dolayısıyla uygulama hakkında “reklamsızdır” veya “hiç teknik veri işlemez” biçiminde kesin ve doğrulanmamış bir vaat verilmez.

## Sürüm ve dosya karşılaştırması nasıl yapılır?

Benzer adlara sahip iki APK’yı karşılaştırırken şu sırayı kullanabilirsiniz:

1. **Dosya adı:** İlk ipucudur, fakat tek başına yeterli değildir.
2. **Uygulama etiketi:** Kurulum ekranında görünen adı kontrol edin.
3. **Paket kimliği:** Android’in uygulamayı hangi kimlikle tanıdığını gösterir.
4. **Sürüm adı ve kodu:** Güncelleme sırasını anlamaya yardımcı olur.
5. **Dosya boyutu:** Eksik veya farklı indirmeyi fark ettirebilir.
6. **SHA-256:** Dosyaların bayt düzeyinde aynı olup olmadığını gösterir.
7. **İmza:** Aynı paket kimliğine sahip güncellemelerde Android imza uyumluluğu arar.

Bu depoda verilen bilgiler ilk altı alanı açıkça belgelemektedir. İmza uyumluluğu konusunda eski PRO paketiyle karşılaştırma iddiası yapılmaz.

## Güncel resmî adresler

- Web: [https://inatvapp.com/](https://inatvapp.com/)
- GitHub: [https://github.com/inattv-ops](https://github.com/inattv-ops)
- X: [https://x.com/inattvapk](https://x.com/inattvapk)
- E-posta: **inattvapk@gmail.com**

Eski `inattv.rest` alan adı ve eski GitHub organizasyon bağlantıları güncel yönlendirme olarak kullanılmamaktadır.

## Sık sorulan sorular

### İnat TV PRO v21’i bu repodan indirebilir miyim?

Hayır. `inat-tv-pro-v21.apk` güncel olmadığı için kaldırılmıştır. Depodaki tek APK `inat-box-v16.apk` dosyasıdır.

### İnat BOX v16, İnat TV PRO’nun otomatik güncellemesi midir?

Bu yönde bir garanti verilmez. Güncel İnat BOX paketinin kimliği `com.bp.box` olarak doğrulanmıştır; eski PRO paketinin imza ve paket uyumluluğu bu sayfada doğrulanmamaktadır.

### İnat BOX v16’nın gerçek sürümü nedir?

Kaynak yapılandırmaya göre sürüm adı 16.0, sürüm kodu 16’dır.

### Hangi Android sürümü gerekir?

Minimum Android seviyesi API 23, yani Android 6.0’dır.

### “Virüs yok” garantisi veriliyor mu?

Hayır. İncelenmeden mutlak güvenlik iddiasında bulunmak doğru değildir. SHA-256 değeri yalnızca indirilen dosyanın yayımlanan dosyayla aynı olduğunu kontrol eder.

### APK iOS cihazlarda çalışır mı?

Hayır. APK biçimi Android içindir ve iPhone/iPad üzerine kurulamaz.

## Yasal kullanım ve üçüncü taraf hakları

Uygulamanın kullanımı sırasında bulunduğunuz bölgedeki yasalara, kullanılan hizmetlerin koşullarına ve içerik sahiplerinin haklarına uymalısınız. Bu depo, üçüncü taraf yayınlar, platformlar veya markalar üzerinde sahiplik ya da resmî ortaklık iddiasında bulunmaz.

## Sonuç

İnat TV PRO aramasıyla bu sayfaya geldiyseniz mevcut durumu kısa biçimde şöyle özetleyebiliriz: eski PRO v21 dosyası kaldırılmıştır; güncel indirilebilir paket İnat BOX 16.0’dır. Dosyayı yalnızca resmî repo bağlantısından indirin ve kurmadan önce SHA-256 değerini kontrol edin.

### [İnat BOX v16 APK dosyasını indir](https://github.com/inattv-ops/inattvpro/raw/refs/heads/main/inat-box-v16.apk)

---

**Uygulama:** İnat BOX · **Sürüm:** 16.0 · **Minimum Android:** 6.0 · **Dosya:** `inat-box-v16.apk`
