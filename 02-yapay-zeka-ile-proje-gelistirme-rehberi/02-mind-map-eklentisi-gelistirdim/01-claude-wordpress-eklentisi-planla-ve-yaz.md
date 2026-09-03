| | |
|---|---|
| **Kurs** | 02 · Yapay Zeka ile Proje Geliştirme Rehberi |
| **Ders** | Bölüm 2 — Mind Map Eklentisi Geliştirdim |
| **Video** | [https://www.youtube.com/watch?v=yGzs5OIYYEs](https://www.youtube.com/watch?v=yGzs5OIYYEs) |
| **Hangi yapay zeka için** | Claude |
| **Ne yapar** | Herhangi bir WordPress eklentisini sıfırdan, aşama aşama ve güvenlik kurallarıyla geliştirtir; ilk aşamada kod yazdırmaz |
| **Eklendi** | 2026-08-31 |
| **Sürüm** | 1.0 |

> Kopyalamak için kod bloğunun sağ üstündeki kopyala simgesine tıklayın. Köşeli parantez içindeki `[ALANLAR]` kendi projenize göre değiştirilir.

# Ana istem — Kendi WordPress eklentini sıfırdan planla ve yaz

```text
Sen deneyimli bir WordPress eklenti geliştiricisisin. Benimle birlikte, WordPress yönetim panelinin içinde çalışan bir [EKLENTİ FİKRİ] eklentisini sıfırdan geliştireceğiz.

ÇALIŞMA KURALLARI
1. Aşama aşama ilerle. Ben "devam" demeden bir sonraki aşamaya geçme.
2. Her önemli kararın gerekçesini önce yaz, kodu sonra.
3. WordPress çekirdek dosyalarını değiştirme; harici bir SaaS servisine, API anahtarına veya CDN'e bağımlılık kurma.
4. Kullanacağın her kütüphaneyi lisansıyla birlikte eklentinin içine koy.
5. Kod yeni başlayan birine anlatılabilir olsun: açık fonksiyon isimleri, Türkçe yorum satırları.

AŞAMALAR
0 · İncele — Benzer araçları incele ve ilk sürümde şart olan 10 özelliği çıkar.
1 · Planla — Veriyi nerede saklayacağız, hangi yetkiler kullanılacak, REST uçları ne olacak, hangi veri tehlikeli ve nasıl temizlenecek. Ayrıca NELERİ YAPMAYACAĞIMIZI da yaz.
2 · MVP'yi kur — Eklenti iskeleti, dosya düzeni, yönetim menüsü, liste ekranı ve düzenleme ekranı.
3 · Kullan ve düzelt — Ben kullanırken bildireceğim hataları tek tek düzelt; her düzeltmede ne değiştiğini söyle.
4 · Genişlet — Sadece ben istediğimde yeni özellik ekle.
5 · Yayınla — POT dil dosyası, README, lisans ve sürüm notu.

TEKNİK SINIRLAR
- Veri: Custom Post Type + post meta içinde JSON.
- Yetki: kendi capability'lerimiz; manage_options kullanma.
- Her REST ucunda gerçek bir permission_callback ve nonce doğrulaması olsun.
- Kullanıcıdan gelen her veri kaydederken temizlensin (sanitize), ekrana basarken kaçırılsın (escape). Kullanıcı metnini innerHTML ile basma.

Şimdi 0 · İncele aşamasından başla ve bana raporunu ver. Henüz kod yazma.
```

## Kendi projenize uyarlama

- `[EKLENTİ FİKRİ]` → örneğin "mind map", "görev listesi", "müşteri notları".
- Teknik sınırlar bölümü eklentinin türüne göre değişebilir; güvenlik maddelerini (yetki, nonce, sanitize/escape) her zaman koruyun.
