# Aday Takip Sistemi

Bu proje insan kaynakları firmalarının adaylarını, firmalarını takip etmek ve yöntemek için geliştirilmiştir. Proje %90 oranında tamamlanmış ve MIT lisansı altında açık kaynak olarak paylaşılmıştır.

## Proje Kaynak Kodları

Projeye ait frontend ve server repolarına buradan erişebilirsiniz.

[Proje Frontend Linki](https://github.com/Fatihkrty/aday-takip-sistemi-client)

[Proje Backend Linki](https://github.com/Fatihkrty/aday-takip-sistemi-server)

## Proje Bölümleri

### Giriş Modülü

Sisteme giriş e-mail ve şifre üzerinden tamamlanır. Bu alanda giriş, şifre sıfırlama isteği gönderme ve şifre sıfırlama işlemleri yapılabilir. Giriş yaptığınız takdirde sistemdeki rolünüze göre (`admin` , `user`) ön yüz üzerinde işlem kısıtlamaları yapılır.
Örneğin; Kullanıcı ekleme silme ve güncelleme işlemleri sadece `admin` rolüne aittir.

![ekran resmi](screenshots/auth/15.png)

![ekran resmi](screenshots/auth/16.png)

### Dashboard Modülü

Sisteme giren her personel kendi adına tanımlı talepleri ve talep durumlarını görüntüleyebilir. Ayrıca sistem üzerinde tanımlanan tüm talepler ve durumları hakkında bilgileri görebilir, en fazla talep veren 5 firma ve sayıları listelenebilir.

![ekran resmi](screenshots/dashboard/17.png)

### Firma Modülü

Bu modül ile sisteme firma tanımlanabilir. Firmaların sözleşmeleri, yetkili iletişim bilgileri, genel bilgileri vb. sistemde saklanır ve excel tarzı gelişmiş filtreleme ile filtrelenebilir. Firma ekleme, güncelleme ve silme yetkisi yalnızca `admin` rolüne aittir.

Firmaların personel talepleri IK tarafından girilebileceği gibi, firma temsilcilerine e-posta ile gönderilen tek kullanımlık linkler sayesinde firma temsilcilerinin personel istekleri sisteme tanımlanabilir.

![ekran resmi](screenshots/company/4.png)

![ekran resmi](screenshots/company/3.png)

![ekran resmi](screenshots/company/2.png)

![ekran resmi](screenshots/company/1.png)

### Aday Modülü

Bu modül ile adayların genel bilgileri, çalışma bilgileri, pozisyon ve sektör bilgileri saklanabilir. Ayrıca adayların CV dosyaları sistem yükklenebilir ve takibi yapılabilir. Adaylar firmalara yönlendirildikleri takdirde adaylara toplu bir şekilde bilgilendirme e-postası atılabilir. Adayların davranış ve tutumlarına göre derecelendirme ve kara liste işlemleri gerçekleştirilebilir.

Adayların genel bilgileri ile gelişmiş excel filtrelemesi yapılabilir. Aday kartı seçenekleri ile adayların bilgileri ve firma yönlendirme geçmişleri takip edilebilir.

![ekran resmi](screenshots/candidate/1.png)

![ekran resmi](screenshots/candidate/5.png)

![ekran resmi](screenshots/candidate/2.png)

![ekran resmi](screenshots/candidate/3.png)

![ekran resmi](screenshots/candidate/4.png)

### Yönlendirme Takip Modülü

Bu modül üzerinden firmaların gönderdikleri talepler ve bu taleplere yönlendirilen adaylar takip edilebilir. Adayların geçmişi ve firmalar hakkındaki tutumları not edilebilir, filtrelenebilir.

![ekran resmi](screenshots/referral/2.png)

![ekran resmi](screenshots/referral/1.png)

### Otomatik Tamamlama Modülü

Sistemde kullanımı kolaylaştırmak adına otomatik tamamlama seçenekleri eklenmiştir. Otomatik tamamlama verileri; `pozisyonlar` , `sektörler` , `lokasyonlar` şeklinde tanımlanmıştır. Veri girişi (aday ekleme, talep ekleme, firma ekleme vb.) sırasında tanımlanmayan pozisyon, lokasyon, sektör bilgileri sisteme otomatik olarak eklenir.

![ekran resmi](screenshots/autocomplete/1.png)

![ekran resmi](screenshots/autocomplete/2.png)

### Diğer Özellikler

Projeye bildirim sistemi, gelişmiş tablo özellikleri eklenmiştir. Tablo özellikleri arasında;

- Tablo tam ekran çalışma
- Excel tarzı gelişmiş filtreleme (server-database üzerinden canlı filtreleme yapar)
- Veri sıralama (server-database üzerinden canlı sıralama yapar)
- Tablo çalışma alanını kendinize göre düzenleme (kolon gizleme, kolon sabitleme vb.)
- Tablo boyutu ayarlama
- Veri güncelleme, sağ tık menü özellikleri vb.

![ekran resmi](screenshots/other/4.png)

![ekran resmi](screenshots/other/5.png)

![ekran resmi](screenshots/other/13.png)
