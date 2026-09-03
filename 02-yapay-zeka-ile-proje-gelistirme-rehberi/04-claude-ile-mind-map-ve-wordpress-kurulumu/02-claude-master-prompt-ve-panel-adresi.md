| | |
|---|---|
| **Kurs** | 02 · Yapay Zeka ile Proje Geliştirme Rehberi |
| **Ders** | Bölüm 4 — Claude WordPress Sitesini Canlı Kuruyor |
| **Video** | [https://www.youtube.com/watch?v=FS_Cnoe0sHk](https://www.youtube.com/watch?v=FS_Cnoe0sHk) (yayın: 4 Eylül 2026, 05:00) |
| **Hangi yapay zeka için** | Claude (Claude in Chrome eklentisi kurulu) |
| **Ne yapar** | Projedeki ilk mesaj: Master Prompt'un tamamı + Claude'un Chrome eklentisiyle gireceği WordPress panelinin adresi; Claude Mind Map'i kurar ve onay bekler |
| **Eklendi** | 2026-09-04 |
| **Sürüm** | 1.0 |

> Kopyalamak için kod bloğunun sağ üstündeki kopyala simgesine tıklayın. Köşeli parantez içindeki `[ALANLAR]` kendi projenize göre değiştirilir.

# Claude için — Master Prompt + WordPress panel adresi (projedeki ilk mesaj)

Master Prompt'u (3. bölümde ChatGPT ile hazırladığınız prompt ya da
[oto servis örneği](../03-yapay-zeka-ile-konusarak-proje-gelistirme/02-claude-master-prompt-oto-servis-ornek.md))
sohbet kutusuna yapıştırın, **Shift+Enter** ile yeni satıra geçin ve panel adresini ekleyin. Claude ilk kez bu adrese
girerken "Allow Claude to use the browser in …" izni ister; videoda **Always allow** diyorum.

Önemli: Sitede FB Mind Map eklentisi kurulu ve aktif olmalı. Claude bu siteye gerçekten eklenti ve tema kuracağı için
müşteri sitesi değil, deneme sitesi kullanın (canlı sunucu ya da localhost fark etmez).

```text
[MASTER PROMPT'UN TAMAMINI BURAYA YAPIŞTIRIN]

WordPress paneli: https://[SİTENİZ]/wp-admin/
Bu adrese Chrome eklentisi ile gir. Sitede FB Mind Map eklentisi kurulu; Master Prompt'taki aşamaları önce bu eklentinin içinde Mind Map olarak oluştur. Mind Map bitince WordPress kurulumuna geçmeden önce benden onay bekle.
```
