# Dosyalama kuralları

Bu depo sitedeki kurs ağacının aynasıdır. Yeni bir ders eklenirken **hiçbir mevcut dosya taşınmaz**;
sadece yeni klasör ve dosyalar eklenir. Böylece eski videolardaki bağlantılar hep çalışır.

## Klasör yapısı

```
NN-kurs-slug/                 ← kurs (sitedeki kurs slug'ı, oluşturulma sırasına göre numaralı)
  README.md                   ← kurs açıklaması + ders listesi
  NN-ders-slug/               ← ders (kurs içindeki Sıra numarası + sitedeki ders slug'ı)
    README.md                 ← ders başlığı, video bağlantısı, promptların kullanım sırası
    NN-promptun-adi.md        ← prompt (videoda kullanıldığı sıra + kısa ad)
```

## Adlandırma

- Bütün numaralar iki basamaklı: `01`, `02`, … `99`.
- Sadece küçük harf, rakam ve tire. Türkçe karakter yok (ş→s, ı→i, ğ→g, ü→u, ö→o, ç→c), boşluk yok.
- Kurs ve ders klasör adları sitedeki URL slug'ı ile aynıdır; böylece site ile depo arasında arama yapmak kolaydır.
- Prompt dosya adı promptun **ne için** olduğunu söyler, hangi yapay zeka için olduğunu değil
  (o bilgi dosyanın içindeki tabloda yazar). Örnek: `01-chatgpt-konusmayi-master-prompta-donustur.md`.
- Promptu olmayan ders de klasör ve `README.md` alır; ağaç sitedeki bütün dersleri gösterir.

## Prompt dosyasının içi

1. Üstte tablo: Kurs, Ders, Video, Hangi yapay zeka için, Ne yapar, Eklendi, Sürüm.
2. Promptun tamamı tek bir kod bloğu içinde (```text). Özet yok, kısaltma yok.
3. Değiştirilecek yerler `[KÖŞELİ PARANTEZ]` ile işaretlenir.
4. Prompt sonradan iyileştirilirse sürüm numarası artar ve dosyanın altına **Değişiklikler** bölümü eklenir
   (tarih + ne değişti). Eski videoyu izleyen biri promptun değiştiğini böyle anlar.

## Yeni ders ekleme sırası

1. Ders sitede yayınlanır (Dersler → yeni ders, Kurs + Sıra seçilir).
2. Aynı gün bu depoya ders klasörü, `README.md` ve prompt dosyaları eklenir.
3. Dersin **Downloads** kutusuna bu depodaki ders klasörünün bağlantısı konur.
4. Kurs `README.md` içindeki ders listesi güncellenir.
