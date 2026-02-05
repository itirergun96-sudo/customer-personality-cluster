# Customer Personality Analysis – Clustering

Bu projede, müşteri demografik ve davranışsal verileri kullanılarak kümeleme tabanlı bir müşteri segmentasyonu gerçekleştirilmiştir. 
Amaç, benzer özelliklere sahip müşterileri gruplandırarak pazarlama ve müşteri ilişkileri yönetimi süreçlerine katkı sağlayacak anlamlı müşteri segmentleri oluşturmaktır.

---

## Projenin Amacı
Bu çalışmanın amacı, müşteri verilerini kullanarak etiketsiz öğrenme (unsupervised learning) teknikleri ile müşteri segmentleri oluşturmak ve bu segmentleri iş perspektifinden yorumlamaktır.

---

## Kullanılan Veri Seti
Veri seti, müşterilerin demografik bilgilerini, ürün bazlı harcama alışkanlıklarını, satın alma kanallarını ve pazarlama kampanyalarına verdikleri tepkileri içermektedir.

---

## Kullanılan Yöntemler
- Keşifsel Veri Analizi (EDA)
- Veri Ön İşleme ve Özellik Mühendisliği
- StandardScaler ile Ölçekleme
- Elbow Yöntemi ve Silhouette Skoru
- KMeans Clustering
- Agglomerative Clustering
- PCA ile Boyut İndirgeme ve Görselleştirme

---

## Elde Edilen Sonuçlar
Analiz sonucunda, müşterilerin yaş, gelir düzeyi, hane yapısı, harcama miktarı ve kampanyalara verdikleri tepkiler açısından anlamlı şekilde ayrıştığı gözlemlenmiştir. 
Her iki kümeleme algoritması da benzer müşteri profilleri üretmiş ve elde edilen segmentlerin tutarlı olduğu görülmüştür.

---

## Gerçek Hayat Uygulaması
Oluşturulan müşteri segmentleri;
- Sadakat programlarının geliştirilmesi,
- Kişiselleştirilmiş pazarlama kampanyalarının tasarlanması,
- Yeniden kazanım (re-engagement) stratejilerinin planlanması

gibi iş süreçlerinde kullanılabilir.

---

## Dosya Yapısı
- `data/` : Veri seti
- `notebooks/` : Analiz ve modelleme süreci
- `models/` : Eğitilmiş modeller ve ön işleme nesneleri

---

## Kullanım
Kaydedilen modeller, Streamlit uygulaması veya Hugging Face Space üzerinde dağıtım için hazırdır. 
Bu sayede müşteri segmentasyonu modeli, gerçek zamanlı senaryolarda yeniden kullanılabilir.

---

## Sonuç
Bu proje, kümeleme tabanlı müşteri segmentasyonunun yalnızca teknik bir analiz değil, 
aynı zamanda iş kararlarını destekleyen stratejik bir araç olduğunu göstermektedir.
