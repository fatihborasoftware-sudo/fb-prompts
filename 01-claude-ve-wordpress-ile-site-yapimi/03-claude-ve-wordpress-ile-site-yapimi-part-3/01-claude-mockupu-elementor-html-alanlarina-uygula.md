| | |
|---|---|
| **Kurs** | 01 · Claude ve WordPress ile Site Yapımı |
| **Ders** | Part 3 |
| **Video** | [https://www.youtube.com/watch?v=rjDYf4CALwA](https://www.youtube.com/watch?v=rjDYf4CALwA) |
| **Hangi yapay zeka için** | Claude |
| **Ne yapar** | Onaylı HTML mockup'ı mevcut WordPress sayfalarının Elementor HTML Widget alanlarına, header/footer'a dokunmadan uygular |
| **Eklendi** | 2026-08-26 |
| **Sürüm** | 1.0 |

> Kopyalamak için kod bloğunun sağ üstündeki kopyala simgesine tıklayın. Köşeli parantez içindeki `[ALANLAR]` kendi projenize göre değiştirilir.

# Claude için Otomasyon Prompt

```text
WordPress Web Sitesini Mevcut HTML Mockup'a Göre Tamamlama
Merhaba Claude,
Sana daha önce hazırlattığım HTML mockup tasarımını şimdi mevcut WordPress web siteme uygulamanı istiyorum.
WordPress kurulumu, tema kurulumu ve gerekli sayfaların oluşturulması tarafımdan tamamlandı.
ÇOK ÖNEMLİ KURAL
Header ve Footer oluşturma, düzenleme veya değiştirme.
Web sitesinin Header ve Footer alanları WordPress/tema üzerinden ayrıca yönetilecek.
Bu nedenle sana verdiğim HTML mockup içerisinde Header veya Footer kodları bulunuyorsa bunları sayfalara ekleme.
Sadece sayfaların ana içerik bölümlerini kullan.
________________________________________
Mevcut WordPress Yapısı
Aşağıdaki sayfalar WordPress üzerinde zaten oluşturuldu:
•	Anasayfa
•	Hakkımızda
•	Galeri
•	Blog
•	İletişim
Yeni sayfa oluşturma.
Mevcut sayfaları kullan.
________________________________________
Elementor Yapısı
Her sayfayı Elementor ile önceden hazırladım.
Her sayfanın içerisinde HTML kodu eklemek için kullanabileceğin bir Elementor HTML Widget / HTML alanı bulunmaktadır.
Senin yapman gereken:
1.	WordPress yönetim paneline gir.
2.	İlgili sayfayı aç.
3.	Elementor ile Düzenle seçeneğini kullan.
4.	Sayfada bulunan mevcut HTML Widget alanını bul.
5.	Sana verdiğim mockup içerisinden sadece o sayfaya ait HTML içeriğini al.
6.	HTML kodunu mevcut HTML Widget içerisine ekle.
7.	Sayfayı güncelle.
8.	Sonuçları frontend üzerinden kontrol et.
9.	Daha sonra sıradaki sayfaya geç.
________________________________________
Header ve Footer Kuralı
Mockup içerisinde aşağıdaki yapılar bulunuyorsa:

<header> ... </header>

veya

<footer> ... </footer>

bunları KESİNLİKLE Elementor sayfalarına ekleme.
Aynı şekilde:
•	Navbar
•	Ana navigasyon
•	Site logosunun bulunduğu header
•	Global menü
•	Footer menüsü
•	Copyright alanı
•	Global footer iletişim bilgileri
sayfa HTML içerisine eklenmemelidir.
Bunlar WordPress tarafından ayrıca yönetilecektir.
________________________________________
Sayfalara Uygulanacak Yapı
Mockup içerisindeki tasarımı aşağıdaki şekilde ayır:
Anasayfa
Sadece Anasayfa'nın <main> / içerik bölümünü kullan.
Hakkımızda
Sadece Hakkımızda sayfasına ait içerikleri kullan.
Galeri
Sadece Galeri sayfasına ait içerikleri kullan.
Blog
Sadece Blog sayfasına ait içerikleri kullan.
İletişim
Sadece İletişim sayfasına ait içerikleri kullan.
Her sayfanın tasarımı mockuptaki tasarıma mümkün olduğunca sadık kalmalıdır.
________________________________________
Tasarım
Mockup içerisinde kullanılan:
•	renkler
•	kart tasarımları
•	butonlar
•	başlıklar
•	spacing
•	section yapıları
•	border radius
•	görsel alanları
•	hover efektleri
•	responsive yapı
•	typography
•	arka planlar
korunmalıdır.
CSS gerekiyorsa HTML Widget içerisinde çalışabilecek şekilde ilgili sayfanın koduna dahil edebilirsin.
Ancak WordPress'in veya temanın global CSS dosyalarını gereksiz yere değiştirme.
________________________________________
WordPress Sistemine Dokunma
Aşağıdaki alanlarda değişiklik yapma:
•	WordPress kurulumu
•	Tema
•	Pluginler
•	Header
•	Footer
•	WordPress kullanıcıları
•	WordPress ayarları
•	Permalink ayarları
•	Hosting ayarları
•	PHP dosyaları
•	functions.php
•	Tema dosyaları
Senin görevin sadece mevcut Elementor sayfalarındaki HTML alanlarını doldurmak ve sayfaları tamamlamak.
________________________________________
Önemli: Mevcut Yapıyı Koru
Bir sayfaya girdiğinde mevcut Elementor yapısını silip yeniden oluşturma.
Ben HTML Widget alanlarını senin için hazırladım.
Sadece ilgili HTML Widget'ın içeriğini düzenle.
Gereksiz Elementor Container, Section veya Widget oluşturma.
________________________________________
Çalışma Sırası
Aşağıdaki sırayla ilerle:
1.	Anasayfa
2.	Hakkımızda
3.	Galeri
4.	Blog
5.	İletişim
Her sayfayı tamamladıktan sonra frontend üzerinden kontrol et.
Kontrol etmen gerekenler:
•	Sayfa düzgün yükleniyor mu?
•	Header sadece WordPress'in mevcut header'ı olarak mı görünüyor?
•	İkinci bir header oluşmuş mu?
•	Footer sadece WordPress'in mevcut footer'ı olarak mı görünüyor?
•	İkinci bir footer oluşmuş mu?
•	Tasarım mockupa uyuyor mu?
•	Mobil görünüm bozuluyor mu?
•	Tablet görünümü düzgün mü?
•	Masaüstü görünümü düzgün mü?
•	Butonlar ve linkler çalışıyor mu?
•	Görseller düzgün görüntüleniyor mu?
•	HTML/CSS çakışması var mı?
________________________________________
En Önemli Kural
Bu projede sayfanın tüm HTML belgesini WordPress'e yapıştırmıyoruz.
Yani:

<html>
<head> ... </head>
<body>
<header> ... </header>
...
<footer> ... </footer>
</body>
</html>

gibi tüm web sitesi yapısını Elementor'a ekleme.
Elementor'a sadece sayfanın içerik tasarımını ekle.
Örneğin mantık şu olmalı:

<section class="hero">
    ...
</section>

<section class="hizmetler">
    ...
</section>

Header ve Footer WordPress tarafından yönetilmeye devam edecek.
________________________________________
Sonuç
Ben sana HTML mockup dosyasını vereceğim.
Mockup'ı analiz et, her sayfanın içeriğini ayır ve mevcut WordPress sayfalarının içerisindeki Elementor HTML Widget alanlarına doğru kodları yerleştir.
Yeni tasarım üretme.
Yeni sayfa oluşturma.
Header ve Footer yapma.
Mevcut Header ve Footer'a dokunma.
Sadece verdiğim mockup tasarımını mevcut Elementor HTML alanlarına uygula ve bütün sayfaları tamamla.
Tüm işlemleri tamamladıktan sonra hangi sayfalara hangi işlemleri yaptığını kısa bir özet halinde bildir.
```

## Not

Sitedeki ders sayfasında bu promptun içindeki HTML etiketleri (`<header>`, `<footer>`, `<section>` …) WordPress
tarafından temizlendiği için boş görünür; buradaki sürüm etiketleri içeren tam halidir.

## Kendi projenize uyarlama

- Sayfa listesini (Anasayfa, Hakkımızda…) kendi sitenizdeki sayfalarla değiştirin.
- Sayfalarınızda HTML Widget hazır değilse, Part 2'deki gibi her sayfaya önce boş bir HTML Widget ekleyin.
