# Gizlilik Politikası — İsim Şehir

**Yürürlük tarihi:** 29 Nisan 2026
**Son güncelleme:** 29 Nisan 2026

İsim Şehir ("Uygulama", "biz") olarak gizliliğine önem veriyoruz. Bu politika, Uygulamayı kullanırken hangi verilerin toplandığını, nasıl işlendiğini ve haklarını açıklar.

## 1. Veri Sorumlusu
- **Geliştirici:** [BURAYA AD/SOYAD veya FİRMA ADI]
- **İletişim e-postası:** [BURAYA İLETİŞİM EMAILİ]
- **Adres:** [BURAYA ADRES — KVKK için tüzel kişilikse zorunlu]

## 2. Topladığımız Veriler

### 2.1 Doğrudan sağladığın veriler
- **Kullanıcı adı**: hesap oluştururken seçtiğin ad (zorunlu)
- **Parola**: hesabınla giriş için (asla düz metin saklanmaz; bcrypt ile hash'lenir)
- **Avatar seçimi**: önceden hazırlanmış ikonlardan biri (zorunlu)
- **Sohbet mesajları**: oda içi ve özel mesajlar (Premium üyelere)
- **Arkadaş listesi**: eklediğin/seni ekleyen kullanıcılar (Premium üyelere)
- **Premium satın alma kaydı**: ödeme bilgisi App Store / Play Store tarafından işlenir; biz yalnızca "premium aktif/değil" durumunu görürüz

### 2.2 Otomatik toplanan veriler
- **IP adresi**: oturum süresince bağlantı kurmak için
- **Cihaz/işletim sistemi bilgisi**: hata raporlama amaçlı
- **Oyun aktivite verisi**: oluşturduğun ve katıldığın odalar, kazandığın puanlar, kullanıcı adın ile birlikte saklanır

### 2.3 Toplamadığımız veriler
- E-posta adresin (zorunlu değil; kayıt için sadece kullanıcı adı yeterli)
- Telefon numaran
- Konum bilgisi
- Rehber, fotoğraf, takvim erişimi
- Reklam kimliği (IDFA / GAID) — _AdMob entegrasyonu ileride eklenirse bu bölüm güncellenecektir_

## 3. Verilerini Neden ve Nasıl İşliyoruz?

| Amaç | Veri | Yasal dayanak (KVKK m.5) |
|---|---|---|
| Hesap oluşturma ve oturum | Kullanıcı adı, hash'li parola | Sözleşmenin ifası |
| Oyun servisi | Oda durumu, oyuncu aktivitesi | Sözleşmenin ifası |
| Sohbet teslimi | Mesaj içeriği | Açık rıza |
| Güvenlik / kötüye kullanım önleme | IP, oturum logları | Meşru menfaat |
| Yasal yükümlülüklerin yerine getirilmesi | Talep edilen tüm veri | Hukuki yükümlülük |

## 4. Veri Saklama Süreleri

- **Hesap verileri** (kullanıcı adı, parola hash, avatar): hesabın aktif olduğu sürece + hesap silindikten sonra **30 gün** içinde tamamen silinir
- **Oda sohbetleri**: oda kapatılana kadar bellekte tutulur; **veritabanına yazılmaz**, oda kapanınca silinir
- **Özel mesajlar (DM)**: hesabın aktif olduğu sürece veritabanında saklanır
- **Oturum log'ları**: 90 gün
- **Premium satın alma kaydı**: 5 yıl (yasal yükümlülük gereği)

## 5. Verilerini Kimlerle Paylaşıyoruz?

**Asla satmıyoruz.** Sadece şu durumlarda paylaşılır:

- **Sunucu sağlayıcı** (Hetzner Online GmbH — Almanya): veriler bu sunucuda barındırılır
- **App Store / Google Play**: ödeme işlemleri ve hesap doğrulama
- **RevenueCat** (Premium abonelik yönetimi — eklendiğinde): sadece anonim abonelik durumu
- **Yasal zorunluluk**: yetkili makamlardan gelen mahkeme kararı, savcılık talebi vb.

## 6. Verilerin Saklandığı Yer

Tüm veriler Avrupa Birliği'nde (Almanya, Hetzner veri merkezi) barındırılır. AB-Türkiye arası veri transferi GDPR ve KVKK uyumludur.

## 7. Haklarınız (KVKK m.11 / GDPR Art. 15-22)

İletişim e-posta adresimize yazarak şu haklarını kullanabilirsin:
- Hangi verilerin işlendiğini öğrenme
- Düzeltme talep etme
- **Silme** ("unutulma hakkı") — hesap silme uygulama içinden yapılabilir; tam silme talebi 30 gün içinde tamamlanır
- Aktarma (verinin makine-okunur formatta sana iletilmesi)
- İşlemeye itiraz etme

Talebine **30 gün içinde** ücretsiz cevap veririz.

## 8. Çocukların Gizliliği

İsim Şehir **13 yaş altı** kullanıcılara yönelik değildir. 13 yaş altı bir çocuktan veri topladığımızı fark edersek derhal sileriz. Ebeveyn / vasi olarak çocuğunun bizimle paylaştığı veri olduğunu düşünüyorsan iletişim e-postamıza yazman yeterli.

## 9. Güvenlik Önlemleri

- Parolalar **bcrypt** (10 round) ile hash'lenir; düz metin saklanmaz
- Veritabanı erişimi yalnızca uygulama sunucusuyla, parola korumalı bağlantıyla
- Veriler şifreli (TLS) bağlantı üzerinden iletilir
- Düzenli güvenlik güncellemeleri ve yedekleme

## 10. Çerezler ve Takip

İsim Şehir mobil uygulama olduğu için çerez kullanmıyoruz. Web sitesi (varsa) sadece zorunlu (oturum) çerezler kullanır.

## 11. Üçüncü Taraf Bağlantılar

Uygulama içinde harici bağlantı (örn. arkadaş davet linki) bulunabilir. Bu bağlantıları takip ettiğinde ilgili sitenin gizlilik politikası geçerli olur.

## 12. Politikadaki Değişiklikler

Bu politikayı güncelleyebiliriz. Önemli değişikliklerde uygulama içinde bildirim göstereceğiz. Güncel sürümün yürürlük tarihi yukarıda yer alır.

## 13. İletişim

Soruların, talepleriniz veya şikayetin için:
**E-posta:** [BURAYA İLETİŞİM EMAILİ]

KVKK kapsamında yetkili makam:
**Kişisel Verileri Koruma Kurumu** — https://www.kvkk.gov.tr

---

# Privacy Policy — İsim Şehir (English)

**Effective date:** April 29, 2026

## 1. Data Controller
- **Developer:** [YOUR NAME / COMPANY]
- **Contact email:** [YOUR CONTACT EMAIL]
- **Address:** [YOUR ADDRESS]

## 2. Information We Collect

### 2.1 Provided directly by you
- Username (required at signup)
- Password (stored as bcrypt hash, never plaintext)
- Avatar selection
- Chat messages (room chat and private messages, Premium only)
- Friends list (Premium only)
- Premium purchase status (handled by App Store / Play Store; we only store on/off)

### 2.2 Automatically collected
- IP address (during active session)
- Device / OS info (for crash reports)
- Game activity (rooms created/joined, scores)

### 2.3 We do **not** collect
- Email address
- Phone number
- Location
- Contacts, photos, calendar
- Advertising ID — _will be updated if AdMob is later integrated_

## 3. How We Use Your Data

| Purpose | Data | Legal basis (GDPR) |
|---|---|---|
| Account / session | Username, hash | Contract |
| Game service | Room state, activity | Contract |
| Chat delivery | Messages | Consent |
| Security / abuse prevention | IP, logs | Legitimate interest |
| Legal compliance | All requested data | Legal obligation |

## 4. Retention

- Account data: while active + **30 days** after deletion
- Room chats: in-memory only, destroyed when room closes
- Private messages: while account active
- Session logs: 90 days
- Premium purchase records: 5 years (legal requirement)

## 5. Sharing

We **never sell** your data. Limited sharing:
- **Hosting provider** (Hetzner, Germany)
- **App Store / Google Play** (payment & account verification)
- **RevenueCat** (Premium subscription management — when integrated)
- **Legal authorities** (only with valid court order)

## 6. Storage Location

All data is stored in the European Union (Germany — Hetzner data center). EU-Turkey transfers comply with GDPR and KVKK.

## 7. Your Rights (GDPR Art. 15-22)

By emailing us you can:
- Access your data
- Correct it
- **Delete** ("right to erasure") — in-app deletion available; full erase within 30 days
- Port it (machine-readable format)
- Object to processing

We respond **within 30 days** at no cost.

## 8. Children

İsim Şehir is not intended for users **under 13**. If we discover such a user, we delete the data immediately. Parents / guardians may contact us at any time.

## 9. Security

- Passwords hashed with bcrypt (10 rounds)
- Database access only via authenticated app server
- TLS for all in-transit data
- Regular updates and backups

## 10. Cookies & Tracking

As a mobile app, we don't use cookies. Any companion website uses only essential session cookies.

## 11. Third-Party Links

External links inside the app are subject to those services' own privacy policies.

## 12. Changes to This Policy

We may update this policy. Material changes will be communicated in-app. The effective date above reflects the current version.

## 13. Contact

For questions or requests:
**Email:** [YOUR CONTACT EMAIL]

GDPR supervisory authority:
**Turkish Personal Data Protection Authority** — https://www.kvkk.gov.tr
