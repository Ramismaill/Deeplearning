# FET312 - Derin Öğrenme Projesi: [Görüntülerden Hava Durumu Tespiti (Weather Classification)]

**Ders:** FET312 Derin Öğrenme  
**Dönem:** 2025-2026 Güz  

##  Ekip Bilgileri

**Ekip Adı:** [DevDL]

| Adı Soyadı | Öğrenci No | E-Posta | Kullanılan Model |
|-----------|-----------|--------|------------------|
| Mehmet Oytun ÖZER | 23040301043  | mehmetoytunozer@stu.topkapi.edu.tr | VGG16 - MobileNetV2 |
| Furkan Işık | 23040301063 | furkanisik1@stu.topkapi.edu.tr | ResNet50 - InceptionV3 |
| Ram Ismail  | 24040301052 | ramismail@stu.topkapi.edu.tr | EfficientNetB0 - EfficientNetB4 |
| Muhammet Ay | 23040301137 | muhammetay@stu.topkapi.edu.tr | DenseNet121 - RegNetX-8GF |



##  Proje Açıklaması

Bu proje, görüntülerden hava durumunu (güneşli, yağmurlu, bulutlu ve gün doğumu) 
otomatik olarak tespit edebilen bir derin öğrenme modeli geliştirmeyi amaçlamaktadır.

Günlük hayatta hava tahmini çoğunlukla sensör ve radar tabanlı sistemler kullanılarak 
gerçekleştirilmektedir. Bu çalışmada ise yalnızca görsel veriler 
(sosyal medya fotoğrafları, uydu görüntüleri ve trafik kameraları gibi) kullanılarak, 
sensörsüz bir hava durumu tahmin yaklaşımı sunulmaktadır.

Modeller, Evrişimli Sinir Ağları (CNN) ve transfer learning yöntemleri kullanılarak 
VGG16, MobileNetV2, ResNet50, InceptionV3, EfficientNetB0, EfficientNetB4, 
DenseNet121 ve RegNetX-8GF mimarileri ile eğitilmiştir.  
Model performansı Accuracy, Precision, Recall ve F1-score metrikleri ile değerlendirilmiştir.

Bu sistemin; enerji planlaması, tarım uygulamaları ve çevresel gözlem 
gibi alanlarda görsel tabanlı hava durumu analizine katkı sağlaması hedeflenmektedir.

Kullanılan modeller:
- VGG16
- MobileNetV2
- ResNet50
- InceptionV3
- EfficientNetB0
- EfficientNetB4
- DenseNet121
  RegNetX-8GF

---

##  Kullanılan Teknolojiler

- Python
- PyTorch / TensorFlow
- NumPy
- Matplotlib
- Scikit-learn

---

##  Değerlendirme Metrikleri

- Accuracy
- Precision
- Recall
- F1-Score


---

##  Dataset

Bu projede kullanılan veri seti, farklı hava koşullarını temsil eden görsellerden oluşmaktadır.  
Veri setine aşağıdaki link üzerinden ulaşabilirsiniz:

🔗 [Multiclass Weather Dataset – Kaggle](https://www.kaggle.com/datasets/pratik2901/multiclass-weather-dataset)

##  Proje Sunumu (YouTube)

Projenin detaylı anlatımını içeren sunum videosuna aşağıdaki bağlantıdan ulaşabilirsiniz:

🔗 https://www.youtube.com/YOUTUBE_VIDEO_LINKI



