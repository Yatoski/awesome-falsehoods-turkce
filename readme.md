<!--lint disable awesome-heading-->
<p align="center">
  <a href="https://github.com/kdeldycke/awesome-falsehood/">
    <img src="https://github.com/kdeldycke/awesome-falsehood/raw/main/assets/awesome-falsehood-header.jpg" alt="Awesome Falsehood header image">
  </a>
</p>
Dünyanın mantığı tüm doğruluk ve yanlışlıktan önce gelir.  
— Ludwig Wittgenstein[1]

Programcıların inandığı yanlışların derlendiği, özenle seçilmiş bir Harika listesi. Yanlış, başlangıçta doğru olduğuna inandığınız, ancak gerçekte yanlış olduğu kanıtlanmış bir fikirdir.

Örnek fikir: geçerli bir e‑posta adresi tam olarak bir @ karakteri içerir. Böylece e‑posta alanı doğrulama mantığınızı bu kurala göre yazarsınız. Doğru mu? Yanlış! Gerçek: e‑postalar birden fazla @ işareti içerebilir. Bu yüzden uygulamanız buna izin vermelidir. Başlangıçtaki fikir, inandığınız bir yanlıştır.

Aşağıda listelenen yanlış makaleleri, daha iyi bir programcı olmanıza yardımcı olmak için bilmeniz gereken kapsamlı bir yanlış inanışlar listesi sunar.

## İçindekiler

- [Meta](#meta)
- [Sanat](#sanat)
- [İş Dünyası](#i̇ş-dünyası)
- [Kripto Para](#kripto-para)
- [Tarih ve Saat](#tarih-ve-saat)
- [Eğitim](#eğitim)
- [E‑postalar](#e-postalar)
- [Coğrafya](#coğrafya)
- [İnsan Kimliği](#i̇nsan-kimliği)
- [Uluslararasılaştırma](#uluslararasılaştırma)
- [Yönetim](#yönetim)
- [Çoklu Ortam](#çoklu-ortam)
- [Ağlar](#ağlar)
- [Telefon Numaraları](#telefon-numaraları)
- [Posta Adresleri](#posta-adresleri)
- [Bilim](#bilim)
- [Toplum](#toplum)
- [Yazılım Mühendisliği](#yazılım-mühendisliği)
- [Ulaşım](#ulaşım)
- [Tipografi](#tipografi)
- [Video Oyunları](#video-oyunları)
- [Web](#web)

### Meta

- [Programcıların İnandığı Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-programmers-believe) – Yaygın yanlışların kısa bir listesi. Yanlışlar dünyasına harika bir genel bakış ve hızlı giriş.
- [Programlama Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-programming) – Programlama ve programcıların kendileri hakkında alçakgönüllü ve eğlenceli bir liste.
- [Yanlış Listeleri Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-falsehoods-lists) – Bu yanlışların nasıl ele alınmaması gerektiğine dair meta yorum.

### Sanat

- [Müzik Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-music) – Müziği kodlarken yapılabilecek yanlış varsayımlar.
- [Sanat Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-art) – Sanatla ilgili yaygın yanlış anlamalar.

### İş Dünyası

- [Çevrimiçi Alışveriş Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-online-shopping) – Fiyatlar, para birimleri ve envanteri kapsar.
- [Fiyatlar Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-prices) – Para birimleri, tutarlar ve yerelleştirmeyi kapsar.
- [IBAN Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-ibans) – Uluslararası Banka Hesap Numaraları uluslararası değildir.
- [Ekonomi Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-economics) – Ekonomi basit ya da rasyonel değildir.
- [Etsy'nin Muhasebe Sistemindeki Ondalık Nokta Hatası](https://github.com/kdeldycke/awesome-falsehood#decimal-point-error-in-etsys-accounting-system) – Muhasebe yazılımında tiplerin önemi: ondalık noktayı kaçırmak 100 kat fazla ücretlendirmeye yol açar.
- [Yirmi beş bin dolarlık komik para](https://github.com/kdeldycke/awesome-falsehood#twenty-five-thousand-dollars-of-funny-money) – Google Ads’te yukarıdaki hatanın aynısı; sentler ile dolarları ayırmanın tehlikesi. 250$’lık dahili kupon 25.000$’a dönüştü. Tavsiyem: parasal değerler için tamsayı ve kayan noktalı sayılardan kurtulun. Ondalıklı (decimal) kullanın. Ya da string’lere dönüp ayrıştırın, doğrulamayın.
- [“Sistem bir milyar doları kaldıramaz”](https://github.com/kdeldycke/awesome-falsehood#the-system-cant-handle-a-billion-dollars) – Yapay zeka patlamasının ortasında Meta’daki çılgın tazminatlar ERP’leri çökertiyor.
- [Şirket adlarındaki < ve > karakterleri XSS saldırılarına yol açıyor](https://github.com/kdeldycke/awesome-falsehood#characters--and--in-company-names-lead-to-xss-attacks) – İngiltere’de şirketlerin özel karakterlerle tescil edilmesine izin verildiği için bir hacker `\"><SCRIPT SRC=MJT.XSS.HT></SCRIPT> LTD` yanında `; DROP TABLE "COMPANIES";-- LTD`, `BETTS &AMP; TWINE LTD` ve `SAFDASD & SFSAF \' SFDAASF\" LTD` şirketlerini kaydettirdi.
- [Şirket adlarının ayrıntıları](https://github.com/kdeldycke/awesome-falsehood#minutiae-of-company-names) – Delaware Eyaleti ile IRS kurallarının nasıl örtüşmediği.
- [CLDR para birimi tanımları](https://github.com/kdeldycke/awesome-falsehood#cldr-currency-definitions) – 🆓 İsyanlar, işgaller, yeni anayasalar ve yavaş planlı geçişler nedeniyle para birimi geçerlilik tarih aralıkları çakışır.
- [tax](https://github.com/kdeldycke/awesome-falsehood#tax) – 🆓 PHP 5.4+ vergi yönetim kütüphanesi.

### Kripto Para

- [Bitcoin Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-bitcoin) – Bitcoin’e dair hatalı bakış açıları listesi.
- [Ethereum Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-ethereum) – Sözleşme programlamada yanlış anlamalar ve yaygın tuzaklar.

### Tarih ve Saat

- [Zaman Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-time) – Tarih ve saat üzerine ufuk açıcı makale.
- [Zaman Hakkında Daha Fazla Yanlış](https://github.com/kdeldycke/awesome-falsehood#more-falsehoods-about-time) – Yukarıdaki makalenin 2. bölümü.
- [Zaman ve Saat Dilimleri Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-time-and-time-zones) – Saat dilimlerine vurgu yapan bir başka zaman yanlışları derlemesi.
- [Zaman Hakkında Yanlışların Eleştirisi](https://github.com/kdeldycke/awesome-falsehood#critique-of-falsehoods-about-time) – İlk makaleyi ele alır, her yanlışa daha fazla bağlam ve dış kaynaklarla açıklama getirir.
- [Unix Zamanı Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-unix-time) – Artık saniyeye dikkat!
- [Saat Dilimleri Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-time-zones) – DST geçişlerinin uç durumlarına dair güzel noktalar içerir.
- [Sizin Takvime Dair Yanılgınız Şunu Düşünmek…](https://github.com/kdeldycke/awesome-falsehood#your-calendrical-fallacy-is-thinking) – iOS ve macOS geliştiricileri topluluğu tarafından hazırlanmış, ara ekleme ve kültürel etkiyi kapsayan liste.
- [Zaman Dilimi Veritabanı](https://github.com/kdeldycke/awesome-falsehood#time-zone-database) – 🆓 Dünya çapında birçok temsili konum için yerel zamanın tarihçesini temsil eden kod ve veri.
- [Zamanın Uzun ve Acılı Tarihi](https://github.com/kdeldycke/awesome-falsehood#the-long-painful-history-of-time) – Zaman ölçümündeki tuhaflıkların çoğu tarihte bir açıklama bulur.
- [Bir Takvim Reformu Öneriyorsunuz](https://github.com/kdeldycke/awesome-falsehood#you-advocate-a-calendar-reform) – Fikriniz işe yaramayacak. Bu makale nedenini anlatıyor.
- [Saat Dilimlerini Kaldırmak İstiyorsunuz](https://github.com/kdeldycke/awesome-falsehood#so-you-want-to-abolish-time-zones) – Saat dilimlerini kaldırmak iyi bir fikir gibi gelebilir, ancak bunu pek de öyle olmaktan çıkaran epeyce karmaşıklık var.
- [Zaman ve Saat Dilimleri Sorunu](https://github.com/kdeldycke/awesome-falsehood#the-problem-with-time--timezones) – Mümkünse neden saat dilimleriyle asla uğraşmamanız gerektiğini anlatan bir video.
- [Çalışma Bakanlığı'nın 26.000$ Fazla Tahsilatı](https://github.com/kdeldycke/awesome-falsehood#26000-overcollection-by-labor-department) – Yanlış takvim hesaplamasının sonucu.
- [RFC-3339 vs ISO-8601](https://github.com/kdeldycke/awesome-falsehood#rfc-3339-vs-iso-8601) – İki standardın formatlarından oluşan dev bir liste, nasıl örtüştükleri ve canlı örnekler.
- [ISO-8601, YYYY, yyyy ve yılınız neden yanlış olabilir](https://github.com/kdeldycke/awesome-falsehood#iso-8601-yyyy-yyyy-and-why-your-year-may-be-wrong) – Tarihin string biçimlendirmesi zordur.
- [UTC Herkes İçin Yeterli, değil mi?](https://github.com/kdeldycke/awesome-falsehood#utc-is-enough-for-everyone-right) – Tarih ve saatle (özellikle UTC) ilgili muhtemelen düşünmediğiniz uç durumlar var.
- [UTC Saklamak Gümüş Bir Kurşun Değildir](https://github.com/kdeldycke/awesome-falsehood#storing-utc-is-not-a-silver-bullet) – “Tarihleri UTC olarak saklayın” her zaman doğru yaklaşım değildir.
- [UT1, TAI ve UTC Arasında Nasıl Seçim Yapılır](https://github.com/kdeldycke/awesome-falsehood#how-to-choose-between-ut1-tai-and-utc) – SI saniyeleri, dünya dönüşüyle senkronizasyon, artık saniyelerden kaçınma önceliklerinize bağlıdır.
- [Neden bu iki zamanı (1927'de) çıkarmak garip bir sonuç veriyor?](https://github.com/kdeldycke/awesome-falsehood#why-is-subtracting-these-two-times-in-1927-giving-a-strange-result) – Hem karmaşık tarihi saat dilimleri hem de tarihi tarihlerin yazılımın yeni sürümleri tarafından nasıl yeniden yorumlanabileceği hakkında meşhur Stack Overflow cevabı.
- [Kritik ve Önemli Tarihler](https://github.com/kdeldycke/awesome-falsehood#critical-and-significant-dates) – Y2K’dan Unix zaman damgasının 32 bit taşmasına, sisteme bağlı olarak dikkat edilmesi gereken özel tarihlerin listesi.
- [“Vermont’ta bir komüne gidiyorum ve bir mevsimden daha kısa hiçbir zaman birimiyle uğraşmayacağım.”](https://github.com/kdeldycke/awesome-falsehood#im-going-to-a-commune-in-vermont-and-will-deal-with-no-unit-of-time-shorter-than-a-season) – 70’lerde bir mühendisin saniye altı zamanlama endişeleriyle çok uğraştıktan sonra terminaline bıraktığı not. Kaynak: *The Soul of a New Machine*.

### Eğitim

- [Bilgisayar Bilimi Öğrencilerinin Mezun Olurken (Hâlâ) İnandığı Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-cs-students-still-believe-upon-graduating) – Sadece bilgisayar bilimi öğrencilerinin değil, şaşırtıcı biçimde bazen daha iyisini bilmeleri gerekirken bile hatalı biçimde inandıkları şeylerin listesi.
- [Doktora sonrası mitleri](https://github.com/kdeldycke/awesome-falsehood#postdoc-myths) – “Doktora sonrası araştırmacılar hakkında söylenen, yazılan ve inanılan pek çok şey doğru değildir.”

### E‑postalar

- [E‑posta Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-email) – Adresler, içerik ve teslimat üzerine.
- [RFC'yi Okuyana Kadar Bir E‑posta Adresini Nasıl Doğrulayacağımı Biliyordum](https://github.com/kdeldycke/awesome-falsehood#i-knew-how-to-validate-an-email-address-until-i-read-the-rfc) – RFC-822’ye göre geçerli olduğu tahmin edilemeyen karmaşık örnekler sunar.
- [Yani e‑posta adreslerini doğrulayabileceğinizi mi düşünüyorsunuz (FOSDEM 2018)](https://github.com/kdeldycke/awesome-falsehood#so-you-think-you-can-validate-email-addresses-fosdem-2018) – Uç durum e‑posta adreslerinin ve neden regex kullanarak ayrıştırmamanız gerektiğinin sunumu.
- [E‑posta Doğrulama Mantığınız Yanlış](https://github.com/kdeldycke/awesome-falsehood#your-e-mail-validation-logic-is-wrong) – Bir e‑posta adresinde izin verilen çeşitli şaşırtıcı şeylerin özeti.
- [libvldmail](https://github.com/kdeldycke/awesome-falsehood#libvldmail) – 🆓 E‑posta adresleri için RFC tabanlı kontroller uygulayan bir kütüphane.

### Coğrafya

- [Coğrafya Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-geography) – Yerler, adları ve konumları üzerine.
- [Haritalar Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-maps) – Koordinatlar, projeksiyon ve CBS'yi kapsar.
- [Hava Durumu Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-weather) – Hava durumu konuma bağlıdır ve bu nedenle uç durumlarla doludur.
- [Koordinat Sistemlerinden Nefret Ediyorum](https://github.com/kdeldycke/awesome-falsehood#i-hate-coordinate-systems) – Konumsal uygulayıcılar için koordinat sistemleriyle ilgili yaygın sorunları teşhis ve düzeltme kılavuzu.
- [Japonya'daki en çılgın 5 kanji yer adı](https://github.com/kdeldycke/awesome-falsehood#top-5-most-insane-kanji-place-names-in-japan) – “Japonların bile okumakta zorlandığı özel bir kanji grubu var: yer adları.”

### İnsan Kimliği

- [İsimler Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-names) – Her şeyi başlatan makale.
- [İsimler Hakkında Yanlışlar – Örneklerle](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-names--with-examples) – Yukarıdaki makalenin bu kez ayrıntılı açıklamalarla gözden geçirilmiş hali.
- [Biyometri Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-biometrics) – Parmak izleri benzersiz değildir.
- [Aileler Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-families) – Bir aileyi katı kurallarla gerçekten tanımlayamazsınız.
- [Cinsiyet Hakkında Yanlışlar: #1](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-gender-1) & [#2](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-gender-2) – Cinsiyet insan kimliğinin bir parçasıdır ve kendi inceliklerine sahiptir.
- [Benim Hakkımda Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-me) – İsimler, cinsiyet ve uluslararasılaştırmanın kesişimindeki sorunlar.
- [Eşcinsel Evlilik: Veritabanı Mühendisliği Perspektifi](https://github.com/kdeldycke/awesome-falsehood#gay-marriage-the-database-engineering-perspective) – Cinsiyet, adlandırma ve ilişkiler hakkındaki yanlışların çoğunu ele alarak bir evlilik veritabanında nasıl saklama yapılır.
- [Dünya Genelinde Kişisel İsimler](https://github.com/kdeldycke/awesome-falsehood#personal-names-around-the-world) – İnsanların isimleri dünya çapında nasıl farklılık gösterir ve bunun Web için sonuçları nelerdir?
- [XKCD #327: Bir Annenin İstismarları](https://github.com/kdeldycke/awesome-falsehood#xkcd-327-exploits-of-a-mom) – Bir yanlışın uygulanmasının güvenlik açıklarına nasıl yol açabileceğine dair komik bir örnek.
- [Merhaba, ben Bay Null. Adım Beni Bilgisayarlara Görünmez Kılıyor](https://github.com/kdeldycke/awesome-falsehood#hello-im-mr-null-my-name-makes-me-invisible-to-computers) – Uygulanan bir yanlışın birinin hayatını nasıl olumsuz etkilediğine dair gerçek yaşam örneği.
- [HL7 v3 RIM](https://github.com/kdeldycke/awesome-falsehood#hl7-v3-rim) – İnsan isimlerini temsil etmek için esnek bir veri modeli.
- [Apple iOS NSPersonNameComponentsFormatter](https://github.com/kdeldycke/awesome-falsehood#apple-ios-nspersonnamecomponentsformatter) – Bir kişinin adının bileşenlerinin yerelleştirilmiş gösterimleri.

### Uluslararasılaştırma

Karakter kodlaması, string biçimlendirme, unicode ve uluslararasılaştırma üzerine.

- [Dil Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-language) – Bir yazılımı İngilizceden çevirmek göründüğü kadar basit değildir.
- [Dil Hakkında Yanlışlar (ek)](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-language-1) – Önceki makaleyi tamamlayan ilave vakalar.
- [Düz Metin Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-plain-text) – Düz metin yetersiz kalır, bu da Unicode'u sorunsuz çalışabilme yeteneğiyle daha da inanılmaz kılar.
- [Metin hakkında yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-text) – Unicode normalizasyonu, bitişik harfler, vekil çiftler, karakter genişlikleri ve alt string işlemlerindeki grafem kümesi tuzaklarını gösteren pratik örnekler.
- [Kodu Uluslararasılaştırma](https://github.com/kdeldycke/awesome-falsehood#internationalisz-ing-code) – Kodunuzu uluslararasılaştırırken aklınızda bulundurmanız gerekenler hakkında bir video.
- [Unicode ve Karakter Kümeleri Hakkında Bilinmesi Gereken Minimum Şey](https://github.com/kdeldycke/awesome-falsehood#minimum-to-know-about-unicode-and-character-sets) – Unicode'a, tarihsel bağlamına ve kökenlerine iyi bir giriş, ardından iç işleyişine genel bakış.
- [Harika Unicode](https://github.com/kdeldycke/awesome-falsehood#awesome-unicode) – Keyifli Unicode bilgi kırıntıları, paketler ve kaynakların özenle seçilmiş listesi.
- [Unicode'un Karanlık Köşeleri](https://github.com/kdeldycke/awesome-falsehood#dark-corners-of-unicode) – Unicode kapsamlıdır, işte ejderhalar.
- [Kod Noktalarına Anlam Yüklemeyi Bırakalım](https://github.com/kdeldycke/awesome-falsehood#lets-stop-ascribing-meaning-to-code-points) – Unicode'a derinlemesine dalar ve kod noktaları hakkındaki mitleri çürütür.
- [Unicode yanlış anlamaları](https://github.com/kdeldycke/awesome-falsehood#unicode-misconceptions) – Harf büyüklüğü, kodlamalar, string uzunluğu ve daha fazlası üzerine bir yanlışlar koleksiyonu.
- [Latin-1 Varsayımlarımızı Kırmak](https://github.com/kdeldycke/awesome-falsehood#breaking-our-latin-1-assumptions) – Çoğu programcı Latin-1 ile o kadar çok zaman geçirir ki diğer yazı sistemlerinin tuhaflıklarını unutur.
- [Bir kargo etiketine övgü](https://github.com/kdeldycke/awesome-falsehood#ode-to-a-shipping-label) – Karakter kodlaması zordur, özellikle de her kırık veri giriş katmanı kendi baharatını eklediğinde.
- [Yerelleştirme Başarısızlığı: Sıcaklık Zordur](https://github.com/kdeldycke/awesome-falsehood#localization-failure-temperature-is-hard) – Sıcaklık farklarını olduğu gibi yerelleştiremezsiniz.
- [i18n Test Verisi](https://github.com/kdeldycke/awesome-falsehood#i18n-testing-data) – 🆓 Birim test ve QA için gerçek dünya uluslararası ve çeşitli isim verilerinin derlemesi.
- [Büyük Yaramaz String Listesi](https://github.com/kdeldycke/awesome-falsehood#big-list-of-naughty-strings) – 🆓 Kullanıcı girdisi olarak kullanıldığında sorun çıkarma olasılığı yüksek dev bir string külliyatı. Yazılımınızı karşı test etmek için olmazsa olmaz pratik uç durumlar seti.

### Yönetim

- [İş Adayları Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-job-applicants) – İş adayları ve iş geçmişleri hakkındaki varsayımlar her zaman doğru değildir.

### Çoklu Ortam

- [Video Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-video) – Hepsini kapsar: video çözme ve oynatma, dosyalar, görüntü ölçekleme, renk uzayları ve dönüşüm, ekranlar ve altyazılar.
- [Müzikle uğraşırken dikkate alınması gereken korkunç uç durumlar](https://github.com/kdeldycke/awesome-falsehood#horrible-edge-cases-to-consider-when-dealing-with-music) – Müzik katalog verileri çılgın şeylerle doludur.
- [MusicBrainz veritabanı şeması](https://github.com/kdeldycke/awesome-falsehood#musicbrainz-database-schema) – Müzik katalog yönetiminin karmaşıklığını çözmüş gibi görünen açık kaynaklı bir proje ve veritabanı.
- [DDEX](https://github.com/kdeldycke/awesome-falsehood#ddex) – Arşivleme, ses kaydı, satış ve kullanım raporlaması, telif hakları ve lisans anlaşmaları dahil müzik meta verisi için endüstri standardı.
- [Apple Music Stil Kılavuzu](https://github.com/kdeldycke/awesome-falsehood#apple-music-style-guide) – Keşfedilebilirliği artırmak için müzik, sanat eseri ve meta veriyi biçimlendirmeye yönelik kalite güvence yönergeleri.

### Ağlar

- [Ağlar Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-networks) – TCP, DHCP, DNS, VLAN'lar ve IPv4/v6'yı kapsar.
- [Dağıtık Hesaplamanın Yanılgıları](https://github.com/kdeldycke/awesome-falsehood#fallacies-of-distributed-computing) – Dağıtık uygulamalara yeni başlayan programcıların her zaman yaptığı varsayımlar.
- [Bir IP adresi yazmanın birden fazla yolu vardır](https://github.com/kdeldycke/awesome-falsehood#theres-more-than-one-way-to-write-an-ip-address) – Adresin bazı bölümleri isteğe bağlıdır, ondalık ve sekizlik gösterime dikkat edin ve IPv6'yı da unutmayın.
- [IDN çılgındır](https://github.com/kdeldycke/awesome-falsehood#idn-is-crazy) – Alan adlarındaki uluslararası karakterler, homograf ve heterograf desteği anlamına gelir.

### Telefon Numaraları

- [Telefon Numaraları Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-phone-numbers) – Telefon numaralarını, gösterimlerini ve anlamlarını kapsar.
- [libphonenumber](https://github.com/kdeldycke/awesome-falsehood#libphonenumber) – 🆓 Google'ın uluslararası telefon numaralarını ayrıştırmak, biçimlendirmek ve doğrulamak için ortak Java, C++ ve JavaScript kütüphanesi. C#, Objective-C, Python ve PHP için de mevcut.

### Posta Adresleri

- [Adresler Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-addresses) – Sokaklar, posta kodları, binalar, şehirler ve ülkeleri kapsar.
- [İkamet Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-residence) – Sadece adresin kendisi değil, bir kişi ile ikametgahı arasındaki ilişki de önemlidir.
- [İsimsiz, Adressiz Teslim Edilen Mektup](https://github.com/kdeldycke/awesome-falsehood#letter-delivered-despite-no-name-no-address) – Posta adresleriyle ilgili nihai yanlış: bir adrese ihtiyacınız yoktur.
- [Birleşik Krallık Adres Tuhaflıkları](https://github.com/kdeldycke/awesome-falsehood#uk-address-oddities) – 1995'ten bu yana İngiltere ve Galler'deki çoğu konut satışının listesinden çıkarılan tuhaflıklar.
- [Kendi Posta Koduna Sahip Ayı](https://github.com/kdeldycke/awesome-falsehood#the-bear-with-its-own-zip-code) – Smokey Bear'ın kendi posta kodu (20252) var çünkü çok fazla mektup alıyor.
- [Kosta Rika neden gerçek adresler kullanmıyor?](https://github.com/kdeldycke/awesome-falsehood#why-doesnt-costa-rica-use-real-addresses) – Kosta Rika, referans noktalarına, tarihe ve epeyce tahmine dayanan kendine özgü bir adres sistemi kullanır.
- [Regex ve Posta Adresleri](https://github.com/kdeldycke/awesome-falsehood#regex-and-postal-addresses) – Düzenli ifadeler ve sokak adresleri neden birbirine karışmaz.
- [Meşhur Japon Posta CSV'sini Ayrıştırmak](https://github.com/kdeldycke/awesome-falsehood#parsing-the-infamous-japanese-postal-csv) – “Birçok korkunç şey gördüm, ama bu özel biçimlendirme tercihini başka hiçbir yerde görmedim.”
- [USPS Posta Adresleme Standartları](https://github.com/kdeldycke/awesome-falsehood#usps-postal-addressing-standards) – Hem standart adres biçimlerini hem de içeriği tanımlar.
- [libaddressinput](https://github.com/kdeldycke/awesome-falsehood#libaddressinput) – 🆓 Google'ın uluslararası posta adreslerini ayrıştırmak, biçimlendirmek ve doğrulamak için ortak C++ ve Java kütüphanesi.
- [addressing](https://github.com/kdeldycke/awesome-falsehood#addressing) – 🆓 Google'ın veri kümesiyle çalışan PHP 5.4+ adresleme kütüphanesi.
- [postal-address](https://github.com/kdeldycke/awesome-falsehood#postal-address) – 🆓 Posta adreslerini ayrıştırmak, normalleştirmek ve biçimlendirmek için Python modülü.
- [address](https://github.com/kdeldycke/awesome-falsehood#address) – 🆓 Google'ın veri kümesini kullanarak adresleri doğrulamak ve biçimlendirmek için Go kütüphanesi.

### Bilim

- [Ölçüm Sistemleri Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-systems-of-measurement) – Ölçüm sistemleriyle çalışma ve aralarında dönüşüm yapma üzerine.

### Toplum

- [Siyasi Atamalar Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-political-appointments) – Seçim sistemleri tasarlamanın kendine has püf noktaları vardır.
- [Teknolojide Kadınlar Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-women-in-tech) – STEM (Fen, Teknoloji, Mühendislik, Matematik) sektörlerindeki kadınlar hakkındaki mitler.

### Yazılım Mühendisliği

- [Sürümler Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-versions) – Bir yazılım sürümüne kimlik atfetmek düşünüldüğünden daha zor olabilir.
- [Derleme Sistemleri Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-build-systems) – Yazılım derlemek zordur. Yazılım derleyen yazılım derlemek daha zordur.
- [Tanımsız Davranış Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-undefined-behavior) – Tanımsız davranışı çağırmak, "herhangi bir şey"in sanıldığından çok daha geniş bir tanımıyla her şeyin olmasına neden olabilir.
- [CPU Önbellekleri Hakkındaki Mitler](https://github.com/kdeldycke/awesome-falsehood#myths-about-cpu-caches) – Önbellekler hakkındaki yanlış anlamalar, özellikle eşzamanlılık ve yarış koşulları söz konusu olduğunda genellikle hatalı önermelere yol açar.
- [Null işaretçiler hakkında yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-null-pointers) – Null işaretçiler genel olarak işaretçilerden bile daha lanetlidir ve provenance zaten işaretçileri oldukça karmaşık hale getirir.
- [CSV'ler Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-csvs) – RFC4180 var olsa da, kesin olmaktan uzaktır ve büyük ölçüde göz ardı edilir.
- [Paket Yöneticileri Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-package-managers) – Paketleri ve yöneticilerini kapsar.
- [Test Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-testing) – Test hakkında bir yanlışlar listesi oluşturma girişimi.
- [Arama Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-search) – Aramanın (analiz, tokenleştirme, vurgulama dahil) neden aldatıcı derecede karmaşık olduğu.
- [Her yazılım mühendisinin arama hakkında bilmesi gerekenler](https://github.com/kdeldycke/awesome-falsehood#what-every-software-engineer-should-know-about-search) – Arama motorları uygulamanın zorluğu hakkında daha iyi kaynaklandırılmış bir makale.
- [Sayfalandırma Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-pagination) – Sayfalandırma algoritmanız neden birine (muhtemelen size) baş ağrısı veriyor.
- [Çöp toplama hakkında yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-garbage-collection) – Çöp toplamanın öngörülebilirliği ve performansı hakkındaki yanlış anlamalar.
- [Dosya Yolları Hakkındaki Mitler](https://github.com/kdeldycke/awesome-falsehood#myths-about-file-paths) – Dosya sistemlerinin ve işletim sistemlerinin çeşitliliği dosya yollarını düşündüğümüzden biraz daha zor hale getirir.
- [Windows dosya yollarının tuhaf dünyası](https://github.com/kdeldycke/awesome-falsehood#the-weird-world-of-windows-file-paths) – “Unix türevi herhangi bir sistemde yol hayranlık uyandıracak kadar basit bir şeydir: / ile başlıyorsa, bir yoldur. Windows'ta öyle değil.”
- [/dev/urandom hakkındaki mitler](https://github.com/kdeldycke/awesome-falsehood#myths-about-devurandom) – /dev/urandom ve /dev/random hakkında tekrar tekrar söylenen birkaç şey vardır. Bunlar hâlâ yanlıştır.
- [Durum Makineleri Hakkında Gerçekler](https://github.com/kdeldycke/awesome-falsehood#facts-about-state-machines) – Durum makineleri sıklıkla yanlış anlaşılır ve yetersiz uygulanır.
- [Merhaba! Benim adım…](https://github.com/kdeldycke/awesome-falsehood#hi-my-name-is) – Bu konuşma, kullanıcı adları (ve diğer tanımlayıcılar) hakkındaki yanlışlar olarak da adlandırılabilirdi.
- [mtime hakkındaki yaygın yanlış anlamalar](https://github.com/kdeldycke/awesome-falsehood#popular-misconceptions-about-mtime) – Dosyanın mtime karşılaştırmasının neden zararlı kabul edilebileceğine dair bir yazının parçası.
- [Otomatik Tamamlama için Kurallar](https://github.com/kdeldycke/awesome-falsehood#rules-for-autocomplete) – Tam olarak yanlışlar değil, yine de otomatik tamamlama uygulamak için harika bir iyi uygulamalar listesi.
- [Kayan Noktalı Matematik](https://github.com/kdeldycke/awesome-falsehood#floating-point-math) – “Diliniz bozuk değil, kayan noktalı matematik yapıyor. (…) Bu yüzden, çoğu zaman 0.1 + 0.2 != 0.3.”
- [Cehennemden gelen yaml belgesi](https://github.com/kdeldycke/awesome-falsehood#the-yaml-document-from-hell) – YAML, kazara sayılar ve string olmayan anahtarlar gibi anlaşılması güç karmaşıklıklarla doludur.
- [İçerik etiketleme sistemlerine sonsuz hayranlık duyuyorum](https://github.com/kdeldycke/awesome-falsehood#i-am-endlessly-fascinated-with-content-tagging-systems) – Sade bir yapıda olması beklenen etiketleme sistemlerinde bile uç durumlar vardır.
- [Olay Güdümlü Sistemler Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-event-driven-systems) – Olay güdümlü sistemler ve mesaj iletimi hakkındaki yanlış anlamalar.
- [Dijital Nesne Tanımlayıcıları (DOI) Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-digital-object-identifiers-dois) – Araştırma çıktılarını (ve pek çok başka şeyi) tanımlamak ve bağlamak için kullanılan tanımlayıcılar hakkındaki yanlış kavrayışlar.
- [CVE Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-cve) – CVE ≠ güvenlik açığı (ve diğer 36 karışıklık).

### Ulaşım

- [Havacılık Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-aviation) – Havacılık verileri düşündüğünüzden daha az normalize edilmiştir.
- [Havayolu Koltuk Haritaları Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-airline-seat-maps) – Havayolu koltuk haritaları düzgün sıra ve sütunlardan çok daha karmaşıktır.
- [Havalimanı Kodlarının Çıldırtıcı Karmaşası](https://github.com/kdeldycke/awesome-falsehood#the-maddening-mess-of-airport-codes) – Tarihi, pratikliği ve lojistiği uzlaştırmaya çalışan birden fazla uluslararası ve ulusal kurumun olması, kodların gizemli kurallara uymasına neden olur.
- [Adım herhangi bir rezervasyonda soruna neden oluyor!](https://github.com/kdeldycke/awesome-falsehood#my-name-causes-an-issue-with-any-booking) – Eski havayolu rezervasyon sistemleri MR ekini Mister olarak değerlendirir ve düşürür.

### Tipografi

- [Fontlar Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-fonts) – Web'de ve masaüstü uygulamalarda tipografi hakkındaki varsayımlar.
- [Programcıların harf büyüklüğü hakkında bilmesi gereken doğrular](https://github.com/kdeldycke/awesome-falsehood#truths-programmers-should-know-about-case) – Harf büyüklüğü (büyük ve küçük harf metin) konusunda yanlışlar formatının tam tersi.

### Video Oyunları

- [Kapı Problemi](https://github.com/kdeldycke/awesome-falsehood#the-door-problem) – Oyunlarda kapılarınız için uygulamayı düşünmediğiniz tüm şeyler.

### Web

- [HTML Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-html) – “Web güzeldir. Web çirkindir. Web şaşırtıcıdır. Bu çekiciliğin bir parçası da tarihsel tuhaflıklarıyla HTML'dir.”
- [REST API'leri Hakkında Yanlışlar](https://github.com/kdeldycke/awesome-falsehood#falsehoods-about-rest-apis) – API'ler oluştururken ve belgelendirirken dikkat edilmesi gereken tuzaklar.
- [URL'ler: Karmaşık…](https://github.com/kdeldycke/awesome-falsehood#urls-its-complicated) – Bir URL'de birçok bileşen vardır ve hepsinin kendi mantığı vardır.
- [Favicon İndirmenin Gizli Karmaşıklığı, 15+ Uç Durumda Anlatılıyor](https://github.com/kdeldycke/awesome-falsehood#the-hidden-complexity-of-downloading-favicons-told-in-15-edge-cases) – Tarayıcı sekmelerinde gördüğünüz o küçük simgeyi indirmek basit bir egzersiz olmalı. Düşündüğünüzden çok daha karmaşık çıktı. Bir Yak tıraşlamadığınızdan emin olun.

## Katkıda Bulunma

Katkılarınız her zaman memnuniyetle karşılanır! Lütfen önce [katkı yönergelerine](https://github.com/kdeldycke/awesome-falsehood/blob/main/contributing.md) bir göz atın.

## Dipnotlar

Bu liste son birkaç yıldır sosyal medyada popülerlik kazandı. [Başka yerlerde tartışıldığını ve anıldığını](https://github.com/kdeldycke/awesome-falsehood#social-media) görebilirsiniz.

Başlık görseli, Şubat 2010'da Iza Bella tarafından çekilmiş, Creative Commons BY-SA 2.0 UK lisansı altında dağıtılan değiştirilmiş bir fotoğrafa dayanmaktadır.

[1]: Notebooks, 1914-1916 (Liveright, 2022) - kaynak: sayfa 14e. [↑]



