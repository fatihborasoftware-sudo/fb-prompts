# Bölüm 4 — ChatGPT ile Master Prompt, Claude ile Mind Map #4 | Claude WordPress Sitesini Canlı Kuruyor

- Video: [https://www.youtube.com/watch?v=FS_Cnoe0sHk](https://www.youtube.com/watch?v=FS_Cnoe0sHk) (28:56 — yayın: 4 Eylül 2026, 05:00)
- Sitede: [https://fbsoftwaresolutions.com.tr/tutorials/claude-ile-mind-map-ve-wordpress-kurulumu/](https://fbsoftwaresolutions.com.tr/tutorials/claude-ile-mind-map-ve-wordpress-kurulumu/)
- Önceki ders: [Bölüm 3 — Yapay Zeka ile Konuşarak Proje Geliştirme](../03-yapay-zeka-ile-konusarak-proje-gelistirme/)

3. bölümde ChatGPT ile konuşarak hazırladığımız **Master Prompt**'u bu derste Claude'a veriyoruz ve Claude'un bir insan
gibi çalışmasını baştan sona canlı izliyoruz: önce WordPress panelindeki **FB Mind Map** eklentisinin içine girip projenin
bütün aşamalarını Mind Map olarak kuruyor, sonra HTML mockup hazırlayıp onay bekliyor, onaydan sonra Chrome üzerinden
WordPress'e giriyor ve siteyi gerçekten kuruyor: WPvivid yedek, Kadence, Elementor, iletişim formu, sayfalar, menü,
mobil uyum ve son yedek. Sonuç, yapay zekanın ürettiği bir HTML şablonu değil, Elementor widget'larıyla kurulmuş ve
panelden düzenlenebilen gerçek bir WordPress sitesi.

Örnek proje: oto servis ve araç bakım web sitesi. Akış:

**Master Prompt → Claude Projesi → Mind Map (WordPress panelinde) → HTML Mockup → Onay → WordPress Kurulumu → Elementor kontrolü**

## Bu dersteki promptlar (kullanım sırasıyla)

| Sıra | Dosya | Yapay zeka | Ne yapar |
|---|---|---|---|
| 01 | [01-claude-proje-aciklamasi.md](01-claude-proje-aciklamasi.md) | Claude (Projects) | Yeni proje açarken yazılan proje açıklaması |
| 02 | [02-claude-master-prompt-ve-panel-adresi.md](02-claude-master-prompt-ve-panel-adresi.md) | Claude + Chrome eklentisi | Master Prompt + WordPress panel adresi; Claude Mind Map'i kurar ve onay bekler |
| 03 | [03-claude-mockup-revizyonu-acik-koyu.md](03-claude-mockup-revizyonu-acik-koyu.md) | Claude | Mockup revizyonu: açık/koyu versiyon ve banner'lı hero |
| 04 | [04-claude-mockup-onayi-ve-wordpress-kurulumu.md](04-claude-mockup-onayi-ve-wordpress-kurulumu.md) | Claude | Mockup onayı ve WordPress kurulumuna geçiş |

Master Prompt'un kendisi 3. bölümün klasöründe:
[02-claude-master-prompt-oto-servis-ornek.md](../03-yapay-zeka-ile-konusarak-proje-gelistirme/02-claude-master-prompt-oto-servis-ornek.md)

Gerekli eklenti: [FB Mind Map](https://github.com/fatihborasoftware-sudo/fb-mind-map) ([son sürüm](https://github.com/fatihborasoftware-sudo/fb-mind-map/releases/latest)). Ayrıca Chrome'da [Claude in Chrome](https://claude.com/chrome) eklentisi kurulu olmalı.

Videodaki uyarılar: ilk Mind Map ve site kurulumu 10–40 dakika sürebilir; tarayıcı yöntemi çok token harcar (daha az
token kullanan Playwright yöntemi ayrı bir videoda); Claude'un yazdığı iletişim bilgilerini mutlaka kontrol edin.
