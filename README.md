# Steam Oyun Piyasası ve Oyuncu Etkileşimleri Analiz Raporu

Bu proje, Steam platformuna ait geniş ölçekli bir veri seti üzerinden oyun piyasasının dinamiklerini, fiyatlandırma stratejilerini ve oyuncu kitlelerinin memnuniyet oranlarını incelemek amacıyla hazırlanmıştır. 

Proje kapsamında gerçekleştirilen veri analitiği süreçleri, tanımsal istatistikler ve görselleştirmeler,kod blokları ve grafikler bir arada olacak şekilde raporlaştırılmıştır.

## 🔗 Proje Bağlantıları
* **Yayınlanmış Canlı Rapor (GitHub Pages):** [Canlı Web Sitesini Açmak İçin Tıklayın] (https://esmaozturkmen.github.io/STEAMVERIANALIZI-VABP2/)
* **GitHub Kaynak Deposu (Repository):** [Proje Dosyalarına Gitmek İçin Tıklayın](https://github.com/ESMAOZTURKMEN/STEAMVERIANALIZI-VABP2)

## 📊 Veri Seti ve Değişkenler
Analizde kullanılan `steam.csv` veri seti toplam 27.075 satır ve 18 sütundan oluşmaktadır. İşlenen temel değişkenler şunlardır:
* `name`: Oyunun resmi adı (Kategorik)
* `developer`: Oyunu geliştiren şirket (Kategorik)
* `price`: Satış fiyatı (£ - Sayısal)
* `positive_ratings` / `negative_ratings`: Oyuncu yorum sayıları (Sayısal)
* `average_playtime`: Ortalama oynanma süresi (Dakika - Sayısal)

## 🛠️ Kullanılan Teknolojiler
* **Programlama Dili:** Python
* **Kütüphaneler:** Pandas, NumPy, Matplotlib, Seaborn
* **Raporlama:** Jupyter Notebook & NBConvert (HTML Export)
