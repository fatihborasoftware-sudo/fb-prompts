| | |
|---|---|
| **Kurs** | 02 · Yapay Zeka ile Proje Geliştirme Rehberi |
| **Ders** | Bölüm 3 — Konuşarak Proje Geliştirme |
| **Video** | Yayın: 4 Eylül 2026, 13:00 — bağlantı yayından sonra eklenecek |
| **Hangi yapay zeka için** | Claude |
| **Ne yapar** | Videodaki gerçek Master Prompt: Claude'a projeyi Mind Map'e kelimesi kelimesine eklemesini, uygulama planını çıkarmasını ve onay gelene kadar WordPress'e dokunmamasını söyler |
| **Eklendi** | 2026-09-03 |
| **Sürüm** | 1.0 |

> Kopyalamak için kod bloğunun sağ üstündeki kopyala simgesine tıklayın. Köşeli parantez içindeki `[ALANLAR]` kendi projenize göre değiştirilir.

# Claude için — Master Prompt (oto servis örnek projesi)

Bu, videoda ChatGPT ile yaptığım konuşmadan çıkan ve Claude'a verdiğim **gerçek** Master Prompt'tur. Proje adı ve
site adresi benim örnek projeme aittir; kendi projenizde `"OTO SERVİS VE ARAÇ BAKIM WEB SİTESİ"` yerine kendi
proje adınızı, en sondaki bağlantı yerine kendi WordPress panelinizin adresini yazın. Genel şablon için
[03-claude-master-promptu-mind-mape-aktar.md](03-claude-master-promptu-mind-mape-aktar.md) dosyasına bakın.

Claude'da bu prompt bir **Claude Projesi**'nin açıklamasıyla birlikte kullanıldı. Önce o açıklama, sonra prompt:

## Claude Projesi açıklaması

```text
PROJE AÇIKLAMASI (Claude Projesi: "AI WordPress Oto Servis Web Sitesi – Mind Map ile Otomatik Kurulum")

Bu projenin amacı, bir oto servis / oto bakım işletmesi için profesyonel bir WordPress web sitesi oluşturma sürecini baştan sona bir Mind Map içerisinde planlamaktır.

Bu Mind Map daha sonra Claude tarafından bir uygulama rehberi ve proje talimatı olarak kullanılacaktır.

Claude ilerleyen aşamada tarayıcı üzerinden WordPress yönetim panelini kullanarak siteyi oluşturacaktır. Ancak bu ilk görevde WordPress sitesinde hiçbir işlem yapılmayacaktır. İlk görev yalnızca mevcut Mind Map eklentisi içerisinde projenin eksiksiz planını oluşturmaktır.
```

## Master Prompt

```text
==================================================
MASTER PROMPT'U MIND MAP'E EKLE
==================================================
ÇOK ÖNEMLİ:
Bu projede sana verdiğim bu MASTER PROMPT sadece geçici bir sohbet
talimatı değildir.
Bu Master Prompt aynı zamanda oluşturacağın Mind Map'in içerisinde
saklanmalıdır.
Mind Map içerisinde açıkça görülebilen bir ana bölüm oluştur:
"MASTER PROMPT / CLAUDE PROJE TALİMATLARI"
Bu bölümün içerisine bu projede sana verdiğim Master Prompt'un
TAMAMINI ekle.
Master Prompt'u özetleme.
Önemli maddeleri çıkarma.
Talimatları kısaltma.
Master Prompt'un tamamı Mind Map içerisinde saklanmalıdır.
Amaç:
İleride Claude veya başka bir yapay zeka bu Mind Map'i açtığında,
önce Master Prompt'u okuyarak:
- Projenin amacını
- Web sitesinin Türkçe olacağını
- Hangi sayfaların oluşturulacağını
- Hangi eklentilerin kurulacağını
- Hangi temanın kullanılacağını
- Mockup sürecini
- Mockup onay noktasını
- WordPress kurulum sırasını
- Elementor kullanım şeklini
- Menü yapısını
- Yedekleme sürecini
- Kalite kontrol kurallarını
- Otonom çalışma kurallarını
tam olarak anlayabilmelidir.
==================================================
MIND MAP YAPISI
==================================================
Mind Map içerisinde en az iki ana bölüm bulunmalıdır:
1. MASTER PROMPT / CLAUDE PROJE TALİMATLARI
Burada bu Master Prompt'un tamamını sakla.
2. PROJE UYGULAMA PLANI
Burada Master Prompt'u uygulanabilir Mind Map adımlarına dönüştür.
Uygulama planının ana akışı:
PROJE BAŞLANGICI
↓
PROJE PLANLAMASI
↓
WEB SİTESİ YAPISI
↓
SAYFALAR
↓
MENÜ YAPISI
↓
HTML MOCKUP TASARIMI
↓
MOCKUP ONAYI
↓
WORDPRESS'E GİRİŞ
↓
WPVIVID KURULUMU
↓
İLK YEDEK
↓
KADENCE KURULUMU
↓
ELEMENTOR KURULUMU
↓
SAYFALARIN OLUŞTURULMASI
↓
MENÜNÜN OLUŞTURULMASI
↓
ELEMENTOR + HTML UYGULAMASI
↓
MOBİL UYUMLULUK
↓
KALİTE KONTROL
↓
SON YEDEK
↓
SON RAPOR
↓
PROJE TAMAMLANDI
==================================================
MIND MAP'İN AMACI
==================================================
Bu Mind Map yalnızca görsel bir proje planı değildir.
Bu Mind Map aynı zamanda projenin:
- Dokümantasyonu
- Yol haritası
- Claude çalışma talimatı
- Uygulama kontrol listesi
- Proje hafızası
olarak kullanılacaktır.
Bu nedenle Mind Map tek başına açıldığında projenin nasıl
gerçekleştirileceği anlaşılabilmelidir.
İleride yeni bir Claude oturumu açıldığında, yalnızca bu Mind Map
okunarak projeye devam edilebilmesi hedeflenmektedir.
==================================================
ŞİMDİ YAPILACAK İŞ
==================================================
Şu anda WordPress sitesini oluşturma.
Öncelikle:
1. Mevcut Mind Map sistemini aç.
2. Yeni projeyi oluştur.
3. Proje adını:
   "OTO SERVİS VE ARAÇ BAKIM WEB SİTESİ"
   olarak belirle.
4. Master Prompt'un tamamını Mind Map'e ekle.
5. Master Prompt'tan yola çıkarak proje uygulama planını oluştur.
6. Gerekli alt dalları ve görevleri ekle.
7. Bütün Mind Map'in Türkçe olduğundan emin ol.
8. Mind Map'in eksiksiz olduğunu kontrol et.
9. İşlem tamamlandığında DUR.
10. Bana oluşturduğun Mind Map'i göster.
BEN ONAY VERMEDEN WORDPRESS WEB SİTESİNİ OLUŞTURMAYA BAŞLAMA.

Link : [WORDPRESS PANELİNİZİN ADRESİ, örn. https://siteniz.com/wp-admin/]
```
