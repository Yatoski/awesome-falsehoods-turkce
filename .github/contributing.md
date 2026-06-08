# Katkıda Bulunma

Katkılarınız her zaman memnuniyetle karşılanır! İşte bazı yönergeler.

Durum
Bu depo bir denge durumuna ulaşmıştır. Biriktirme aşamasını geride bıraktık ve seçki sürecinin ortasındayız. Bu, kavramları rafine etmek, ilerlemeyi yumuşatmak ve yeni içerik eklemeyi özenle değerlendirmekle daha çok ilgilendiğimiz anlamına gelir.

Pull-request ve konular (issues)
Yeni bir tane oluşturmadan önce önceki öneriler için mevcut ve geçmiş konuları ve pull-request’leri arayın. Sizinki bir tekrar veya devam eden bir çalışma olabilir.

Commit başına yalnızca bir liste öğesi.

Pull-request başına yalnızca bir commit. Değişiklikleri uyguladıktan sonra commit’leri her zaman squash’layın.

Yazım ve dilbilginizi kontrol edin.

Bağlantı verdiğiniz kaynağın neden harika olduğunu ve mevcut külliyata ne kattığını ekleyin.

GitHub depoları şu temel ölçütleri karşılamalıdır:

En az 50 yıldız. Bilinmeyen projeleri elemek için asgari bir ilgi sinyali.

Arşivlenmemiş olması. Arşivlenmiş depolar, yazarın yoluna devam ettiğini gösterir.

Son 3 yıl içinde güncellenmiş olması. 3 yıldan uzun süredir push yapılmamış depolar bayat kabul edilir.

Bunlar varsayılanlardır, mutlak değildir. Yürütücüler, içeriğin niteliğine bağlı olarak istisnalar yapabilir. Statik kaynaklar (okuma listeleri, denemeler, yanlış makaleleri, veri setleri) değerli kalmak için düzenli commit’lere ihtiyaç duymaz. Topluluk tarafından yüksek kabul görmüş arşivlenmiş depolar hâlâ referans olarak kullanılabilir. Buna karşılık, etkin yazılım projeleri her üç ölçüt için de daha sıkı beklentilere tabidir.

Çeviri içeriğini teklifinizle güncel tutun. Değişiklikleri tüm readme.*.md dosyalarına yayın. Otomatik çeviri araçlarından yararlanın. İki dilli katkıcılar sonucu daha sonra düzeltecektir.

Lint’leme
Pull-request’iniz resmî Awesome List linter’ından geçmelidir.

Burada ek bir iş gerekmez, çünkü zaten GitHub actions aracılığıyla entegre edilmiştir.

Yine de, aşağıdaki komutla linter’ı yerelde çalıştırarak sorunları önceden görebilirsiniz:

shell
$ npx awesome-lint
Biçimlendirme
Aşağıda awesome-lint CLI tarafından kapsanmayan ek kurallar bulunmaktadır.

Bu kurallardan biri linter ile çelişirse, linter’ın kuralı öncelikli olur. Onu uygulayın.

Genel içerik
Sondaki boşlukları kaldırın.

Girinti için sekme değil, boşluk kullanın.

Kesme işaretleri tek ASCII işareti kullanmalıdır: '.

Açıklama için, orijinal içerikten en iyi tek alıntıyı belirlemeye çalışın.

Özet işlevi görecek bir alıntı bulunamazsa, maddenin hem başlığını hem de açıklamasını kendi cümlelerinizle yazmaktan çekinmeyin. Unutmayın, bu bir seçkidir: orijinal içeriğin değerini kümeleme, kategorilere ayırma ve akıllı editoryal düzenlemeyle artırıyoruz. Yalnızca orijinal içeriğin ruhuna saygı duymanız yeterlidir.

Bölümler
Bölümler alfabetik sıraya göre kasıtlı olarak sıralanmamıştır. Bu, genelden özel konulara bir ilerleyiş sunmak içindir.

Önemli

İstisna olarak awesome-falsehood listesinde bölümler alfabetik sıradadır, çünkü tüm konular birbirinden bağımsızdır.

Bölümler bir paragraflık giriş ve bir görsel (grafik, çizim, fotoğraf) içerebilir.

URL
Mümkünse HTTPS protokolü kullanın.

CI/CD işleri tarafından erişilebilir olmalıdır. Alan adı hız sınırlama veya içerik koruması nedeniyle 40x hataları döndürüyorsa, kararlı bir bağlantı ile değiştirin:

Araştırma makaleleri için sci-hub.st

Haber makaleleri için archive.ph

Diğer her şey için archive.org

Bazı platformlar içeriği kimlik doğrulamasının ardına koyar ve anonim trafiğe 403 döndürür (Quora, çoğu sosyal ağ tartışması, arşiv kopyası olmayan ücretli haber siteleri): bunları kullanmayın, alternatif bir kaynak bulun.

Bir GitHub deposu yeni bir sahibe devredildiğinde, yönlendirmeye güvenmek yerine URL’yi yeni asıl konuma güncelleyin (eski SAHIP/REPO ad alanı herkes tarafından geri alınabilir, bu da bağlantının alakasız bir içeriğe işaret etmesine yol açar).

Bir satıcı blogu kaybolduğunda (satın alma, yeniden markalaşma, kullanımdan kaldırılan alt alan adı), orijinal URL’yi https://web.archive.org/web/<YYYYMMDDhhmmss>/ ile sarın, bulanık bir yıl ön eki yerine: belirli bir zaman damgası, istek anında Wayback’in en yakın anlık görüntüyü seçmesine bırakmaktan daha kalıcıdır.

Madde başlığı
“ ve ” eğri tırnak işaretleri kullanılmaz. Bunlar, açıklamalarda orijinal içerik alıntıları için ayrılmıştır.

Alıntı yapmak için ya tek ' ya da çift " varyasyonları kullanın. Bunları düzgün biçimde dengeli tutun.

Önemli

awesome-falsehood listesinde, bağlantı başlıklarındaki "Programcılar ... inanır" kısmı, listeyi derli toplu tutmak için çıkarılmalıdır.

Madde açıklaması
Açıklama olarak, kendi başına anlamlıysa orijinal metinden alıntı yaparak eyleme dönük bir TL;DR sunmaya çalışın.

Açıklamadaki TL;DR: ön ekini kaldırın. Zaten her açıklama kısa bir özettir.

Alıntılar “ ve ” eğri tırnak işaretleriyle düzgün biçimde sınırlandırılmalıdır.

Parantez içinde üç nokta (…) kullanarak orijinal metni kısaltabilirsiniz.

Alıntı içinde alıntı için tek ' veya çift " ASCII işaretlerini kullanın. Bunları düzgün biçimde dengeli tutun.

Bir listeyi açıklamaya dönüştürmek için şu biçimi kullanın:

Maddeyi özetleyen bir açıklama metni. Ve işte orijinal içerikten gelen “üç önemli konu: 1. Falan filan; 2. Falan filan? 3. Falan filan.” hakkında bir liste. Ve sonuca bağlayan biraz daha metin.

Bu biçim, okunabilirliğe ve hızlı içerik taramasına yardımcı olan görsel dayanak noktaları sağlar.

Orijinal listedeki bazı maddeleri atlayabilir ve yeniden numaralandırabilirsiniz.

Ancak yeniden sıralama yapmamalısınız.

Açıklamada ek bir bağlantıya izin verilir. Bu, daha büyük bir kavrama, bir kısaltma tanımına veya referans materyale (kitap, biyografi, …) işaret etmek gibi ender durumlarla sınırlı olmalıdır.

Lisans işaretleyicileri
Araç, veri seti ve proje girdileri için, okuyucuları projenin ticari duruşu hakkında bilgilendirmek amacıyla açıklamanın başına iki emoji’den birini ekleyin. Makaleler, bildiriler, blog yazıları, haber öğeleri ve seçki listeleri işaretlenmez.

💸 — projenin birincil yürütücüsü, bu yazılımın ücretli bir sürümünü satan ticari bir satıcıdır: barındırılan bulut, Enterprise katmanı veya OSS çekirdeğinin üzerine özel modüller. İşaretleyici bilgilendirme amaçlıdır, bir kalite yargısı değildir: okuyucuya bazı gelişmiş özelliklerin (uyumluluk, denetim günlüğü saklama, çok kiracılı eklentiler, entegrasyonlar) OSS dağıtımının dışında kalabileceğini söyler. Satıcı yalnızca destek, SLA veya özellik kısıtlaması olmaksızın yönetilen barındırma satıyorsa (örneğin Keycloak için Red Hat) uygulamayın.

🆓 — proje, özellik kısıtlaması yoluyla değer elde eden bir ticari satıcı olmaksızın tamamen açık kaynaklıdır: vakıf yönetiminde (CNCF, Apache Software Foundation, Eclipse), topluluk güdümlü, yanında ücretli bir ürün olmadan yayınlanmış kurumsal-OSS (Lyft’in Cartography’si, Yahoo’nun Athenz’i, Salesforce’un Policy Sentry’si, Microsoft’un Presidio’su) veya yalnızca destek sözleşmeleriyle satılan (Keycloak için Red Hat).

Biçim: - [Proje](url) - 💸 Açıklama. veya - [Proje](url) - 🆓 Açıklama.. İki işaretleyici birbirini dışlar: bir proje ya birini ya diğerini alır, asla ikisini birden değil. Awesome-lint bu biçimi değişmeden kabul eder.

Editoryal çizgi
Her listenin genel editoryal çizgisi, giriş kısmında ima edilmiştir.

Ayrıca listeye bağlı bazı özel kurallar da vardır:

awesome-engineering-team-management: madde sırası
Maddeler kabaca şöyle sıralanır:

Önce yazılım geliştiricilere veya yeni yöneticilere hitap eden içerikler bulunur. Erişilebilirliği hedefler, daha geniş kitleye seslenir ve yumuşak bir giriş sunar.

Ardından konuyu daha uygulamalı ve ilişkilendirilebilir kılan birkaç gerçek kullanım örneği veya anekdot yer alabilir.

Üçüncü olarak, kavramları genelleştirmek, yöntemli çözümler sunmak ve daha geniş düşünme çerçevelerini ortaya koymak için birkaç referans materyal eklenebilir.

En sonda, uyarıcı öyküler veya kötüleşen koşulların işaret fişekleri olarak yararlı olan en alaycı veya karamsar içerik gelir.

awesome-falsehood: adaylar
Katkıda bulunmadan önce, eklemek istediğiniz yeni bağlantının iyi bir aday olduğundan emin olun.

Aşağıda, awesome-falsehood listesine dahil edilmek için iyi aday olan maddelerin sınırlayıcı olmayan bir listesi bulunmaktadır.

Yanlış makaleleri
Yanlış şemasını takip eden makaleler, bu harika listeye dahil edilmek için başlıca adaylardır.

Bu makaleler, geliştiricilerin bir alan hakkında saf ve basit bir görüşe sahip olduğu hipoteziyle başlar. Ardından programcıların sahip olabileceği bir dizi içten varsayımı sıralar. Her biri kasıtlı olarak yanlıştır ve en iyi biçimlerinde bir karşı örnekle resmedilir.

Bir yanlış listesi, kavramları rafine etmek üzere tasarlanmış bir ilerleyiş olarak kurgulanır. Listenin tamamını okuduktan sonra okuyucu, bir alanın mitlerini çürütürken daha iyi bir genel bakışa sahip olmalı, yaygın tuzaklara işaret etmeli ve inceliklerini göstermelidir.

Yanlış makaleleri, bir anlamda, gerçek dünya kullanımından gelen kapsamlı uç durumları kapsayan ayrıntılı birim testleri süitidir. Dünya dağınıktır. Bir alanın sanıldığından çok daha karmaşık olduğunu keşfetmek hayal kırıklıklarına ve masa devirmelere (╯°□°)╯︵ ┻━┻ yol açacaktır. Bu, liste için harika bir adayın işaretidir!

Yalnızca bir ürüne (ya da hizmete) özgü maddeler içeren makaleler yeterince genel sayılamaz ve kaçınılmalıdır.

Kütüphaneler
Yukarıdaki yanlış makalelerinin işaret ettiği karmaşıklıkları çözen veya azaltan programlama kütüphaneleri veya modülleri de iyi adaylardır.

Böylece masaları tekrar yerine koyabiliriz. ┬─┬ ノ( ゜-゜ノ)

Veri yapıları
Çoğu yanlışı kapsayacak ve ele alacak kadar genel veri modelleri ve yapıları da bu sayfada memnuniyetle karşılanır.

SSS
Seçki sürecini örneklemek için bazı durumlar.

Cümlelerinizi ve paragraflarınızı yeniden yazabilir miyim?
Evet. Ana dili İngilizce olmayan biriyim, bu yüzden yazdıklarımın bazıları biraz süslü olabilir. İlk metnimin daha kısa, öz ve doğru bir versiyonunu önerebilirseniz, yapın! Bu iyileştirmeler her iki okuyucu türü için de okunabilirliği büyük ölçüde artırır.

Listeye YouTube videoları önerebilir miyim?
Evet, ancak videonun başlangıcını ilgili bir zamana işaretlemeye çalışın. YouTube URL’lerindeki &t=13m30s parametresinde olduğu gibi.

Videodan daha iyisi: yazılı transkripsiyonunun bir bağlantısı. Ya da sunulan noktayı sulandırmıyorsa sunum slaytları.

Bir X (Twitter) dizisine bağlantı verebilir miyim?
Evet, ancak önce yazarın ürettiği içerikte arama yapmaya çalışın: bazen yazar, söylemini daha sindirilebilir bir makaleye dönüştürmüş olabilir. Ona bağlantı vermeyi tercih ederiz.

Bağlantı çürümesini nasıl önleyebilirim?
Bir katkıcının işaret ettiği gibi:

Buradaki bağlantıların çevrimdışı olma eğilimi var. Bunun uzun vadeli değere sahip bir kaynak olması için, sayfaları arşivleyerek bağlantı çürümesi önlenebilir.

Bu doğrudur.

Orijinal URL artık erişilemez durumdaysa, alternatif bir arşivlenmiş/önbelleğe alınmış bağlantı ile değiştirmekte bir sakınca görmem.

Kırık URL’ler sinir bozucudur. Onları tek tek düzelteceğiz. Bazıları yeni bir alan adına taşındı. Bazıları tamamen kayboldu, bu yüzden onları arşivlenmiş bir bağlantı ile değiştireceğiz.

Kırık bir bağlantı bulursanız, lütfen düzeltmek için bir PR önerin. Ya da sadece bir konu (issue) olarak bildirin, ben işi yapayım.

Çevrimdışı olan makaleleri nasıl arşivleyeceksiniz?
Bu soru, onları çevrimdışı olmadan önce arşivlememiz gerektiği paradoksuna işaret eder.

İçeriği önleyici olarak arşivlemek için acele yoktur. Başkalarının bunu yapması için teşvikler mevcuttur:

Bu liste, içeriğinin düzenli arşiv tarayıcıları tarafından alınmasına yetecek kadar popülerdir.

Listedeki popüler içerik, onlara değer veren kullanıcılar tarafından doğal olarak arşivlenir.

İçeriğini önemseyen veya bu listenin sağladığı SEO suyundan yararlanan yazarlar, onları orijinal URL’lerinde erişilebilir tutmak için bir teşviğe sahiptir.

Bu teşviklere rağmen, içeriğin hiçbir arşiv kopyası olmaksızın web’den tamamen kaybolma ihtimali sıfırdan büyüktür. Bu dünyanın sonu değildir. Belki de içerik buna değmezdi ve ilk etapta dahil edilmeye uygun değildi. Bu uç durumu, içerik üzerinde doğal bir seçilim süreci olarak düşünün; bu da doğal seçkiye yardımcı olur.

Neden etkin olmayan GitHub projeleri kaldırılıyor?
Bakımı yapılmayan GitHub depoları genellikle sahipleri tarafından arşivlenir. Ancak bazıları fiilen bakımsızdır veya yazarı tarafından açıkça arşivlenmeden olduğu gibi terk edilmiştir.

Her iki durumda da, ele aldıkları alan kalabalıksa ve listede başka depolar referans verilmişse, bağlantı gürültüyü azaltmak için silinmeye iyi bir adaydır.

Öte yandan, proje başka bir yerde çatallanmış veya yeniden başlatılmışsa, artık yeni konuma işaret edebiliriz.

Ticari projem neden listede yok?
Muhtemelen temel içerik bir ödeme duvarının arkasında olduğu için. Özellikle çevrimiçi olarak daha kapsamlı ve ücretsiz erişilebilen daha iyi kaynaklar varsa.

Bu, özellikle SaaS ve diğer lisanslı yazılımlar için geçerlidir. Açık kaynaklı bir proje mevcutsa, ticari çözümler yerine onu işaret etmeyi tercih ederiz.

Bu alternatiflerin daha iyi olması gerekmez. İlham alınabilecek kadar iyiyseler veya giriş engeli olmaksızın bir şey başlatıyorlarsa yeterlidir.

Dolayısıyla, örtüşen birden fazla projenin olduğu bir kümede, ticari olanları tekrar olarak değerlendirip listeyi sade tutmak için kaldıracağız.

Ayrıca bkz. Açık kaynaklı projem neden kaldırıldı? — proje teknik olarak açık kaynak olsa bile geçerli olan ağır-açık-çekirdek modeli için.

Açık kaynaklı projem neden kaldırıldı?
GitHub deposundaki izin verici bir lisans yeterli değildir. Projenin ödeme yapmadan üretimde gerçekten kullanılabilir olup olmadığını da değerlendiririz. Filtrelediğimiz model ağır-açık-çekirdektir: temel özellikleri ücretli bir Enterprise katmanı veya barındırılan bir Cloud eklentisinin arkasına kilitleyen bir OSS kabuğu sunan proje.

Temel özellik sayılan şey listenin alanına bağlıdır. Bir kimlik doğrulama veya erişim yönetimi projesi için MFA, SSO protokolleri (SAML, OIDC, LDAP federasyonu), çok kiracılılık, ince taneli izinler, SCIM/dizin senkronizasyonu, denetim günlükleri ve yönetici kullanıcı arayüzü temeldir. Bir veri araçları projesi için eşdeğer çekirdek yetenekler temeldir. Her listenin yürütücüsü, alanla ilgili listeyi SSS’inde veya PR inceleme yorumlarında açıklayacaktır.

Bunlardan herhangi biri OSS dağıtımında yoksa, özellik başına eklenti olarak satılıyorsa, ayrı bir özel mülk dizinde (OSS lisanslı olmayan bir ee/ klasörü gibi) tutuluyorsa veya MAU başına fiyatlandırılıyorsa, proje aşırı kalabalık bir bölümde gerçek-OSS alternatiflerinin yanında listelenmeyecektir.

Birlikte değerlendirilen birkaç daha yumuşak sinyal de listelemeye karşı sayılır:

Satıcının fiyatlandırma sayfası, temel özellik gibi görünen şeyleri ücretli katmanlar olarak listeler.

Proje README’si, bulut için ayrılmış “koruyucu bariyer” veya “premium özellikler”den açıkça söz eder.

OSS sürümünü kendi kendine barındırmak, satıcının yalnızca ücretli bir ürün olarak önceden entegre edilmiş halde sunduğu birkaç ayrı ilkeli bir araya getirmeyi gerektirir.

Lisans testini geçen ancak hafif-açık-çekirdek kategorisine giren mevcut girdiler (bazı gelişmiş uyumluluk veya dizin-senkronizasyon entegrasyonları kilitli, ancak çekirdek OSS’de çalışır), belirgin bir nişi kapsadıklarında hâlâ listelenebilir. Bu tür girdiler açıklamada 💸 işaretleyicisi ile belirtilir.

Ayrıca bkz. Ticari projem neden listede yok? — hiçbir OSS dağıtımının olmadığı tamamen ücretli durum için.

Projem neden etkin olmama nedeniyle kaldırıldı?
Arşivlenmiş depolara ek olarak, yazarının resmî olarak kullanımdan kaldırdığı projeleri de kaldırırız: README’de kullanıcıları farklı bir projeye yönlendiren bir bildirim veya “yeni projeler artık buna bel bağlamamalı” şeklinde bir kamu açıklaması, yalnızca GitHub arşiv bayrağından daha güçlü bir sinyal olarak değerlendirilir.

OSS deposunun bakımı-yapılan-ama-geliştirilmeyen (yalnızca Dependabot sürüm yükseltmeleri ve telif hakkı rötuşları, şirketin yol haritasının halef ticari üründe olduğu) durumla sonuçlanan satın almalar da aşırı kalabalık bölümlerde kaldırma gerekçesidir.

Bağlantım neden reddedildi?
Bağlantınız reddedildiyse, bu durum PR’ınıza yorum olarak katkıcıya gerekçesiyle birlikte açıklanmış olmalıdır.

Sıklıkla örtüşen bazı ret nedenleri şunlardır:

Tekrar içerik

Özgünlük eksikliği

Mevcut içeriğin yeniden ısıtılması

Yeni bağlantının mevcut külliyata ne kattığını açıklayan bir motivasyonun olmaması

Daha fazla içeriğe değil, daha fazla seçkiye ihtiyaç duyan aşırı kalabalık bölüm

Yeterince genel olmama veya tek bir ürün ya da şirkete fazla özgü olma

Listeyi SEO için sömüren pazarlama metni

Aynı ticari alan adına işaret eden çok fazla URL (2 bağlantı yeterlidir)

Katkıcının sorulan sorulara geri bildirim vermemesi

Bu katkı yönergelerinden sapma

Davranış kurallarının ihlali

Bir bağlantıyı listeye nasıl zorla sokabilirim?
Katkınız reddedildiyse, seçki kurallarını aşmanın bir yolu vardır. Bir sponsorluk satın alarak ürününüzü, logonuzu ve bağlantınızı bu deponun en üstüne yerleştirebilirsiniz! 🤗 Tıpkı Descope’un awesome IAM listesinde bir yıl boyunca yaptığı gibi.

awesome-falsehood için SSS
Bu sorular Awesome Falsehood projesine özeldir.

Neden yanlışları doğrudan listeye kopyalamıyorsunuz?
Tüm yanlışları depoda derlemek iyi bir fikir olabilir. Topluluğun onları sürdürmesine ve zenginleştirmesine olanak tanırdı. Ayrıca, çoğu harici makale bir yanlışın neden yanlış olduğunu gösterme veya açıklama zahmetine girmediğinden genel kaliteyi de artırabilirdi.

Ancak bu büyük bir çabadır, bu yüzden işleri basit tutmak adına bu listede yalnızca harici makalelerin bir koleksiyonunu yapıyoruz. Bu arada, yanlışlar eklemek isterseniz, potansiyel katkıcılardan bunları başka bir yerde barındırmalarını isteyeceğim.

Ayrıca, ham yanlışları bu depoda barındırmak zorunda kalsaydık, lisansı kontrol etmemiz ve orijinal yazardan izin istememiz gerekebilirdi.





