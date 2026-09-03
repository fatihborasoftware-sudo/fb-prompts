| | |
|---|---|
| **Kurs** | 02 · Yapay Zeka ile Proje Geliştirme Rehberi |
| **Ders** | Bölüm 3 — Konuşarak Proje Geliştirme |
| **Video** | Yayın: 4 Eylül 2026, 13:00 — bağlantı yayından sonra eklenecek |
| **Hangi yapay zeka için** | ChatGPT (sesli konuşma modu) |
| **Ne yapar** | Sesli anlattığınız dağınık proje fikrini yapılandırır, eksikleri sorar ve Claude için bir Master Prompt üretir |
| **Eklendi** | 2026-09-03 |
| **Sürüm** | 1.0 |

> Kopyalamak için kod bloğunun sağ üstündeki kopyala simgesine tıklayın. Köşeli parantez içindeki `[ALANLAR]` kendi projenize göre değiştirilir.

# ChatGPT için — Konuşmamı Master Prompt'a dönüştür

Bu promptu sesli konuşmaya başlamadan önce ChatGPT'ye yazılı olarak verin, sonra mikrofonu açıp projeyi anlatın.

```text
Şimdi seninle sesli olarak bir yazılım projesi hakkında konuşacağım. Ben projeyi normal bir insana anlatır gibi, dağınık ve eksik olabilecek şekilde anlatacağım. Senin görevin:

1. Anlattıklarımı dikkatle dinlemek ve düzenli bir yapıya oturtmak.
2. Eksik veya belirsiz gördüğün noktaları bana tek tek sormak (hedef kitle, sayfalar, tema, eklentiler, kurulum sırası, onay noktaları, yasaklar).
3. Konuşma bittiğinde, Claude adlı bir yapay zeka geliştirme aracına vereceğim PROFESYONEL BİR MASTER PROMPT hazırlamak.

Master Prompt şu bölümleri içermeli:
- Proje adı ve tek cümlelik amaç
- Hedef kitle ve dil (site Türkçe olacak)
- Sayfa listesi ve her sayfanın içeriği
- Teknik yığın: WordPress + [tema] + [eklentiler]
- Çalışma sırası (adım adım, numaralı)
- Onay noktaları: hangi adımda durup benden onay isteyeceği
- Kesin kurallar: neyi yapmayacağı
- Teslim biçimi: önce Mind Map, sonra HTML mockup, sonra WordPress

Bitirdiğinde Master Prompt'u tek bir kod bloğu içinde, kopyalamaya hazır şekilde ver.
```
