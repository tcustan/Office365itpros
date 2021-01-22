
https://office365itpros.com/office-365-github-repository/

BT Uzmanları için Office 365 GitHub Deposu
BT Uzmanları için Office 365 e-Kitabının geliştirilmesinin bir parçası olarak veya blog gönderilerinin oluşturulmasını desteklemek için çok sayıda PowerShell komut dosyası yazıyoruz. Kod, işlerin nasıl yürüdüğünü veya görevlerin nasıl gerçekleştirileceğini göstermeyi amaçlamaktadır. Birkaç yıl önce komut dosyalarını GitHub depomuza koymaya başladık . Aşağıdaki uyarıları içeren komut dosyalarını indirip kullanmaktan çekinmeyin:

Bunlar üretime hazır komut dosyaları değildir. Bunları çevrenizde kullanıma hazırlamak için bazı çalışmalar yapmanız gerekecek. Örneğin, herhangi bir hata işleme durumunda komut dosyaları yetersiz gelir. Ayrıca, fonksiyonlarda kod yazma eğiliminde değiliz çünkü herkesi profesyonel programcı olarak eğitmeye çalışmadan işin nasıl yapılacağını göstermeye çalışıyoruz.
İnternetten indirilen PowerShell koduna her zaman güvenmeyin. Kodu test etmeden asla üretimde hiçbir şey çalıştırmayın.
Bir konuyu araştırırken kodu yazıyoruz. Bazen birisinin bize soru sorması gibi, gerekirse geri dönüp kodu yeniden ziyaret ederiz. Bireysel grupları bulmanın en hızlı yolu gibi belirli görevleri gerçekleştirmek için komut dosyalarında her zaman en yeni ve en büyük tekniği kullanmayız. Office 365 for IT Pros eBook'ta programlama önerilerini güncel tutuyoruz .
Artık oyunun kurallarını anladığınıza göre, burada depodaki bazı komut dosyalarının ayrıntıları verilmiştir (kodumuzu geliştirmekten çekinmeyin). BT Uzmanları için Office 365 veya Petri makalesinde bir komut dosyasında gösterilen kavramlar hakkında daha fazla bilgiyi nerede bulabileceğinizi belirttik. Komut dosyalarının çoğuna Office 365 for IT Pros eBook'ta başvurulmaktadır .

Microsoft 365 Grupları Süre Sonu İlkesine Ekip Ekleme
AddTeamstoGroupsExpirationPolicy.ps1 : Bir kiracıdaki tüm ekiplerin Gruplar süre sonu ilkesine nasıl ekleneceğini gösterir.

SendAs Audit Etkinliklerini İzinlere Göre Analiz Edin
AnalyzeSendAsAuditData.ps1 : Hangi izinlerin kullanıldığını ve hangilerinin kullanılmadığını anlamak için paylaşılan ve kullanıcı posta kutularındaki izinlere karşı SendAs eylemleri için oluşturulan denetim kayıtlarını çözümler . Dahafazla bilgi için bu gönderiye bakın.

Microsoft 365 Gruplarını (ve Takımları) Arşivleyin
ArchiveMicrosoft365Groups.PS1 : Microsoft, etkin olmayan Teams'i arşivlemek için bir yönteme sahiptir. Bu komut dosyasında, özel bir arşiv hesabı dışındaki tüm üyeleri kaldırarak grupları bir arşiv durumuna getiren başka bir yaklaşımı gösteriyoruz. Dahafazla bilgi için bu gönderiye bakın.

Bir Kullanıcı için SharePoint Çevrimiçi Etkinliğini Bildirme
AuditSPOOperationsByUser.PS1 : Bu komut dosyası, Office 365 denetim günlüğündeki olayların, bireysel kullanıcılar için SharePoint Online etkinlikleri hakkında bir rapor oluşturmak için nasıl kullanılacağını gösterir (belge oluşturma ve düzenleme, dosya paylaşma vb.). Dahafazla bilgi için bu gönderiye bakın.

Kısmen İndekslenmiş Öğeleri Analiz Et
ComplianceSearchParticallyIndexedItems.ps1 : Office 365'e yüklenen belgeler ve dosyalarla dizin oluşturmanın ne kadar iyi olduğunu anlamak faydalıdır. Bu, bir kiracıdaki kısmen dizine alınmış öğeleri analiz etmek için kullanılan bir Microsoft komut dosyası sürümüdür. Dahafazla bilgi için bu gönderiye bakın.

Exchange Dağıtım Listesini Microsoft 365 Grubuna Dönüştür
ConvertDLtoO365Group.PS1 : Bu komut dosyası, bir Exchange Online dağıtım listesini Microsoft 365 Grubuna dönüştürür. Listelerin tümü dönüştürülemez ve bu, işin nasıl yapılacağına dair mükemmel bir örnek değildir, ancak işe yarar.

Korumalı SharePoint Online Belgelerinin Şifresini Çözme (Grafik Sürümü)
DecryptProtectedSPODocuments-Graph.PS1 : Bu komut dosyası, bir SharePoint belge kitaplığındaki korumalı (şifrelenmiş) belgeleri bulmak ve atanmış duyarlılık etiketini kaldırarak bunların şifresini çözmek için PowerShell ve Microsoft Graph API çağrılarının bir karışımının nasıl kullanılacağını gösterir.

Korumalı SharePoint Online Belgelerinin Şifresini Çözme (PnP Sürümü)
DecryptProtectedSPODocuments.PS1 : Komut dosyasının bu sürümü, daha sonra şifresi çözülen SharePoint kitaplığındaki belgeleri bulmak için SharePoint PnP modülünün nasıl kullanılacağını gösterir. Grafik sürümü (yukarıda) daha güçlüdür, ancak işi bu yapar. Kod, bu makalede örnek olarak kullanılmıştır.

Service Communications API'den Mesajları Alın
FetchServiceMessagesGraph.ps1 : Yeni güncellemeler ve iş yüklerindeki değişiklikler için bir hizmet bildirimleri raporu (Microsoft 365 mesaj merkezine gönderilen tür) oluşturur. Veriler, Service Communications API kullanılarak alınır.

Gönderme ve Arama Kayıtlarını Bulun
FindCrucialSendAndSearchRecords.PS1 :Office 365 for IT Pros eBook'un 21. Bölümünde kullanılan Search-UnifiedAuditLog cmdlet'inikullanma örnekleri.

Etkin Olmayan Dağıtım Listelerini Bulun
FindInactiveDLs.PS1 : Dağıtım listelerinin etkin kullanımda olup olmadığının nasıl kontrol edileceğine dair bir örnek. Exchange Online tarafından depolanan mesaj izleme verileri, bir dağıtım listesinin etkin olup olmadığını kontrol etmek için kullanılır (mesaj izleme verilerinin çevrimiçi olarak ne kadar uzun süreyle mevcut olduğu, son 10 günde kullanıldığı şekilde tanımlanır). Dahafazla bilgi için bu gönderiye bakın.

Erişilen Posta Öğelerini Rapor Et Denetim Kayıtları
FindMailItemsAccessedAuditRecords.PS1 : Microsoft, MailItemsAccessed'i yüksek değerli bir denetim olayı olarak tanımlar. Exchange Online, bir posta kutusu için bu olayları günlüğe kaydetmeden önce hesapların Office 365 E5 lisanslarına ihtiyacı vardır. Bu komut dosyası, denetim günlüğü verilerini çıkarır ve MailItemsAccessed olayları için rapor eder. Dahafazla bilgi için bu gönderiye bakın.

Etkinliğe Göre Etkin Olmayan Misafir Hesaplarını Bulun (V1)
FindObsoleteGuestsByActivity.ps1 : Kiracılarda oluşturulan konuk hesaplarının sayısı göz önüne alındığında, hesaplara göz kulak olmak ve kullanılmayanları kaldırmak iyi bir fikirdir. Bu komut dosyası, misafirlerin belgelere erişip erişmediğini veya e-posta alıp almadığını anlamak için denetim verilerini ve mesaj izleme verilerini kullanır; bu, hesapların etkin olup olmadığını anlamanıza yardımcı olabilir. Dahafazla bilgi için bu gönderiye bakın.

Etkinliğe Göre Etkin Olmayan Misafir Hesaplarını Bulun (V2)
FindObsoleteGuestsByActivityV2.ps1 : Konuk hesabının yaşıyla bir karşılaştırma içeren ve misafirin hangi Microsoft 365 Gruplarına ait olduğunu kontrol eden orijinal komut dosyasının daha gelişmiş bir sürümü. Misafir, yalnızca hesap 365 günden daha eski ise işaretlenir (kolayca ayarlanabilir). V1 yerine bu sürümü kullanın.

Bir Hassasiyet Etiketi Konuk Erişimini Engellediğinde Misafirlerle Microsoft 365 Gruplarını Bulun
FindOffice365GroupsWithBadGuests.PS1 : Konuk erişimini engelleyen bir gruba, ekibe veya siteye bir duyarlılık etiketi uygulayabilirsiniz, ancak eylem, halihazırda grup üyeliğinde olan konukları kaldırmak için hiçbir şey yapmaz. Bu komut dosyası, misafir erişimini engelleyen etiketlere sahip gruplar halinde misafirleri tarar ve bulduklarını bildirir. Dahafazla bilgi için bu gönderiye bakın.

Bir Yıldan Eski Misafir Hesaplarını Bulun
FindOldGuestUsers.ps1 : Bir kiracıdaki tüm konuk hesaplarını taramak ve bir yıldan eski olanları rapor etmek için bir komut dosyası. Rapor, konuk hesabının ait olduğu grupların adlarını içerir. Dahafazla bilgi için bu gönderiye bakın.

Yetim OneDrive İş Hesaplarını Bulun
FindOrphanOneDriveSites.PS1 : Azure AD tarafından bilinen hesaplara ait olmayan hesapları bulmak için kiracıdaki OneDrive İş hesaplarını tarayan bir komut dosyası. Herhangi bir sahipsiz hesap bulunursa, bunlar, daha sonra hesaplarda depolanan içeriği açmak ve incelemek için kullanılabilen bir aday hesaba atanır. Dahafazla bilgi için bu gönderiye bakın.

Azure Active Directory'de Olası Sorunları Bulun (kiracı için)
FindPotentialDirectoryProblems.PS1 : Bu komut dosyası, Azure Active Directory'yi tarayarak ortak özniteliklere (telefon numaraları veya departmanlar gibi) sahip olmayan hesapları arar. Buradaki fikir, Kişi Kartı ve diğer Microsoft 365 özelliklerinin büyük ölçüde doğru Azure AD verilerine bağlı olmasıdır, bu nedenle temel bilgilerin tüm hesaplar için yapıldığından emin olmak iyi bir fikirdir. Dahafazla bilgi için bu gönderiye bakın.

Geçen Hafta Ekiplere Eklenen Yeni Konukları Bul ve Rapor Et (E-postayla)
FindReportGuestsAddedTeams.PS1 : Bu komut dosyası, geçen hafta Teams'e eklenen konuk hesaplarının ayrıntılarını bulmak için Office 365 denetim günlüğünü arar (tarih aralığı bir değişken ayarlanarak yapılandırılabilir). Herhangi bir misafir bulunursa, yeni misafir hesabı olup olmadıkları kontrol edilir. Eğer öyleyse, ayrıntıları, eklemenin gerçekten gerekli olup olmadığını (veya istediğiniz başka bir metni) sormak için konuğu ekleyen kişiye e-posta ile gönderilir. Ayrıntılar için bu gönderiye bakın.

SendAs İzni Kullanılarak Gönderilen İletileri Rapor Et
FindSendAsAuditRecords.ps1 : Bu komut dosyası, kişiler paylaşılan posta kutularından veya temsilci erişimine sahip oldukları diğer kullanıcı posta kutularından ileti göndermek için SendAs posta kutusu iznini kullandıklarında günlüğe kaydedilen denetim kayıtlarını bulur. Bir posta kutusundan bu mesajı kimin gönderdiği sorusuna cevap vermek oldukça sık bir taleptir ve bu bir çözümdür.

ReportSendAsAuditEvents.PS1 : grup posta kutuları için SendAs olaylarının ayrıntıları da dahil olmak üzere konuyla ilgili başka bir yaklaşımdır. Bu makale , bu denetim olaylarını Exchange Online'da bildirmek için şirket içi yerine neden farklı bir yaklaşımın gerekli olduğunu açıklar.

Teams'e Yüklenen Rapor Uygulamaları ve Sekmeleri
FindTabsAndAppsInTeams.ps1 : Bir kuruluştaki her ekipte kanallarda yüklü sekmeleri ve uygulamaları bulmak üzere Teams için Graph API'nin nasıl kullanılacağını gösteren bir komut dosyası. Bu senaryoyu bir organizasyonda çok sayıda ekibin nasıl işleneceğinin bir göstergesi olarak yazdık. Dahafazla bilgi için bu gönderiye bakın.

Güncellenen Servis Bildirimlerini Bildirin
FindUpdatedOffice365Notifications.ps1 : 2020'nin ikinci yarısında, Microsoft'un uzun süredir gönderilmeyen bir grup Teams özelliğini duyurduğu yönünde bir teori geliştirildi. Teoriyi test etmek (ve bu makaleyi yazmak) için, Microsoft 365 mesaj merkezine gönderilen bildirimleri almak için bir komut dosyası oluşturduk ve gecikmenin ne kadar olduğunu bilmek için orijinal duyuru tarihini güncelleme tarihiyle karşılaştırarak güncellemeleri aradık.

Anonim (Herkes) Paylaşım Bağlantılarının Kullanımını Bildirin
FindWhenAnonymousLinkUsed.ps1 : Anonim (herkes) bir paylaşım bağlantısı oluşturulduğunda ve kullanıldığında günlüğe kaydedilen denetim olaylarını ayıklamak için bir komut dosyası. Dahafazla bilgi için bu makaleye bakın.

Microsoft 365 Gruplarına ve Ekiplerine Kimin Eklediğini Bildirin
FindWhoAddedGuestsToGroups.ps1 : Bir Microsoft 365 grubuna (veya ekibine) yeni konuk üyeler eklendiğinde yakalanan kayıtları bulmak için Office 365 denetim günlüğünde arama yapan bir komut dosyası.

SharePoint Paylaşımı Üzerinden Konuk Ekleyenleri Rapor Edin
FindWhoCreatedGuestsThroughSPOSharing.ps1 : Konuklar bir SharePoint Online belgesi paylaşılarak kiracıya eklenebilir. Bu komut dosyası, son 90 gün içinde SharePoint paylaşımı tarafından eklenen tüm misafirleri, paylaşılan belgeyle birlikte bildirir.

Ekip Dizini Oluşturun
GenerateTeamsDirectory.ps1 : Teams, bir organizasyon içindeki ekiplerin dizinini yayınlamaz. Bu komut dosyası, kullanıcılara verilebilecek Takımların bir listesini oluşturur. Daha büyük kuruluşlarda, Get-Team çağrısını Teams Graph API ile değiştirmek en iyisidir. Komut dosyası bu makalede yer aldı.

Ekipler ve Gruplar için Azure AD Access İncelemelerinin Ayrıntılarını Alın
GetAzureADAccessReviewDetailsGraph.PS1 : Tüm Microsoft 365 Grupları ve Ekipleri için bir Azure AD Access İncelemesinin ilerlemesini analiz etmek için bir komut dosyası. Gözden geçirilmesi gereken grupların sayısı, reddetme ve onaylama kararlarının sayısı ve alınacak kararların sayısı ile birlikte rapor edilir.

Teams Özel Arka Planları için Bing Görüntülerini Alın
GetBingImagesTeamsBackgrounds.PS1 : Bing, ana sayfasının arka planı olarak kullanmak için günlük olarak güzel görüntüler yayınlar. Aynı görüntüler, Teams toplantıları için genellikle iyi özel arka planlar oluşturur. Bu komut dosyası, Teams özel arka planları için kullanılan klasöre Bing günlük görüntülerini indirip yükler ve 30 gün sonra eski görüntüleri kaldırır. Dahafazla bilgi için bu makaleye bakın.

Graph API ile Kullanıcı İstatistiklerini Raporlayın
Kullanıcı etkinliği hakkında veri ayıklamak ve bir rapor oluşturmak için Grafik etkinliği API'sinin nasıl kullanılacağını göstermek üzere tasarlanmış bu komut dosyasının iki sürümü vardır ( bu makalede açıklanmıştır ). Orijinal GetGraphUserStatisticsReport.PS1 çalışıyor, ancak binlerce kullanıcı hesabı için verileri işlerken oldukça yavaş. İşleri hızlandırmak için birçok şeyi ( bu makaledeki ayrıntılar ) yeniden yazdık ve GetGraphUserStatisticsReportV2.PS1'i ürettik . Aramalar için PowerShell karma tablolarını kullanarak, komut dosyası çok daha hızlıdır ve 30.000 veya daha fazla hesabı (en çok test ettiğimiz) işleyebilir.

Posta Kutusu İçin Yerinde Rapor Muhafazaları
GetHoldsOnMailbox.PS1 : Bir posta kutusunda bulunan muhafaza kümesini yorumlamak ve muhafazaların nereden kaynaklandığını söylemek için Office 365 for IT Pros e- Kitabının 19. Bölümünde başvurulan bir komut dosyası.

Posta Kutuları için Son Etkinlik Zamanlarını Alın
GetLastActiveTimeMailboxes.PS1 :Posta kutuları için son etkinlik tarihini bildirmek için Export-MailboxDiagnosticsLogs cmdlet'itarafından açıklanan verileri kullanmak için bu makalede referans verilen komut dosyasının bir varyasyonu. Get-MailboxStatistics cmdlet'itarafından bildirilen LastLogonDate bulut posta kutuları için çok hatalı olduğuiçin daha doğru etkinlik verilerine ihtiyaç vardır.

Bir Kullanıcı Hesabı için Rapor Planlayıcı Bilgileri
Planner'ın bir Grafik API'si vardır, ancak plan verilerini alabilmek için bir planın üyesi olmanız gerekir. Planner verilerini raporlamak için API'nin nasıl kullanılacağını gösteren iki örnek komut dosyamız var. GetPlansForUser-DeviceCode.PS1 bir cihaz kodu ve temsilci izinleri kullanırken GetPlansForUser.PS1 bunu bir cihaz kodu olmadan yapar. Daha fazla bilgi için bu makaleye bakın .

Güvenlik Uyarılarını Bildir
GetServiceAlertsGraph.ps1 : Güvenlik uyarıları hakkında bilgi almak ve bunları PowerShell'de yorumlamak için Graph Güvenlik Uyarıları API'sini kullanır. Bunu yapmanızın nedenleri bu makalede açıklanmaktadır.

Kullanıcı Oturum Açmalarını Grafikten Rapor Edin
GetUserSignInDataGraph.PS1 : Azure AD'den kullanıcı oturum açma verilerini almak ve bulduğumuzu rapor etmek için bir komut dosyası. Oturum açma etkinliğini anlamak için kullanışlıdır. Hepsi bu Petri.com makalesinde açıklanmıştır.

Misafir Hesapları için Son Oturum Açma Zamanını Analiz Edin
LastLoggedOnByExternalUsers.ps1 : Bir kiracıya konuk kullanıcı bağlantılarını aramak için Office 365 denetim günlüğünde arama yapan bir komut dosyası. Konuk hesaplarına herhangi bir e-posta gönderilip gönderilmediğini keşfetmek için ileti izleme verilerine de bakarız.

Yönetilen Klasör Yardımcısı'nın Posta Kutularını En Son İşlem Yaptığı Zamanı Bildirin
MFAReportMailboxes.ps1 : Exchange Online Managed Folder Assistant (MFA), saklama ilkelerine göre bilgileri kaldırmak için posta kutularını işlemekten sorumludur. MFA, iş döngüsü temelinde çalışır ve posta kutularını haftada en az bir kez işlemelidir. Normalde döngü daha sık işler. Komut dosyası, her bir kullanıcı posta kutusunun en son ne zaman işlendiğini ve MFA tarafından kaç öğenin kaldırıldığını bildirir. Bir posta kutusu yalnızca 10 MB'den fazla kullanıcı verisi tutuyorsa işlenir, bu nedenle bazı kullanıcı posta kutuları işlenmez.

Teams Kanalına Yeni Microsoft 365 Yol Haritası Öğeleri Gönderin
PostNewMicrosoft365RoadmapItems.PS1 : Microsoft 365 yol haritası için RSS beslemesini okumak, yol haritasında bulunan öğeleri paketinden çıkarmak ve son 7 günde (yapılandırılabilir) oluşturulan tüm öğeleri gelen Webhook bağlayıcısını kullanarak bir Teams kanalına göndermek için bir komut dosyası. Dahafazla bilgi için bu gönderiye bakın.

Bir İçerik Arama Eylemi Kullanarak Exchange Online Mesajlarını Temizleme
PurgeMessagesWithContentSearch.PS1 : Microsoft, Arama-Gelen Kutusu cmdlet'inden kurtulmakla meşgul ve bunun yerine, temizlemek istediğiniz öğeleri bulmak için bir içerik araması ve bulunan öğeleri temizlemek için bir içerik arama eylemi kullanmakla meşgul. Bu komut dosyası, işin nasıl yapılacağını gösterir. Bu gönderi temel bilgileri kapsar.

Microsoft 365 Gruplarını yeniden adlandırın
RenameMicrosoft365GroupsNamingPolicy.PS1 : Microsoft 365 Grupları için bir adlandırma ilkesi uygularsanız, görünen adları yeni ilkeye uymayan bazı mevcut gruplarınız olabilir. Bu komut dosyası, isimleri kontrol etmek ve gerekirse ayarlamak için gruplar arasında nasıl döngü yapılacağının bir örneğidir.

Etkin Takımları Bildir
ReportActiveTeams.ps1'i Güncelle : Bu komut dosyası, bir takımın etkin olup olmadığını anlamak için bir kanal konuşmasında birileri yayınladığında oluşturulan uyumluluk kayıtlarını kullanır (açıkçası, eğer herhangi bir konuşma yoksa, ekip muhtemelen aktif değildir).

Etkinlik Uyarısı Denetim Olaylarını Bildir
 Update ReportActivityAlertAuditEvents.P S1 : Güvenlik uyumu uyarılarını aramak için Office 365 denetim günlüğünü tarayan bir komut dosyası.

MFA Tarafından Korunmayan Yönetici Hesaplarını Rapor Edin
ReportAdminAzureADAccountsNoMFA.PS1 : Bu komut dosyası, bir yönetim rolü olan Azure AD hesaplarını arar ve ardından hesapların çok faktörlü kimlik doğrulama ile korunup korunmadığını denetler. MFA için etkinleştirilmesi gereken hesaplar için bir rapor (CSV) oluşturulur. Dahafazla bilgi için bu gönderiye bakın.

Seçilen bir SharePoint Dosyası için Dosya Güncellemelerini Rapor Edin
ReportAuditRecsFileUpdates.PS1 : SharePoint Online veya OneDrive İş'te depolanan belirli bir belge için dosya güncelleme kayıtları için Office 365 denetim günlüğünde arama yapın. Amaç, bir belgeyi en son kimin değiştirdiğini rapor edebilmektir. Kitabın 21. Bölümünde örnek olarak kullanılmıştır.

Grup Oluşturma için Rapor Denetim Kayıtları
ReportAuditRecsGroupCreation.PS1 : Yeni Microsoft 365 gruplarının oluşturulması için kaydedilen olayları bulmak için Office 365 denetim günlüğünü arar. Kitabın 21. Bölümünde alıntılanan örnek.

SharePoint Belgelerine Konuk Erişimi için Denetim Kayıtlarını Raporlama
ReportAuditRecsGuestDocAccess.PS1 : Komut dosyası, Dosya Erişimli kayıtları denetim günlüğünden alır ve konuk hesaplarının belge erişimlerini bulmak için bunları filtreler. SharePoint aspx bileşenleri gibi yaygın dosyalara erişimi kaldırdıktan sonra, kalan kayıtları rapor ederiz. Kitabın 21. Bölümünde kullanılan örnek. Büyük kiracılarda 90 günlük bir süre içinde 5.000'den fazla etkinliğe sahip olma olasılığınız vardır, bu nedenle hepsi toplanana kadar kayıtları almaya devam edebilir veya süreyi kısaltabilirsiniz.

Kullanıcı Oturum Açmaları için Denetim Kayıtlarını Raporlama
ReportAuditRecsUserSignIns.PS1 : Kullanıcı oturum açma olaylarını ( Teams'e bağlantılar dahil) bulmak için Office 365 denetim günlüğünü arar. Kitabın 21. Bölümünde kullanılan örnek. Bunun tersi, başarısız kullanıcı oturum açma işlemlerini aramaktır ve bunu ReportAuditRecFailedSignIn.PS1 ile yapabiliriz .

Lisans Atamalarını Kullanıcı Hesaplarına Bildirme
ReportLicenseAssignmentsToUsers.Ps1 : Bir rapor oluşturmak için kullanıcı hesapları için depolanan lisans atamalarının nasıl kullanılacağına bir örnek. Yalnızca bazı lisans türlerini sayan çok basit bir komut dosyasıdır ve bir kiracıda kullanılabilecek farklı lisanslarla ilgilenmek için genişletmeniz gerekir.

Posta Kutularına Atanan Standart Olmayan İzinleri Bildirme
ReportMailboxPermissionsMailboxes.PS1 : Kullanıcı ve paylaşılan posta kutularına atanan izinlerin Tam Erişim, SendAs ve SendOnBehalf raporuna yönelik bir komut dosyası. Bir posta kutusuna atanan izinlerin, neden geçtikten sonra orada kalmamasını sağlamak için zaman zaman bu tür bir komut dosyasını çalıştırmak iyi bir fikirdir. Dahafazla bilgi için bu gönderiye bakın.

Kullanıcı Posta Kutusu Kota Kullanımını Rapor Et
ReportMailboxQuotaUsed.Ps1 : Kullanıcı posta kutularını taramak ve posta kutusuna atanan kotanın yüzde ve miktarının ne kadarının kullanıldığını bildiren bir komut dosyası. Çıktı bir CSV dosyasıdır. Komut dosyasının kullanımı burada açıklanmaktadır .

OneDrive İş Depolama Kullanımını Bildirme
ReportOneDriveStorageUsage.PS1 : Kiracıdaki OneDrive İş siteleri kümesini kapmak ve her site tarafından ne kadar kota kullanıldığını ve ne kadar kaldığını gösteren bir rapor oluşturmak için basit bir komut dosyası. Hepsi bu yazıda açıklanmıştır .

Exchange Klasörlerinde Rapor İzinleri
ReportPermissionsFolderLevel.PS1 : Klasör düzeyinde izin atamalarını (örneğin, takvim klasörünü okuma yeteneği) bulmak için Exchange posta kutularındaki klasörleri kontrol etmeye yönelik bir komut dosyası. Çıktı bir CSV dosyasıdır. Bu, çalıştırılması hızlı bir komut dosyası değildir, ancak bu yazıda açıklandığı gibi bazı değerli bilgiler sağlayabilir.

Exchange Online Posta Kutularında Rapor İzinleri
ReportPermissionsOnMailboxes.PS1 : Bir script özellikli bu görevde Exchange Online kullanıcı ve paylaşılan posta kutuları atanan izinlere bir rapor oluşturmak için nasıl göstermek için.

Karantinaya Alınan İletileri Bildir
ReportQuarantinedMessages.PS1 : Karantinadaki iletileri tarayın (tüm posta kutuları için) ve bulunanları bildirin . Düzenlenebilen ve daha sonraiyi iletileri yayınlamakiçin Release-QuarantineMessage cmdlet'inegirdi olarak kullanılabilen bir CSV dosyası oluşturulur. Hepsi bu yazıda açıklanmıştır.

Kurtarılabilir Kalemler için Denetim Kayıtlarını Raporlayın
ReportRestoreRecoverableItemsAudit.PS 1 : Yöneticiler, bir EAC seçeneğini veya Restore-RecoverableItems cmdlet'inikullanarak kullanıcılar adına posta kutusu öğelerini kurtarabilir. Bu komut dosyası, bu olaylar meydana geldiğinde oluşturulan denetim kayıtlarını bildirir. Dahafazla bilgi için bu makaleye bakın.

Saklama Etiketlerinin Belgelere Atamasını Rapor Edin
ReportRetentionLabelAuditEvents.PS1 : Öğelere saklama etiketleri atandığında yakalanan olayları aramak için Office 365 denetim günlüğünü tarar. Komut dosyası, politika tarafından uygulanan etiketleri ve kullanıcılar tarafından uygulanan etiketleri birbirinden ayırır. Bu, kitabın 21. Bölümünde alıntılanan bir örnektir.

SharePoint Online Saklama Politikalarını Bildirin
ReportSPORetentionPolicies.PS1 : Kitabın 19. Bölümünde SharePoint Online sitelerine uygulanan saklama ilkelerini bildirmek için kullanılan bir örnek.

Siteye göre SharePoint Online Depolama Kotasını Bildirme
ReportSPOSiteStorageUsage.PS1 : Bu komut dosyası, bir kiracıda bulunan siteleri tarar ve kullanılan depolamayı ve her site için kota yüzdesini bildirir. Çıktı ayrıca site adını, sahiplerini ve şablonu (türü) içerir. Dahafazla bilgi için bu makaleye bakın.

ReportSPOSiteStorageUsedGraph.PS1 : SharePoint Online modülünden cmdlet'ler yerine Graph API çağrıları kullanması dışında diğer komut dosyasıyla hemen hemen aynı işlevi görür. Komut dosyasının kullanımı ve Grafiği kullanırken karşılaşılan farklılıklar bu makalede açıklanmaktadır.

Duyarlılık Etiketleri için Denetim Verilerini Raporlama
ReportSensitivityLabelsAuditRecords.ps1 : Duyarlılık etiketlerinin belgelere ve kapsayıcılara (Ekipler, Gruplar ve Siteler) atanması ve etiket uyuşmazlıkları için denetim kayıtlarını çıkarmak için bir komut dosyası. Ocak 2021'den itibaren Office Online, masaüstü ve mobil uygulamalar bu kayıtları oluşturur.

Teams Kanallarına Atanan E-posta Adreslerini Raporla
ReportTeamsChannelEmailAddresses.ps1 :İnsanların ona e-posta göndermesine izin vermek içinbir kanala bir e-posta adresi atanabilir. Graph API, bu e-posta adreslerini bildirmenin tek yoludur, bu komut dosyasının yaptığı da budur. Komut dosyasının ne yaptığı hakkında daha fazla bilgiyi bu Petri.com makalesinde bulabilirsiniz .

E-posta ile Yeni Takımların Rapor Oluşturulması
ReportTeamsCreationbyEmail.ps1 : Son 90 güne bakmak ve yeni ekiplerin oluşturulması için denetim kayıtlarını bulmak için bir komut dosyası. Yeni ekibin ayrıntılarını içeren bir e-posta mesajı oluşturulur ve aday gösterilen bir alıcıya gönderilir. Dahafazla ayrıntı için bu makaleye bakın.

E-Keşif Vakalarını Bildirin
ReporteDiscoveryCases.Ps1 : eDiscovery vakaları hakkında bir rapor oluşturun (temel ve gelişmiş). BT Uzmanları için Office 365 e-Kitabı'nın 20. Bölümünde örnek olarak kullanılmıştır.

SharePoint Online Saklama Politikalarını Bildirin
SPOSitesRetention.ps1 : Bir Office 365 kiracısında SharePoint Online ve OneDrive İş için geçerli olan saklama ilkelerini bildiren bir komut dosyası. BT Uzmanları için Office 365 e-Kitabı'nın 19. Bölümünde örnek olarak kullanılmıştır.

Posta Kutularından Öğeleri Kaldırmak için Arama Posta Kutusunu Kullanın
SearchAndRemoveItemsMailboxes.PS1 : Microsoft, Search-Mailbox cmdlet'ini kullanımdan kaldırmıştır, ancak hala Exchange Online'da mevcuttur. Bu komut dosyası, bir dizi posta kutusunu aramak ve bir sorgu tarafından bulunan öğeleri kaldırmak için Arama-Posta Kutusu'nun nasıl kullanılacağını gösterir. In Bu durumda , bu senaryoyu yazdım, bu yüzden de kullanıcı posta kutularına toplantılar bulmaktı.

Silinen Akış Videoları Hakkında E-posta Gönderin
SendMessageAboutDeletedStreamVideos.PS1 : Akış geri dönüşüm kutusunda kalıcı olarak silinmeyi bekleyen video kümesini bildirmek ve kiracı yöneticisine bu videolar hakkında e-posta göndermek için bir komut dosyası. Buradaki fikir, insanların herhangi bir gözetim olmadan videoları kaldırmamasını sağlamaktır. Ayrıca bir HTML raporu da oluşturulur. Dahafazla bilgi için bu makaleye bakın.

Eski Gruplar Hakkında Microsoft 365 Grup Sahiplerine E-posta Gönderin
SendMsgToGroupOwners.ps1 : Bu komut dosyası, Teams and Groups Activity rapor komut dosyasından $ Report çıktısını alır vepotansiyel olarak eski olarak işaretlenen grup sahiplerine bu üzücü durum hakkında bilgi vermek için bir e-posta oluşturur.

Yeni Posta Kutularına Hoş Geldiniz E-postası Gönderin
SendWelcomeEmail.PS1 : Yeni hesaplara hoş geldiniz mesajı göndermek için bir komut dosyası (son 7 gün içinde eklenir). Dahafazla bilgi için bu makaleye bakın.

Ekipler ve Microsoft 365 Grupları Etkinlik Raporu (PowerShell Sürümü)
TeamsGroupsActivityReport.ps1 : Bu komut dosyası, Office 365 Grupları başlatıldıktan kısa bir süre sonra oluşturuldu ve TechNet Galerisi'nde yayınlandı. Dokümantasyonuna buradan ulaşabilirsiniz . Komut dosyası, TechNet Galerisi'nin kullanımdan kaldırılmasının ardından GitHub'a taşındı ve şu anda 4.8 sürümünde. Bu sürüm yalnızca PowerShell'i kullanır ve bu nedenle Get-UnifiedGroup gibi bazı cmdlet'lerin hız kısıtlamaları ile sınırlıdır. Çalışır, ancak Grafik tabanlı sürüm çok daha hızlıdır.

Ekipler ve Microsoft 365 Grupları Etkinlik Raporu (Grafik Sürümü)
TeamsGroupsActivityReportV5.PS1 : Teams ve Microsoft 365 Grupları Etkinlik Raporu komut dosyasının Grafik tabanlı (ve çok daha hızlı) sürümü. Hız kazanmak ve makul bir sürede on binlerce grubu işleyebilmek için, orijinal komut dosyası, mümkün olduğunda Graph API çağrılarını kullanacak şekilde yeniden yazıldı. Bu nedenle, bir komut dosyasında daha performanslı Graph çağrıları için ağır PowerShell cmdlet'lerinin nasıl değiştirileceğine dair iyi bir çalışma örneğidir.

Exchange Online Posta Kutuları için Denetim Yapılandırmalarını Güncelleme
UpdateMailboxAuditing.PS1 : Office 365 E3 veya üzeri lisansa sahip her Exchange Online posta kutusu için posta kutusu denetimi etkinleştirilmelidir, ancak bazen denetim yapılandırması tam olarak ihtiyacınız olan veya istediğiniz şey değildir. Bu komut dosyası, denetim yapılandırmasını istenen duruma ayarlamak için posta kutularını işler.

OWA için E-posta İmzalarını Güncelleme
UpdateOWASignatures.ps1 : OWA (Outlook değil) tarafından kullanılacak ad, iş unvanı ve telefon numarası gibi Azure AD özniteliklerini içeren kurumsal bir e-posta imzası oluşturma. Bu komut dosyası, imzanın bir HTML biçimini oluşturur ve bunu kullanıcı posta kutusu ayarlarına yazar. Dahafazla bilgi için bu gönderiye bakın.

Office 365 Tarafından Kullanılan PowerShell Modüllerini Güncelleyin
UpdateOffice365PowerShellModules.PS1 : Office 365 iş yükleri (Azure AD, SharePoint, Teams ve Exchange Online) için PowerShell modülleri oluşturan mühendislik grupları düzenli olarak güncellemeler yayınlar. Bu komut dosyası, PowerShell Galerisi'nde bulunan güncellemeleri kontrol eder ve güncellemeleri indirip yükler. Ayrıntılar için bu makaleye bakın.

Windows Masaüstü İstemcisi için Outlook için E-posta İmzasını Güncelleştirme
UpdateOutlookSignature.PS1 : Windows için Outlook, imza bilgilerini sistem kayıt defterinde depolar. Bu komut dosyası, yeni bir imzanın nasıl oluşturulacağını ve kayıt defterinin nasıl güncelleneceğini gösterir. Ayrıntılar için bu gönderiye bakın.

Konteyner Yönetimi için Hassasiyet Etiketlerini Yeniden Yapılandırma
UpdateSensitivityLabelsForGroups.PS1 : Hassasiyet etiketleri kapsayıcı yönetimi için kullanılabilir (Ekipler, Gruplar ve Siteler). Etiketleri bu amaçla kullanmaya karar verirseniz, kap yönetimi için ayrılmış ayrı bir etiket kümesi oluşturmak isteyebilir ve daha sonra mevcut etiketleri yeni etiketlerle değiştirmeniz gerekebilir. Hepsi bu Petri.com makalesindeaçıklanmıştır.

Ekipler Tarafından Kullanılan Microsoft 365 Gruplarında Abone Ayarlarını Güncelleyin
UpdateSubscribersInGroupsUsedByTeams.PS1 : Grup abone ayarları, üyelerin takvim etkinlikleri gibi şeyler için hangi e-posta bildirimlerini alacağını belirler. Ekipler abone ayarlarını güncellemez, bu nedenle insanların kanal toplantılarına davet almadıklarından şikayet etmeleri gibi sorunlarla sonuçlanırsınız. Komut dosyası bu yazıda açıklanmıştır.

Microsoft 365 Hesapları için Kullanıcı Fotoğraflarını Güncelleyin
UpdateUserPhotos.PS1 : Bu komut dosyası, herkesin en iyi şekilde görünmesini sağlamak için bir klasörde depolanan görüntülerle kullanıcı hesaplarını günceller. Açıklaması bu Petri.com makalesinde .
