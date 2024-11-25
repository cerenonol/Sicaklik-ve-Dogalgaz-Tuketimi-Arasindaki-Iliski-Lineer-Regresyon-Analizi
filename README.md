# Sıcaklık ve Doğalgaz Tüketimi: Dönemsel Değişimlerin Lineer Regresyon Analizi

Bu proje, şehirlerin yıllık sıcaklık ortalamaları (yaz ve kış) ile doğalgaz tüketimi arasındaki ilişkiyi **lineer regresyon modeli** kullanarak incelemektedir. Yaz ve kış mevsimlerine ait sıcaklıklar, doğalgaz tüketimini nasıl etkilediği üzerinde derinlemesine bir analiz yapılmıştır.

## Proje Amacı
Bu çalışmanın amacı, farklı şehirlerin sıcaklık verilerine dayalı olarak, yaz ve kış mevsimlerinde doğalgaz tüketimi arasındaki ilişkiyi anlamaktır. Proje, iki ayrı dönemi (yaz ve kış) ele alarak her bir dönemin doğalgaz tüketimi üzerindeki etkilerini analiz etmektedir.

## Kullanılan Yöntem
- **Lineer Regresyon**: Sıcaklık verilerini kullanarak doğalgaz tüketiminin tahmin edilmesi.
- **Veri Görselleştirme**: Yaz ve kış sıcaklıklarının doğalgaz tüketimi üzerindeki etkisini görselleştiren grafikler.

## Kullanılan Teknolojiler
- **Python**: Programlama dili
- **Pandas**: Veri işleme
- **Matplotlib**: Veri görselleştirme
- **scikit-learn**: Lineer regresyon modeli

## Veri Seti
Proje, Türkiye'deki çeşitli şehirlerin sıcaklık ve doğalgaz tüketimi verilerini kullanmaktadır. Şehirler için yaz ve kış sıcaklık ortalamaları ile doğalgaz tüketimi yüzdeleri yer almaktadır.

| Şehir      | Yaz Sıcaklık (°C) | Kış Sıcaklık (°C) | Doğalgaz Tüketimi (%) |
|------------|-------------------|-------------------|-----------------------|
| Eskişehir  | 24.3              | 4.3               | 15                    |
| İstanbul   | 26.7              | 8.7               | 27.60                 |
| Bursa      | 28                | 7.3               | 10.20                 |
| ...        | ...               | ...               | ...                   |

## Sonuçlar
Projede, yaz ve kış sıcaklıklarının doğalgaz tüketimi ile olan ilişkisi iki ayrı regresyon doğrusu ile analiz edilmiştir. Görselleştirmeler, sıcaklık artışlarının doğalgaz tüketimi üzerindeki etkilerini açıkça ortaya koymaktadır.

## Kurulum ve Çalıştırma
Projeyi kendi bilgisayarınızda çalıştırmak için gerekli kütüphaneleri yüklemek için aşağıdaki komutu kullanabilirsiniz:

```bash
pip install numpy pandas matplotlib scikit-learn


Bu **README.md** dosyası, projenizin amacını ve kullandığınız yöntemleri açık ve anlaşılır bir şekilde tanımlar. Aynı zamanda, görselleştirmeler ve sonuçlar hakkında kısa bir bilgi verir ve projeyi çalıştırmak için gerekli adımları belirtir.

