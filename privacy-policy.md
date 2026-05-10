# Gizlilik Politikası — İsim Şehir

**Yürürlük tarihi:** 9 Mayıs 2026
**Son güncelleme:** 9 Mayıs 2026

İsim Şehir ("Uygulama", "biz") olarak gizliliğine önem veriyoruz. Bu politika, Uygulamayı kullanırken hangi verilerin toplandığını, nasıl işlendiğini ve haklarını açıklar.

## 1. Veri Sorumlusu
- **Geliştirici:** Samet Yılmaz
- **İletişim e-postası:** sametyilmaz1628@gmail.com
- **Adres:** İstanbul, Türkiye

## 2. Topladığımız Veriler

### 2.1 Doğrudan sağladığın veriler
- **Kullanıcı adı**: hesap oluştururken seçtiğin ad (zorunlu)
- **Parola**: hesabınla giriş için (asla düz metin saklanmaz; bcrypt ile hash'lenir)
- **E-posta adresi**: hesap doğrulama, şifre sıfırlama ve önemli güvenlik bildirimleri için (zorunlu)
- **Avatar seçimi**: önceden hazırlanmış ikonlardan biri (zorunlu)
- **Sohbet mesajları**: oda içi (anlık, kalıcı saklanmaz) ve özel mesajlar (Premium özelliği)
- **Arkadaş listesi**: eklediğin/seni ekleyen kullanıcılar (Premium özelliği)
- **Premium satın alma kaydı**: ödeme bilgisi App Store / Play Store tarafından işlenir; biz yalnızca "premium aktif/değil" durumunu ve geçerlilik süresini saklarız

### 2.2 Otomatik toplanan veriler
- **IP adresi**: oturum kurma, güvenlik ve kötüye kullanım önleme amaçlı
- **Cihaz/işletim sistemi bilgisi**: hata raporlama ve uyumluluk amaçlı
- **Push bildirim tokeni** (Expo / Apple Push Notification / Firebase Cloud Messaging): bildirim göndermek için, izin verdiğin durumda
- **Oyun aktivite verisi**: oluşturduğun ve katıldığın odalar, kazandığın puanlar, kullanıcı adın ile birlikte saklanır
- **Reklam kimliği (IDFA / GAID)**: Premium olmayan kullanıcılarda gösterilen banner reklamlar için Google AdMob tarafından, iOS ATT (App Tracking Transparency) izninle veya kişiselleştirilmemiş reklam modunda kullanılır

### 2.3 Toplamadığımız veriler
- Telefon numaran
- Konum bilgisi (GPS, ülke, şehir tahmini dahil)
- Rehber, fotoğraf, takvim, mikrofon, kamera erişimi
- Sağlık verisi, ödeme kartı bilgisi
- Biyometrik veri (Face ID / Touch ID cihazında lokal kalır)

## 3. Verilerini Neden ve Nasıl İşliyoruz?

| Amaç | Veri | Yasal dayanak (KVKK m.5 / GDPR Art.6) |
|---|---|---|
| Hesap oluşturma ve oturum | Kullanıcı adı, e-posta, parola hash'i | Sözleşmenin ifası |
| Oyun servisi | Oda durumu, oyuncu aktivitesi | Sözleşmenin ifası |
| Sohbet ve mesaj teslimi | Mesaj içeriği | Sözleşmenin ifası |
| Push bildirimi | Bildirim token'ı | Açık rıza (cihaz izniyle) |
| Reklam gösterimi (Premium olmayanlar) | Reklam kimliği, cihaz bilgisi | Açık rıza (ATT izniyle) |
| Güvenlik / kötüye kullanım önleme | IP, oturum logları | Meşru menfaat |
| Yasal yükümlülüklerin yerine getirilmesi | Talep edilen tüm veri | Hukuki yükümlülük |

## 4. Veri Saklama Süreleri

- **Hesap verileri** (kullanıcı adı, e-posta, parola hash'i, avatar): hesabın aktif olduğu sürece + hesap silindikten sonra aktif sistemlerden silinir; yedek sistemler ve yasal kayıt zorunlulukları için makul süre içinde anonymize edilir veya silinir
- **Oda sohbetleri**: oda kapatılana kadar bellekte tutulur; **veritabanına yazılmaz**, oda kapanınca silinir
- **Özel mesajlar (DM)**: hesabın aktif olduğu sürece veritabanında saklanır, hesap silindiğinde silinir
- **Oturum / IP log'ları**: güvenlik, kötüye kullanım önleme ve hata ayıklama amacıyla sınırlı süreyle saklanır (azami 90 gün)
- **Premium satın alma kaydı**: 5 yıl (vergi ve tüketici hukuku yükümlülüğü gereği)

## 5. Moderasyon ve Topluluk Güvenliği

Güvenlik, kötüye kullanım önleme, topluluk kurallarının uygulanması ve yasal yükümlülüklerin yerine getirilmesi amacıyla kullanıcı mesajları ve aktiviteleri **sınırlı ölçüde incelenebilir**. İnceleme şu durumlarda yapılabilir:

- Başka bir kullanıcıdan gelen şikayet/raporun ardından
- Otomatik kötüye kullanım tespiti (spam, sosyal mühendislik, bot)
- Yasal makamlardan gelen geçerli talep üzerine

İçerikler genel pazarlama, analiz veya üçüncü taraflarla paylaşım amacıyla incelenmez.

## 6. Verilerini Kimlerle Paylaşıyoruz?

**Kişisel veriler reklam amacıyla üçüncü taraflara satılmaz.** Sınırlı paylaşım yalnızca aşağıdaki durumlarda gerçekleşir:

- **Sunucu sağlayıcı** (Hetzner Online GmbH — Almanya): veriler bu sunucuda barındırılır
- **App Store / Google Play** (Apple Inc. / Google LLC): ödeme işlemleri ve hesap doğrulama
- **RevenueCat** (Premium abonelik yönetimi): anonim müşteri kimliği ve "aktif/değil" durumu
- **Google AdMob** (banner reklam): Premium olmayan kullanıcılara reklam gösterimi için cihaz/reklam kimliği
- **Expo / Apple Push / Firebase Cloud Messaging**: push bildirim teslimi için bildirim token'ı
- **E-posta servis sağlayıcı**: hesap doğrulama ve şifre sıfırlama e-postalarının iletimi için
- **Yasal zorunluluk**: yetkili makamlardan gelen mahkeme kararı, savcılık talebi vb.

## 7. Verilerin Saklandığı Yer

Veriler Avrupa Birliği'nde (Almanya, Hetzner veri merkezi) barındırılır. AB-Türkiye ve diğer ülkeler arası veri transferlerinde, uygulanabilir veri koruma mevzuatlarına (KVKK, GDPR) uygun teknik ve organizasyonel önlemler alınır.

## 8. Haklarınız (KVKK m.11 / GDPR Art. 15-22)

İletişim e-posta adresimize yazarak şu haklarını kullanabilirsin:
- Hangi verilerin işlendiğini öğrenme
- Düzeltme talep etme
- **Silme** ("unutulma hakkı") — hesap silme uygulama içinden yapılabilir; tam silme talebi 30 gün içinde tamamlanır
- Aktarma (verinin makine-okunur formatta sana iletilmesi)
- İşlemeye itiraz etme
- Otomatik karar verme süreçlerine itiraz (uygulanabilirse)

Talebine **30 gün içinde** ücretsiz cevap veririz.

## 9. Çocukların Gizliliği

İsim Şehir **13 yaş altı** kullanıcılara yönelik değildir. 13 yaş altı bir çocuktan veri topladığımızı fark edersek derhal sileriz. Ebeveyn / vasi olarak çocuğunun bizimle paylaştığı veri olduğunu düşünüyorsan iletişim e-postamıza yazman yeterli.

## 10. Güvenlik Önlemleri

- Parolalar **bcrypt** (10 round) ile hash'lenir; düz metin saklanmaz
- Veritabanı erişimi yalnızca uygulama sunucusuyla, parola korumalı bağlantıyla
- Veriler şifreli (TLS) bağlantı üzerinden iletilir
- Düzenli güvenlik güncellemeleri ve yedekleme
- Yetkisiz erişim girişimleri loglanır

## 11. Çerezler ve Takip

İsim Şehir mobil uygulama olduğu için çerez kullanmıyoruz. Yasal belgelerin yayınlandığı `isimsehir.app` web sitesi yalnızca temel oturum çerezleri kullanır.

## 12. Üçüncü Taraf Bağlantılar

Uygulama içinde harici bağlantı (örn. arkadaş davet linki, destek e-postası) bulunabilir. Bu bağlantıları takip ettiğinde ilgili sitenin gizlilik politikası geçerli olur.

## 13. Politikadaki Değişiklikler

Bu politikayı güncelleyebiliriz. Önemli değişikliklerde uygulama içinde bildirim göstereceğiz. Güncel sürümün yürürlük tarihi yukarıda yer alır.

## 14. İletişim

Soruların, talepleriniz veya şikayetin için:
**E-posta:** sametyilmaz1628@gmail.com

KVKK kapsamında yetkili makam:
**Kişisel Verileri Koruma Kurumu** — https://www.kvkk.gov.tr

---

# Privacy Policy — İsim Şehir (English)

**Effective date:** May 9, 2026
**Last updated:** May 9, 2026

İsim Şehir ("the App", "we") respects your privacy. This policy explains what data we collect, how we process it, and your rights.

## 1. Data Controller
- **Developer:** Samet Yılmaz
- **Contact email:** sametyilmaz1628@gmail.com
- **Address:** Istanbul, Turkey

## 2. Information We Collect

### 2.1 Provided directly by you
- **Username** (required at signup)
- **Password** (stored as bcrypt hash, never plaintext)
- **Email address**: required for account verification, password reset, and important security notifications
- **Avatar selection** (required)
- **Chat messages**: room chat (transient, not persisted) and direct messages (Premium feature)
- **Friends list** (Premium feature)
- **Premium purchase status**: payment data is processed by App Store / Play Store; we only store the active/inactive flag and validity period

### 2.2 Automatically collected
- **IP address**: for session, security, and abuse prevention
- **Device / OS info**: for crash reporting and compatibility
- **Push notification token** (Expo / Apple Push / Firebase Cloud Messaging): for delivering notifications, when permitted
- **Game activity**: rooms created/joined, scores, stored together with your username
- **Advertising ID (IDFA / GAID)**: used by Google AdMob to serve banner ads to non-Premium users, under your iOS App Tracking Transparency consent or in non-personalized ads mode

### 2.3 We do **not** collect
- Phone number
- Location (GPS, country/city inference included)
- Contacts, photos, calendar, microphone, camera access
- Health data, payment card details
- Biometric data (Face ID / Touch ID remains on-device)

## 3. How We Use Your Data

| Purpose | Data | Legal basis (GDPR Art.6) |
|---|---|---|
| Account / session | Username, email, password hash | Performance of contract |
| Game service | Room state, activity | Performance of contract |
| Chat & message delivery | Message content | Performance of contract |
| Push notifications | Notification token | Consent (device permission) |
| Ad serving (non-Premium) | Advertising ID, device info | Consent (ATT permission) |
| Security / abuse prevention | IP, logs | Legitimate interest |
| Legal compliance | All requested data | Legal obligation |

## 4. Retention

- **Account data**: while active + removed from active systems upon deletion; backup systems and legally mandated records anonymized or deleted within a reasonable period
- **Room chats**: in-memory only, destroyed when the room closes
- **Direct messages**: while account active, deleted upon account deletion
- **Session / IP logs**: retained for security and abuse prevention for a limited period (max 90 days)
- **Premium purchase records**: 5 years (tax / consumer protection obligation)

## 5. Moderation and Community Safety

User messages and activity may be reviewed in **limited circumstances** for moderation, abuse prevention, community safety, and to comply with legal obligations. Review may occur:

- After a report by another user
- Through automated abuse detection (spam, social engineering, bots)
- Upon a valid legal request

Content is not reviewed for general marketing, analytics, or sharing with third parties.

## 6. Sharing

**Personal data is not sold to third parties for advertising purposes.** Limited sharing occurs only:

- **Hosting provider** (Hetzner Online GmbH, Germany): data is hosted on this server
- **App Store / Google Play** (Apple Inc. / Google LLC): payment processing and account verification
- **RevenueCat** (Premium subscription management): anonymous customer ID and active/inactive status
- **Google AdMob** (banner ads): device/advertising ID for serving ads to non-Premium users
- **Expo / Apple Push / Firebase Cloud Messaging**: notification token for push delivery
- **Email service provider**: delivery of verification and password-reset emails
- **Legal authorities**: with a valid court order or prosecutor request

## 7. Storage Location

Data is stored in the European Union (Germany, Hetzner data center). Transfers between EU, Turkey, and other countries are subject to appropriate technical and organizational measures under applicable data-protection laws (KVKK, GDPR).

## 8. Your Rights (GDPR Art. 15-22)

By emailing us you can:
- Access your data
- Correct it
- **Delete** ("right to erasure") — in-app deletion is available; full erasure is completed within 30 days
- Port it (machine-readable format)
- Object to processing
- Object to automated decision-making (where applicable)

We respond **within 30 days** at no cost.

## 9. Children

İsim Şehir is not intended for users **under 13**. If we discover such a user, we delete the data immediately. Parents / guardians may contact us at any time.

## 10. Security

- Passwords hashed with bcrypt (10 rounds)
- Database access only via the authenticated app server
- TLS for all in-transit data
- Regular updates and backups
- Unauthorized access attempts are logged

## 11. Cookies & Tracking

As a mobile app we don't use cookies. The companion website at `isimsehir.app` (where legal documents are published) only uses essential session cookies.

## 12. Third-Party Links

External links in the app (e.g. friend invitation links, support email) may be present. Those services have their own privacy policies.

## 13. Changes to This Policy

We may update this policy. Material changes will be communicated in-app. The effective date above reflects the current version.

## 14. Contact

For questions or requests:
**Email:** sametyilmaz1628@gmail.com

GDPR supervisory authority:
**Turkish Personal Data Protection Authority** — https://www.kvkk.gov.tr
