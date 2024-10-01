# 🦓 Zebra Geçidi: kullanımı kolay bir dijital güvenlik kontrol listesi

## 🎯 Buradan başlayın!

### 🤔 Bu kılavuzu okuyun eğer:

- İnterneti günlük olarak kullanıyorsanız — iş, sosyal medya ve finansal işlemler için.
- Dijital güvenliğinizi ve gizliliğinizi proaktif bir şekilde korumak istiyorsanız, ancak acil bir tehlike altında değilseniz. (Eğer acil bir tehlikedeyseniz, topluluğumuzdan biriyle birebir danışmanlık için iletişime geçin.)
- Teknolojiyle rahat hissediyorsanız — bilgisayar veya akıllı telefonunuzun ayarlarını değiştirme konusunda kendinize güveniyorsanız.

### 🗺 Bu kılavuz nereden alınmıştır

- Bu kılavuz, bireylerin ve grupların dijital güvenlik uygulamalarını geliştirmelerine yardımcı olan çalışmalarımızdan ve Amerika Birleşik Devletleri, Kanada ve Hong Kong'da yaşama ve çalışma deneyimlerimizden yararlanılarak hazırlanmıştır.
- Mümkün olan her yerde, teknik olarak sofistike ancak kullanımı zor olanlar yerine erişilebilir ve kullanımı kolay olan uygulamaları ve araçları seçtik. Kararımız, insanların stresli durumlarda daha beceriksiz hale geldiği gözlemimize dayanmaktadır, bu nedenle prosedürleri olabildiğince basit tutmak önemlidir.

### 🌱 Bu kılavuz nasıl kullanılır?

- **Seviye 1'den başlayın ve yukarı doğru ilerleyin!** Öneriler artan zorluk seviyelerine göre sıralanmıştır.
- **Seviye 1 hızlı temeller bölümüdür.** Yaklaşık 1 saat içinde halledebilirsiniz  ve muhtemelen buradaki önerilerin çoğuna zaten aşinasınızdır - ancak iki kez kontrol etmekten asla zarar gelmez.
- **Seviye 2, cihaz/uygulama ayarlarınızı daha derinlemesine inceler ve çevrimiçi gizliliğinize ince ayar yapmanıza yardımcı olur.** Bu bölüm, sık kullandığınız hesap ve cihaz sayısına bağlı olarak 1-2 saat sürecektir.
- **En azından Seviye 1 ve 2'deki her şeyi yapın.** Bu sizi en yaygın kullanılan saldırılardan korurken, paylaştığınız kişisel bilgi miktarını önemli ölçüde azaltacaktır.
- **Seviye 3, dijital güvenlik uygulamalarınızdaki yarım kalmış işleri tamamlar**, ancak tamamlanması daha fazla zaman ve para gerektirir. Gerekli dijital temizlik miktarına bağlı olarak, bu bölüm 1-4 saat arasında sürebilir.
- **Seviye 3'ten sonra paylaşılan senaryolar daha yüksek riskli durumlar içindir.** Bunlardan herhangi birinin sizin için geçerli olup olmadığını görmek için bunları tarayın. (Riskler daha yüksek olduğu için, Seviye 1-3'teki her şeyi yaptığınızı varsayarlar).
- **Bu kılavuz yaşayan bir belgedir.** Lütfen bir pull request göndermekten veya bu kılavuzun [GitHub'daki] sürümünü forklamaktan çekinmeyin (https://github.com/narwhalacademy/zebra-crossing).

### 🗣 Bu kılavuzu diğer dillerde okuyun

- [繁體中文 (Geleneksel Çince)](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-繁體中文.md)
- [Deutsch (Almanca)](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-Deutsch.md)
- [日本語](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-日本語.md) (Japonca, çalışma devam ediyor)
- [Italiano](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-Italiano.md) (İtalyanca, çalışma devam ediyor)
- Başka bir dile katkıda bulunmak mı istiyorsunuz? İşbirliği yapmak için [bize bir mesaj gönderin](mailto:contact@narwhalacademy.org).

### ☕️ Bu kılavuzu destekleyin

- [Bize sanal bir kahve alın](https://ko-fi.com/narwhalacademy)
- Bu kılavuzu arkadaşlarınızla ve topluluğunuzla paylaşın!
- [Geri bildiriminizi gönderin](mailto:contact@narwhalacademy.org) veya [GitHub'da rehbere katkıda bulunun](https://github.com/narwhalacademy/zebra-crossing).

### 🕒 Son güncelleme

- 30 Nisan 2024

---

## 🧐 Öğrenmek için faydalı terimler

### 🎯 Tehdit modellemesi (Threat modeling)

**Tehdit modellemesi**, potansiyel tehditleri belirleyerek bunlara karşı önlem almamızı sağlayan bir süreçtir. Tehdit modelinizi oluşturmak için kendinize şu soruyu sorun:

- **“Ne tür bir tehlike içindeyim? ”** Örneğin kredi kartı hack'leri, kurumsal casusluk veya çevrimiçi taciz/doxxing. (kişisel bilgilerin ifşa edilmesi)
- **"Ne tür varlıkları koruyorum? ”** Örneğin gizli belgeler, özel fotoğraflar veya kişisel mesajlar.

Yine de unutmayın, tehdit modeliniz değişebilir - zaman içinde kademeli olarak veya yeni bir yasa aniden kabul edildiğinde aniden.

### 🔗 En zayıf halka

**En zayıf bağlantı** dijital güvenliğinizin en savunmasız olduğu yerdir. Örneğin, bir hesabın parolamı unuttum işlevi e-postanıza bir bağlantı gönderirse, saldırganların hesaba erişmek için yalnızca e-postanıza erişmesi gerekir.

### 🔡 Şifreleme seviyeleri

**Şifreleme**, bilgiyi yoldan geçenler tarafından okunamaz hale getirmek ve yetkisiz erişimi önlemek için karıştırma veya kodlama işlemidir. İnsanlar genellikle **şifrelemeyi** bu üç türe ayırır:

1. **Şifreleme yok:** Herhangi bir üçüncü taraf veriyi kesebilir ve olduğu gibi okuyabilir. Genellikle “düz metin” olarak adlandırılır.
2. **Standart şifreleme:** Veriler, araya giren üçüncü tarafların okuyamayacağı şekilde şifrelenir, ancak verileri göndermek için kullanılan platform (örneğin Facebook Messenger) verileri çözebilir ve okuyabilir. Platform, emir verilmesi halinde şifresi çözülmüş verileri mahkemelere verilir.
3. **Uçtan uca şifreleme:** Verileri yalnızca orijinal gönderici ve alıcı okuyabilir. Verileri göndermek için kullanılan platform sadece karıştırılmış, okunamayan versiyona sahiptir. Dolayısıyla, mahkemeler platforma verileri teslim etmesini emrederse, teslim edilecek yararlı bir şey yoktur.

### 🧩 Meta Veriler

**Metadata** verilerinizi çevreleyen bağlamsal bilgilerdir. Örneğin, bir telefon görüşmesinin meta verileri, aradığınız numarayı ve görüşmenizin uzunluğunu içerir (ancak görüşmenin içeriğini içermez). Yeterli meta veri ile saldırganlar kim olduğunuza, kimleri tanıdığınıza ve nereye gittiğinize dair nispeten güvenilir bir resim oluşturabilirler.

*Ne yazık ki, meta verilerle ilgili yasal korumalar zayıf ya da hiç yoktur.*

--- 

## 🚶🏽‍♀️ Seviye 1

### ✅ Yapılacak şeyler

#### Önemli hesapları belirleyin

- Bir saldırganın tüm çevrimiçi hesaplarınıza erişim sağladığını düşünün. Bu hesaplardan hangilerini kaybetmek gerçekten acı verici olurdu? Bunları listeleyin ve bir kenara yazın.
- Genellikle bu liste e-posta, çevrimiçi bankacılık, sosyal medya ve belki de işle ilgili bir veya iki hesap için kullanılan hesapları içerir.
- Liste kısa olmalı ve 5-6 hesaptan az olmalıdır.

#### Önemli hesapları iki kere kilitleyin

İlk kilit genellikle hesap şifrenizdir. İkinci kilit farklı bir biçim alır ve/veya farklı bir kanaldan gelir - çoğunlukla bir uygulama veya kısa mesaj (SMS) yoluyla telefonunuza gönderilen bir kod olarak. Bu ek kilit genellikle *iki faktörlü kimlik doğrulama* (*2FA* olarak kısaltılır) olarak adlandırılır.

- **Az önce tanımladığınız önemli hesaplar** için iki faktörlü kimlik doğrulamayı açın. Bunun nasıl yapılacağına ilişkin talimatları bulmak için:
  - İnternette `iki faktörlü kimlik doğrulama` ve hesap adı için bir arama yapın. Örneğin: Instagram iki faktörlü kimlik doğrulama
  - Hesap sağlayıcısını [2fa.directory](https://2fa.directory) adresinde arayın
- **Bir kimlik doğrulayıcı uygulaması kullanın.** 2FA kodunuzu almak için SMS kullanmaktan daha güvenlidirler.
  - Önerilen uygulama: [Authy](https://authy.com/).
- Telefonunuzu kaybetmeniz ihtimaline karşı kimlik doğrulayıcı uygulamanız için bulut yedeklemeyi** açın.
  - Talimatlar için: [Authy](https://authy.com/features/backup/).

#### Önemli hesaplardaki yedek güvenlik sorularını iki kez kontrol edin

- **Bu soruların yanıtlarının hakkınızdaki kamuya açık bilgiler kullanılarak öğrenilmesinin kolay olmadığından emin olun.** Güvenlik soruları genellikle oturum açma veya parola sıfırlama sırasında kimliğinizi doğrulamak için kullanılır, bu nedenle çok önemli bir rol oynarlar.

#### E-postanızın güvenliğini sağlayın

- **https:// için adres çubuğunu kontrol edin** Bir web posta hizmeti kullanıyorsanız, bir `https://` URL'si kullanarak giriş yapıp yapmadığınızı kontrol edin. Eğer böyle bir URL yoksa, yeni bir e-posta sağlayıcısı bulun.
- **E-posta hizmetinizin yedek kodları destekleyip desteklemediğini öğrenin.** 2FA'yı açtığınızda, e-posta sağlayıcınız telefonunuzu kaybetmeniz durumunda kullanabileceğiniz tek kullanımlık yedek kodlar sağlayabilir.
  - Talimatlar için:
    - [Gmail](https://support.google.com/accounts/answer/1187538?hl=en)
    - [Protonmail](https://protonmail.com/support/knowledge-base/set-account-recovery-methods/#how-to-enable-a-recovery-phrase)
    - [iCloud](https://support.apple.com/en-us/HT208072)

#### Telefonunuzu güvence altına alın

- **Telefonunuz için en az 10 basamaklı, yaygın kullanılmayan bir kilit açma kodu kullanın.** Şifre olarak ekrana dokunması daha kolay olduğu için uzun bir sayı dizisi kullanmanızı öneririz (ancak isterseniz hem harf hem de sayı kullanabilirsiniz). Ancak kaydırma desenli şifreler, ekranınızı izleyenler tarafından çok kolay kopyalanabildiği için önerilmez.
- **SIM kartınız için bir pin kodu ayarlayın:**
  - Talimatlar için:
    - [Iphone](https://support.apple.com/en-hk/HT201529)
    - [Android](https://www.maketecheasier.com/change-sim-pin-android/).
  - Sizden bir SIM pin kodu isterse ve ayarladığınızı hatırlamıyorsanız, telefon şirketi varsayılan olarak bir tane ayarlamış olabilir. Ne olduğunu öğrenmek için telefon sağlayıcınızın web sitesine gidin.
- **USB aksesuarlarının kilitli bir cihazı kontrol etmesine izin vermeyin:**
  - iOS: `Ayarlar → Face ID ve Parola → Kilitliyken Erişime İzin Ver seçeneğini kapatın: USB Aksesuarları `seçeneğini kapatın.
  - Android: Ayar varsayılan olarak kapalıdır ve yalnızca `Geliştirici Seçenekleri` açıksa kullanılabilir.
- **iOS cihazları için `Çalıntı Cihaz Koruması` özelliğinin açık olduğundan emin olun:**
  - `Ayarlar → Face ID ve Parola → Çalınan Cihaz Koruması`

#### Bilgisayarınızın güvenliğini sağlayın

- Masaüstü web tarayıcı(lar)ınızda **Sadece HTTPS modunu** açın (şifrelenmemiş web sitesi trafiğine karşı uyarır):
  - Talimatlar için:
    - [Firefox, Chrome, Edge, Safari](https://www.eff.org/https-everywhere/set-https-default-your-browser)
- **Bilgisayarınızın güvenlik duvarını açın:**
  - macOS: `Sistem Tercihleri → Güvenlik ve Gizlilik → Güvenlik Duvarı`.
  - Windows: `Denetim Masası → Sistem ve Güvenlik → Windows Güvenlik Duvarı`.
- **Bilgisayarınızın uzaktan erişimini kapatın:**
  - macOS: `Sistem Tercihleri → Paylaşım → Uzaktan Oturum Açma, Uzaktan Yönetim`.
  - Windows: `Denetim Masası → Sistem ve Güvenlik → Sistem: Uzaktan erişime izin ver → Bu bilgisayara Uzak bağlantılara İzin Verme`.
- **Bilgisayarınızda temel anti-virüs yazılımı kurun:**
  - macOS: Gerekli değil; [Wirecutter'ın açıklamasını okuyun](https://www.nytimes.com/wirecutter/blog/best-antivirus/).
  - Windows: Microsoft Defender Antivirüs'ü açın ([talimatlar](https://support.microsoft.com/en-us/windows/stay-protected-with-windows-security-2ae0363d-0ada-c064-8b56-6a39afb6a963)) ve [ekstra `fidye yazılımı koruması` özelliğini açın](https://lifehacker.com/why-you-should-use-windows-defenders-ransomware-prevent-1837311176).
#### Diğer hususlar

- **İki faktörlü kimlik doğrulamayı atlayan uygulamaya özel şifreleri (mümkünse) kapatın.**.
  - Talimatlar için:
    - [Gmail](https://www.lifewire.com/revoke-an-application-password-for-gmail-1171889)
    - [iCloud](https://support.apple.com/en-us/HT204397)
- **Kötü amaçlı bağlantılar göndermek için kullanılabilen otomatik olarak eklenen takvim davetiyelerini** kapatın.
  - Google Takvim [Ayarlar](https://calendar.google.com/calendar/r/settings) `→ Etkinlik Ayarları → Takvimime davetiye ekle: Davete e-posta ile yanıt verdiğimde`
  - Outlook: Dosya → Seçenekler → Takvim → Otomatik kabul et veya reddet → Otomatik Kabul Et / Reddet: Toplantı İsteklerini Otomatik Olarak Kabul Et ve İptal Edilen Toplantıları Kaldır`
- **Microsoft Office'te makroları devre dışı bırakın ** Makrolar, saldırganlar tarafından istismar edilebilecek eylemleri otomatikleştiren küçük kod parçalarıdır. Yine de bazen yararlı olabilirler, bu nedenle güvenilir kaynaklardan gelen makroların çalışmasına manuel olarak izin vermenizi sağlayan `Bildirimli tüm makroları devre dışı bırak` seçeneğini öneriyoruz.
  - Talimatlar için:
    - [macOS](https://support.microsoft.com/en-us/office/enable-or-disable-macros-in-office-for-mac-c2494c99-a637-4ce6-9b82-e02cbb85cb96)
    - [Windows](https://support.microsoft.com/en-us/office/macros-in-office-files-12b036fd-d140-4e74-b45e-16fed1a7e5c6), [Excel için özel ayarlar](https://support.microsoft.com/en-us/office/change-macro-security-settings-in-excel-a97c09d2-c082-46b8-b19f-e8621e8fe373) gerektirebilir.


### 💪🏽 Geliştirilecek Alışkanlıklar

#### Kimlik avı dolandırıcılıklarına dikkat edin

Kimlik avı dolandırıcılığı, saldırganın sizden şifre veya diğer giriş bilgilerini almaya çalıştığı bir e-posta veya kısa mesajdır. Kendinizi korumak için:

- **İçgüdülerinize güvenin.** Eğer bir şeyin yanlış olduğunu hissediyorsanız — bu, metnin yazılma biçimi, grafiklerin görünümü veya bir hizmet sağlayıcısından gelen alışılmadık, ilk kez yapılan bir istek olabilir — muhtemelen öyledir.
- **Gönderenin kim olduğuna bakın.** Gönderenin adını, telefon numarasını veya e-posta adresini dikkatlice inceleyin. Eğer bu bir e-posta ise, özellikle `@` sembolünden sonraki kısmı dikkatlice okuyun.
- **Ancak gönderen bilgileri taklit edilebilir.** Nadir olsa da, teknik olarak sahte bir gönderici adı, e-posta veya telefon numarası kullanmak mümkündür. Bu yüzden gönderen bilgilerini kontrol etmek %100 güvenilir bir yöntem değildir.
- **Bir bağlantıya tıklamadan önce iki kez düşünün.** Şüphe duyduğunuzda, bağlantıdaki alan adını dikkatlice inceleyin. Bağlantıyı açmadan görmek için:
  - Mobilde:
    - iOS: Bir bağlantıya dokunup basılı tutun. Gideceği yerin küçük bir önizlemesi belirecektir. Bu mini pencerenin sağ üst köşesinde `Önizlemeyi gizle`ye dokunun. Bundan sonra, iOS bir bağlantıya dokunup basılı tuttuğunuzda tam URL'yi gösterecektir.
    - Android: Bir bağlantıya dokunup basılı tutun.
  - Masaüstünde:
    - Firefox, Chrome, Edge: Fare imlecinizi bir bağlantı veya düğmenin üzerine getirdiğinizde tam URL sol alt köşede görünecektir.
    - macOS Safari: Bu özelliği açmak için `Görünüm → Durum Çubuğunu Göster` seçeneğine gidin.
    - macOS Mail: Fare imlecinizi bir bağlantının üzerine getirin ve birkaç saniye bekleyin, bir açılır pencere görünecektir.
- **Bağlantılara tıkladıktan sonra, tarayıcınızdaki URL adres çubuğunu kontrol edin.**
  - Kırmızı bir uyarı ikonu veya 'Güvenli Değil' etiketi var mı? Bu, sitenin `https` yerine şifresiz olarak `http` üzerinden çalıştığı anlamına gelir.
  - Alan adı yanlış mı yazılmış?
- **Eğer hala bir şüpheniz varsa, bağlantıya tıklamayın.** Çoğu durumda bağlantıya tıklamanız gerekmez. Bunun bir işlem veya başvuru ile ilgili olduğunu düşünüyorsanız, her zaman orijinal web sitesine gidip detayları oradan kontrol edebilirsiniz.

#### Dosya eklerine dikkat edin

- **Gereksiz dosya eklerini indirmeyin/açmayın.**
  - Şüphe duyduğunuzda, dosyanın ne olduğunu sormak için asıl göndericiye mesaj yazın.
  - E-postada, ekleri uygulama veya web sitesi içinde önizleyin. Gmail ve Protonmail'de ekin üzerine tıklamak, onu posta programı içinde güvenli bir ortamda önizler.
  - Göndericiden bir dosya paylaşım hizmeti (Dropbox, Google Drive, Tresorit) kullanmasını isteyin, bu hizmetler de kendi çevrimiçi önizleme sistemlerine sahiptir.
- **Şüpheli ekleri analiz etmeleri için [VirusTotal](http://www.virustotal.com) sitesine yükleyin.** *Unutmayın ki VirusTotal'e gönderilen dosyalar, birçok güvenlik araştırmacısıyla paylaşılabilir, bu yüzden hassas bilgileri göndermeyin.*

#### Her şeyi güncelleyin

- **Cihaz işletim sistemleri:** Cihazlarınıza işletim sistemini güncellemeniz gerektiğini belirten bir bildirim geldiğinde, bunu mümkün olan en kısa sürede yapın.
- **Otomatik güncellemeler:** Uygulamalarınızda bu özellik varsa, otomatik güncellemeyi açın. Bir uygulamayı güncellemeniz istenirse, bunu da en kısa sürede gerçekleştirin.
- **Donanım yazılımı güncellemeleri:** Yönlendirici ve diğer internet bağlantılı cihazlarınız için zaman zaman donanım yazılımı güncellemelerini kontrol edin.

#### Diğer hususlar

- **Uygulama içi tarayıcıları olabildiğince az kullanın.** Bir mobil uygulama, web tarayıcınızı açmadan bir web sayfasına göz atmanıza izin verdiğinde (yani uygulama içi tarayıcı kullanarak), uygulama ziyaret ettiğiniz siteleri ve bazı durumlarda yazdıklarınızı takip edebilir. Bu yüzden, bir uygulama içi tarayıcıda gezinirken, telefonunuzun/tabletinizin normal tarayıcısını açma ikonunu bulup hemen ona geçin.
- **Bilinmeyen USB bellekleri/sürücüleri bilgisayarınıza takmayın.** Zararlı yazılım içerebilir.
- **Cihazlarınızı bağışlamadan veya vermeden önce düzgün şekilde silin.** Telefonlarınızı ve bilgisayarlarınızı (daha önce önerildiği gibi) şifrelediyseniz, standart bir fabrika ayarlarına sıfırlama çoğu durumda yeterli olacaktır.
  - Bilgisayar sabit diskleriniz için ekstra güvenlik istiyorsanız, [Wired'ın bu konudaki rehberine](https://www.wired.co.uk/article/securely-wipe-android-iphone-hard-disk) bakın.
- **Telefonunuzu halka açık şarj istasyonlarında/portlarında şarj etmeyin.** Bu, saldırganların verilerinizi çalabileceği bir risk taşır. Bunun yerine, taşınabilir bir batarya kullanın ya da doğrudan prizde şarj edebilmek için kendi adaptörünüzü getirin.

---

**👍 Harika iş çıkardın!**  
**👍 Çevrimiçi güvenliğin ve gizliliğin için**  
**👍 önemli hızlı kazançlar elde ettin.**  
**👍 Lütfen kendine bir fincan çay ve bir esneme molası ver.**  
**👍**  
**👍 Şimdi, 2. seviyeye hazır mısın?**

---

