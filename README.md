# Web Final Projesi

# Yönetim ve Hasta Takip Sistemi

Bu proje, hasta kayıtları ve yönetim süreçlerini kolaylaştırmak amacıyla geliştirilmiş bir web tabanlı uygulamadır. Proje, ASP.NET, C#, SQL Server ve web teknolojileri kullanılarak hayata geçirilmiştir.

---

## İçindekiler
1. [Giriş](#giriş)
2. [GitHub ve GitLab Karşılaştırması](#karşılaştırma)
3. [Platform Seçimi](#platform-seçimi)
4. [GitHub Kullanım Planı](#final-projesi-kullanım-planı)
5. [Ekip Üyeleri ve Görevler](#ekip-üyeleri-ve-görevler)
6. [Projenin İndirilmesi ve Çalıştırılması](#projenin-indi̇rilmesi-ve-çalıştırılması)
7. [Projenin Çalışma Prensibi](#projenin-çalışma-prensibi)

---

## Giriş

- *Git Nedir?*
  Git, dağıtılmış bir versiyon kontrol sistemidir. Geliştiricilerin kodlarını yönetmesine, değişikliklerini takip etmesine ve ekip olarak çalışmasına olanak tanır.

- *GitHub Nedir?*
  GitHub, Git tabanlı bir kod paylaşım platformudur. Geliştiricilere projelerini depolama, paylaşma ve iş birliği yapma imkanı sağlar.

- *GitHub’ın Avantajları:*
  - Kodların merkezi bir yerde güvenli bir şekilde depolanması.
  - Ekip içi iş birliğinin kolaylaştırılması.
  - CI/CD süreçlerinin kolay bir şekilde otomasyona bağlanması.
  - Geniş bir topluluk ve güçlü destek.

---

## Karşılaştırma

| Özellik               | GitHub                      | GitLab                      |
|-----------------------|-----------------------------|-----------------------------|
| *Dağıtılmış Depolar*| Git tabanlı, merkezi odaklı | Git tabanlı, merkezi odaklı |
| *Versiyon Kontrolü* | Güçlü ve yaygın            | Güçlü ve esnek              |
| *CI/CD Araçları*    | GitHub Actions ile entegre  | Daha kapsamlı CI/CD araçları|
| *Proje Yönetimi*    | Basit ve kullanıcı dostu    | Detaylı ve esnek            |

---

## Platform Seçimi

*GitHub’ı tercih etme nedenlerimiz:*

- Kullanım kolaylığı ve anlaşılır arayüz.
- GitHub Actions ile CI/CD otomasyonu.
- Geniş kullanıcı kitlesi ve topluluk desteği.
- Diğer araçlarla kolay entegrasyon.

---

## Final Projesi Kullanım Planı

1. *Depo Oluşturma:*
   - GitHub'da yeni bir depo oluşturulacak.
   - Gerekli başlangıç dosyaları ve proje yapısı eklenecek.

2. *Versiyon Kontrolü:*
   - Farklı geliştirme aşamaları için main ve development gibi dallar oluşturulacak.
   - Kod değişiklikleri Pull Request kullanılarak ana dala dahil edilecek.

3. *Takım Çalışması:*
   - Hata takibi ve iş planı için Issues kullanılacak.
   - Kod incelemesi ve entegrasyon için Pull Requests süreçleri uygulanacak.

---

## Ekip Üyeleri ve Görevler

- *CUMA ALZEDAN (Proje Lideri):*
  - Projenin genel yönetimi ve planlamasını üstlendim.
  - ASP.NET ve C# kullanarak backend geliştirmelerini gerçekleştirdim.
  - Veri tabanı bağlantıları kurarak CRUD işlemleri (Create, Read, Update, Delete) gerçekleştirdim.

- *CUMA ALZEDAN:*
  - Web sayfalarının tasarımı ve kullanıcı arayüzü (UI) geliştirmelerini ben yaptım.
  - CSS ile sayfa düzenini oluşturup, responsive tasarım sağladım.
  - JavaScript ile sayfada dinamik işlemler (form doğrulama, arama, vb.) gerçekleştirdim.

- *CUMA ALZEDAN:*
  - SQL Server veri tabanı tasarımını ve yönetimini ben üstlendim.
  - Veri tabanında hasta bilgilerini saklama ve sorgulama işlemlerini gerçekleştirdim.
  - Veri tabanı ile ASP.NET arasında entegrasyon sağladım.

---

## Projenin İndirilmesi ve Çalıştırılması

1. *GitHub Deposu İndirme:*
   - Projeyi bilgisayarınıza indirmek için öncelikle GitHub reposuna gidin.
   - Sağ üst köşede bulunan Code butonuna tıklayın ve Download ZIP seçeneğini seçerek projeyi ZIP dosyası olarak indirin.
   - Alternatif olarak, terminal veya komut satırında şu komutu kullanarak depoyu klonlayabilirsiniz:
     bash
     git clone https://github.com/zeydaneng/web-final-project.git
     

2. *Projeyi Çalıştırma:*
   - Visual Studio veya Visual Studio Code kullanarak projeyi açın.
   - SQL Server veritabanı bağlantısını doğru şekilde yapılandırın.
   - appsettings.json dosyasındaki veritabanı bağlantı dizisini güncelleyin.
   - Projeyi çalıştırmak için *F5* tuşuna basarak uygulamayı başlatın.

---

## Projenin Çalışma Prensibi

Proje, web tabanlı bir yönetim ve hasta takip sistemi olarak çalışmaktadır. Kullanıcılar, sisteme giriş yaptıktan sonra hasta bilgilerini kaydedebilir, listeleyebilir, güncelleyebilir veya silebilirler.

- *Yönetim Paneli:* Yönetici giriş yaptıktan sonra hastaların kayıtlarını yönetebilir ve listeleyebilir.
- *Hasta Kayıt Sayfası:* Yeni hastalar kaydedilebilir. Bu sayfada TC kimlik numarası gibi veriler doğrulanır.
- *Hasta Listeleme Sayfası:* Kaydedilen hastaların bilgileri burada görüntülenebilir ve düzenlenebilir.
- *Veri Tabanı Entegrasyonu:* Tüm hasta bilgileri SQL Server veritabanında saklanır ve yönetilir.

Uygulama, kullanıcı dostu bir arayüz ile kullanıcıların verimli bir şekilde işlem yapmasına olanak tanır.

---

Bu proje, sağlık yönetimi sistemlerine dijital bir çözüm sunmayı hedeflemektedir. Projenin detaylarına GitHub'dan ulaşabilirsiniz.
