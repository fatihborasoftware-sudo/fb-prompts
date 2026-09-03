| | |
|---|---|
| **Kurs** | 02 · Yapay Zeka ile Proje Geliştirme Rehberi |
| **Ders** | Bölüm 4 — Claude WordPress Sitesini Canlı Kuruyor |
| **Video** | [https://www.youtube.com/watch?v=FS_Cnoe0sHk](https://www.youtube.com/watch?v=FS_Cnoe0sHk) (yayın: 4 Eylül 2026, 05:00) |
| **Hangi yapay zeka için** | Claude |
| **Ne yapar** | Mockup onayı: hangi versiyonla devam edileceğini söyler ve Claude'u WordPress kurulumuna geçirir (giriş → WPvivid yedek → Kadence → Elementor → sayfalar → menü) |
| **Eklendi** | 2026-09-04 |
| **Sürüm** | 1.0 |

> Kopyalamak için kod bloğunun sağ üstündeki kopyala simgesine tıklayın. Köşeli parantez içindeki `[ALANLAR]` kendi projenize göre değiştirilir.

# Claude için — Mockup onayı ve WordPress kurulumuna geçiş

Master Prompt'ta "önce mockup, onaydan sonra WordPress" dediğimiz için Claude bu mesajı bekler. Onay geldiğinde
"Mockup approved, moving to the WordPress build" der ve Chrome üzerinden WordPress paneline girer: genel ayarlar,
kalıcı bağlantılar, WPvivid ile yedek, Elementor, Kadence teması, iletişim formu, sayfalar, menü, mobil uyum ve son yedek.
Bu yöntem ekran görüntüsü ala ala ilerlediği için çok token harcar; ilk kurulum 10–40 dakika sürebilir.

```text
Please use the light theme for the WordPress build and proceed.
```

Türkçesi:

```text
WordPress kurulumu için açık temayı kullan ve devam et.
```

Kurulum bitince mutlaka kontrol edin: videoda Claude iletişim sayfasına **uydurma bir telefon numarası** yazdı.
Gerçek iletişim bilgilerini Master Prompt'a ya da Mind Map'e ekleyin.
