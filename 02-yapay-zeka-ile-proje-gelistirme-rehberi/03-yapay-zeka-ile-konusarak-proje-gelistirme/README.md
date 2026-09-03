# Bölüm 3 — Yapay Zeka ile Konuşarak Proje Geliştirme | ChatGPT ile Master Prompt, Claude ile Mind Map

- Video: Yayın: 4 Eylül 2026, 13:00 — bağlantı yayından sonra eklenecek
- Sitede: [https://fbsoftwaresolutions.com.tr/tutorials/yapay-zeka-ile-konusarak-proje-gelistirme/](https://fbsoftwaresolutions.com.tr/tutorials/yapay-zeka-ile-konusarak-proje-gelistirme/)

Bu derste yapay zekayı gerçek bir projeyi baştan sona planlamak ve geliştirmek için kullanıyoruz — üstelik uzun uzun
prompt yazmak yerine ChatGPT ile **canlı olarak konuşarak**. Kafamdaki proje fikrini ChatGPT'ye anlatıyorum;
ChatGPT eksikleri tamamlayıp bunu Claude'un kullanabileceği bir **Master Prompt**'a dönüştürüyor. Claude bu
Master Prompt'u önce Mind Map'e aktarıyor (proje planı, yol haritası, talimatlar, kontrol listesi ve proje hafızası),
sonra WordPress'e dokunmadan HTML mockup hazırlıyor, onayımızı bekliyor ve ancak onaydan sonra WordPress kurulumuna geçiyor.

Örnek proje: bir oto servis ve araç bakım web sitesi. Akış:

**Konuşma → Planlama → Master Prompt → Mind Map → Mockup → Onay → WordPress Uygulaması**

## Bu dersteki promptlar (kullanım sırasıyla)

| Sıra | Dosya | Yapay zeka | Ne yapar |
|---|---|---|---|
| 01 | [01-chatgpt-konusmayi-master-prompta-donustur.md](01-chatgpt-konusmayi-master-prompta-donustur.md) | ChatGPT (sesli) | Sesli anlattığınız proje fikrini sorularla tamamlayıp Claude için bir Master Prompt'a çevirir |
| 02 | [02-claude-master-prompt-oto-servis-ornek.md](02-claude-master-prompt-oto-servis-ornek.md) | Claude | Videoda kullandığım **gerçek Master Prompt** — oto servis örnek projesi; Claude'a Master Prompt'u Mind Map'e kelimesi kelimesine eklemesini ve uygulama planını çıkarmasını söyler |
| 03 | [03-claude-master-promptu-mind-mape-aktar.md](03-claude-master-promptu-mind-mape-aktar.md) | Claude | 02'nin genel, her projeye uyarlanabilir şablon hali |
| 04 | [04-claude-yeni-oturumda-devam-et.md](04-claude-yeni-oturumda-devam-et.md) | Claude | Yeni bir oturumda Mind Map'i okutup projeye kaldığı yerden devam ettirir |

Gerekli eklenti: [FB Mind Map](https://github.com/fatihborasoftware-sudo/fb-mind-map) ([son sürüm](https://github.com/fatihborasoftware-sudo/fb-mind-map/releases/latest)).
