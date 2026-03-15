# 61616161

## GÖKANLAM Projesi – Giriş ve Motivasyon

İnsansız hava araçları, son on yılda hem askeri hem de sivil alanlarda kullanımı hızla genişleyen kritik bir teknoloji platformu hâline gelmiştir. Küresel İHA pazarının 2030 yılına kadar yıllık %15'i aşan bir büyüme oranıyla onlarca milyar dolar değere ulaşması öngörülmektedir [1]. Askeri alanda İHA sistemleri; keşif ve gözetleme (ISR), sınır devriyesi, hedef tespiti ve mühimmat sevkiyatı gibi kritik görevlerde yaygın biçimde kullanılmaktadır [2]. Sivil alanda ise kentsel hava taşımacılığı (UAM), paket teslimatı, altyapı denetimi, tarım ilaçlama ve arama-kurtarma operasyonları başlıca uygulama alanlarını oluşturmaktadır [3]. Türkiye'de sivil ve ticari amaçlı kayıtlı İHA sayısı her yıl önemli ölçüde artmakta; bu durum, güvenli ve özerk İHA operasyonlarına yönelik yazılım altyapısına olan ihtiyacı giderek derinleştirmektedir [4].

Bu genişlemenin beraberinde getirdiği en kritik teknik zorlukların başında GPS sinyalinin güvenilir olmadığı ortamlarda (kentsel kanyonlar, elektromanyetik gürültü, kasıtlı sinyal engelleme) otonom navigasyonun sürdürülmesi gelmektedir. Öte yandan yoğun yağış, sis, kar ve güneş parlaması gibi olumsuz hava koşullarının bilgisayarlı görü algoritmalarının doğruluk ve güvenilirliğini ciddi biçimde düşürdüğü literatürde belgelenmiştir [5]. Mevcut sistemlerin büyük çoğunluğu bu zorlukları ayrı ayrı ele alan modüler mimarilerle çözmeye çalışmakta; ancak nesne tespiti, konum kestirimi ve tanımlanmamış nesne eşleme yeteneklerini tek bir donanım üzerinde entegre biçimde sunan bütünleşik bir mimari hâlâ literatürde karşılanmamış bir boşluk oluşturmaktadır. GÖKANLAM projesi bu boşluğu doldurmayı hedeflemektedir.

---

## Kaynaklar

[1] MarketsandMarkets, "Drone Market by Solution, Type, Application, End Use, and Geography – Global Forecast to 2030," MarketsandMarkets Research Pvt. Ltd., 2022. [Çevrimiçi]. Erişim: https://www.marketsandmarkets.com/Market-Reports/commercial-drones-market-195175890.html

[2] P. G. Fahlstrom ve T. J. Gleason, *Introduction to UAV Systems*, 4. baskı. Chichester, Birleşik Krallık: Wiley, 2012.

[3] A. Hassanalian ve A. Abdelkefi, "Classifications, applications, and design challenges of drones: A review," *Progress in Aerospace Sciences*, c. 91, ss. 99–131, May. 2017.

[4] Sivil Havacılık Genel Müdürlüğü (SHGM), "İnsansız Hava Aracı (İHA) İstatistikleri," T.C. Ulaştırma ve Altyapı Bakanlığı, Ankara, 2023. [Çevrimiçi]. Erişim: https://www.shgm.gov.tr/tr/insansiz-hava-araci

[5] M. Bijelic, T. Gruber, F. Mannan, F. Kraus, W. Ritter, K. Dietmayer, ve F. Heide, "Seeing Through Fog Without Seeing Fog: Deep Multimodal Sensor Fusion in Unseen Conditions," *Proc. IEEE/CVF Conf. Computer Vision and Pattern Recognition (CVPR)*, Seattle, WA, ABD, 2020, ss. 11682–11692.