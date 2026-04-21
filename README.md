# BMW Market Analizi & EDA Projesi

Bu çalışmam, ikinci el BMW piyasasındaki fiyatlandırma dinamiklerini anlamak ve veri setindeki istatistiksel aykırı değerlerin (outliers) arkasındaki gerçek hikayeyi çözmek için hazırlandı.
Projenin ayrıca bana kattıkları Basit Eda kavramlarını Basit bir proje üzerinden öğrenmekti.

###  Analiz Süreci
Sadece kod yazmakla kalmayıp, verinin fısıldadığı içgörüleri ortaya çıkardık:
* **Keşifçi Veri Analizi (EDA):** Pandas kütüphanesiyle binlerce satırlık veri setinde fiyat, model ve vites tipi gibi kritik değişkenler analiz edildi.
* **Veri Görselleştirme:** Matplotlib kullanılarak piyasanın fiyat dağılımı ve model bazlı değer haritası görselleştirildi.
* **Aykırı Değer (Outlier) Dedektifliği:** İstatistiksel olarak "hata" gibi duran yüksek fiyatlı araçlar mercek altına alındı.

###  Kritik Çıkarım
Analiz sonucunda tespit edilen **85.000£ üzerindeki** uç fiyatlı araçların bir veri girişi hatası değil; **BMW 8 Serisi, M4 ve özel üretim 2 Serisi** gibi markanın üst segment modelleri olduğu kanıtlanmıştır. Bu bulgu, veriye sadece matematiksel değil, sektörel bir vizyonla bakmanın önemini doğrulamıştır.

###  Kullanılan Araçlar
* **Dil:** Python
* **Kütüphaneler:** Pandas, Matplotlib
* **Ortam:** Jupyter Notebook / Google Colab
