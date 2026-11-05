# Akıllı Bilgisayar Rehberi

## Proje Bilgileri

  Bilgi              Açıklama
  ------------------ ------------------------------------
  Üniversite         Amasya Üniversitesi
  Birim              Teknik Bilimler Meslek Yüksekokulu
  Bölüm              Bilgisayar Teknolojileri
  Ders               Bitirme Projesi-I
  Proje adı          Akıllı Bilgisayar Rehberi
  Projeyi yürüten    Arda KİRAZ
  Öğrenci numarası   264212507
  Proje danışmanı    Doç. Dr. Hasan Hüseyin ÖKTEN
  GitHub profili     https://github.com/arda0652

## Proje Özeti (Proje Tanımı)

Akıllı Bilgisayar Rehberi, bilgisayar kullanıcılarının karşılaştıkları
yaygın sorunları anlamalarına ve güvenli çözüm adımlarını uygulamalarına
yardımcı olan kullanıcı dostu bir masaüstü/web uygulaması olarak
tasarlanacaktır. Bilgisayar yavaşlaması, depolama alanının azalması,
uygulamaların açılmaması, internet bağlantısı sorunları ve yaygın hata
mesajları gibi durumlarda kullanıcıdan alınan bilgilere göre açıklamalı
bir rehber sunacaktır. Projenin temel yaklaşımı, yalnızca genel cevap
vermek yerine sorunun belirtilerini sınıflandırmak, uygun kontrol
adımlarını sıralamak ve çözüm sürecini takip etmektir.

Kullanıcı, yaşadığı sorunu kendi cümleleriyle yazabilecek veya
uygulamadaki sorun kategorilerinden seçim yapabilecektir. Sistem sorunu
olası kategorilere ayıracak, basit kontrolleri adım adım açıklayacak ve
her adımın ne işe yaradığını belirtecektir. Kullanıcı isterse sorunun
çözüldüğünü işaretleyebilecek; çözülmediyse bir sonraki öneriye
geçebilecektir. Sistem komut veya ayar değişikliği önerecekse bunları
açıklayacak, kullanıcı onayı olmadan otomatik işlem
gerçekleştirmeyecektir.

Uygulama özellikle bilgisayar bilgisi sınırlı olan kullanıcılar,
öğrenciler ve temel teknik sorunları kendi başına çözmek isteyen kişiler
için tasarlanacaktır. Projeyi benzer yardım sayfalarından ayıran
özellikler; kullanıcı seviyesine göre sade veya teknik anlatım sunması,
daha önce denenen çözüm adımlarını kaydetmesi ve sorun çözülene kadar
kullanıcıya aşamalı rehberlik etmesidir. Bu özellikler bir prototip
kapsamında geliştirilecek ve örnek sorun senaryolarıyla test
edilecektir.

Projenin temel hedefi, bilgisayar sorunları karşısında kullanıcıların ne
yapacağını daha kolay anlamasını sağlamak, gereksiz ve riskli denemeleri
azaltmak ve temel teknik destek bilgilerini anlaşılır bir biçimde
sunmaktır.

## Geliştirilecek Uygulamanın Son Kullanıcısının Temel İhtiyaçları

### 1. Kullanıcı Profili: Temel Bilgisayar Kullanıcısı

Bu kullanıcı tipi Linux veya Pardus ile yeni tanışmış bireylerden
oluşmaktadır.

-   Basit ve anlaşılır, adım adım yönlendirmeler
-   Önerilen kontrollerin ve ayar adımlarının açıklanması
-   Sorun türüne göre uygun kontrol adımlarını bulabilme
-   Çözüm adımlarını işaretleyebilme ve sonuçlarını takip edebilme

### 2. Kullanıcı Profili: Öğrenci veya Ofis Çalışanı

Günlük işlerinde bilgisayar kullanan ve basit teknik sorunlar nedeniyle
zaman kaybeden kişilerdir.

-   Yaygın bilgisayar sorunları için hızlı başlangıç rehberi
-   Teknik destek istemeden önce güvenli temel kontrolleri yapabilme
-   Uygulama, bağlantı ve sistem ayarları konusunda rehberlik
-   Hata mesajlarının sade bir dille açıklanması

## Projenin Sınırlarının Belirlenmesi

### Dahil Olan Özellikler

-   Sorun kategorilendirme ve kural tabanlı/isteğe bağlı yapay zekâ
    destekli açıklama sistemi
-   Yaygın bilgisayar sorunları için açıklamalı çözüm adımları
-   Kullanıcı dostu grafik arayüz ve sorun kategorileri
-   Bilgisayar yavaşlaması, depolama, bağlantı ve uygulama sorunlarına
    yönelik rehber
-   Çözüm geçmişi, adım tamamlama ve kullanıcı seviyesine göre anlatım

### Kapsam Dışı Özellikler

-   Bilgisayardaki tüm sorunları otomatik ve kesin olarak çözme
-   Kurumsal ağ ve sunucu yönetimi
-   Gelişmiş donanım onarımı veya otomatik sistem optimizasyonu
-   Mobil uygulama geliştirilmesi

## Projenin Amacı ve Faydaları

### 1. Projenin Amacı

Bilgisayar kullanıcılarının yaygın sorunları tanımasına, güvenli temel
kontrolleri öğrenmesine ve çözüm adımlarını takip etmesine yardımcı olan
bir uygulama geliştirmek.

### 2. Projenin Faydaları

Projenin kullanıcılar açısından sağlaması beklenen başlıca faydalar
şunlardır:

-   Bilgisayar sorunlarının daha anlaşılır hale gelmesi
-   Temel teknik sorunlarda kullanıcıya rehberlik edilmesi
-   Sorun çözme adımlarının ve sonuçlarının kaydedilmesi
-   Bilgisayar okuryazarlığının ve güvenli işlem alışkanlıklarının
    desteklenmesi

## Projede Kullanılacak Metot ve Yazılım Dilleri

-   Python (uygulama mantığı ve sorun çözüm kuralları)
-   HTML, CSS ve JavaScript (web arayüzü) veya Python arayüz kütüphanesi
-   SQLite (sorun ve çözüm geçmişini yerel olarak kaydetmek için)
-   İşletim sistemine göre güvenli sistem bilgisi kontrolleri; komutlar
    kullanıcı onayı olmadan çalıştırılmayacaktır.

## Proje Planı

Projenin geliştirme aşamaları aşağıdaki biçimde olacaktır.

### Proje Bölümleri ve Tasarımı

Kullanıcı ihtiyaçları dikkate alınarak belirlenen geliştirme aşamaları
ve özellikler aşağıda açıklanmıştır.

1.  İhtiyaç analizi ve belirleme
2.  Sistem tasarımı
3.  Arayüz geliştirme
4.  Yapay zekâ entegrasyonu
5.  Veritabanı ve backend geliştirme
6.  Test süreci
7.  Hata düzeltme ve final teslim

### Proje Plan Tablosu

  --------------------------------------------------------------------------------
              No Bölümün Adı    Kim            Süre (Hafta) Başlangıç   Bitiş
                                Tarafından                  Zamanı      Zamanı
                                Yapılacağı                              
  -------------- -------------- ------------ -------------- ----------- ----------
               1 1\. Bölüm:     Arda KİRAZ                1 1\. Hafta   1\. Hafta
                 İhtiyaç                                    Başı        Sonu
                 Analizi ve                                             
                 Belirleme                                              

               2 2\. Bölüm:     Arda KİRAZ                1 2\. Hafta   2\. Hafta
                 Sistem                                     Başı        Sonu
                 tasarımı ve                                            
                 kapsamın                                               
                 belirlenmesi                                           

               3 3\. Bölüm:     Arda KİRAZ                2 3\. Hafta   4\. Hafta
                 Arayüz                                     Başı        Sonu
                 geliştirme                                             

               4 4\. Bölüm:     Arda KİRAZ                2 5\. Hafta   6\. Hafta
                 Sorun                                      Başı        Sonu
                 kategorileri                                           
                 ve çözüm                                               
                 rehberi                                                
                 geliştirme                                             

               5 5\. Bölüm:     Arda KİRAZ                1 7\. Hafta   7\. Hafta
                 Çözüm geçmişi                              Başı        Sonu
                 ve veritabanı                                          

               6 6\. Bölüm:     Arda KİRAZ                1 8\. Hafta   8\. Hafta
                 Test ve                                    Başı        Sonu
                 kullanıcı                                              
                 senaryoları                                            

               7 7\. Bölüm:     Arda KİRAZ                2 9\. Hafta   10\. Hafta
                 Hata düzeltme                              Başı        Sonu
                 ve final                                               
                 teslim                                                 
  --------------------------------------------------------------------------------

------------------------------------------------------------------------

**Not:** Bu dosya, Bitirme Projesi-I Proje Öneri Formu içeriğinin GitHub
deposunda görüntülenebilmesi için Markdown biçiminde düzenlenmiştir.
