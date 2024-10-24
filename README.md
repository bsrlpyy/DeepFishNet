# Büyük Ölçekli Balık Veri Setinde ANN ve CNN ile Görüntü Sınıflaması 🐟🦐🐠

[image](https://github.com/user-attachments/assets/ad6adfe7-4454-44d5-a075-ff3243d24ec8)


Kaggle Proje Linki: [FishDeepNet](https://www.kaggle.com/code/busraalpay/fishdeepnet/notebook)

**Proje Açıklaması**

Bu proje, büyük ölçekli bir balık veri seti kullanarak yapay sinir ağları (ANN) ve evrişimli sinir ağları (CNN) ile görüntü sınıflaması yapmayı amaçlamaktadır. Proje, farklı deniz ürünü türlerini sınıflandırmayı hedeflemekte olup, veri seti 9 farklı balık türünü içermektedir.


İçerik

	•	Çipura
	•	Mercan
	•	Levrek
	•	Barbunya
	•	İstavrit
	•	Karadeniz Çaçası
	•	Çizgili Barbunya
	•	Alabalık
	•	Karides

Her sınıf için 1000 adet artırılmış görüntü bulunmaktadır.

Kullanılan Teknolojiler

	•	Python
	•	Keras
	•	TensorFlow
	•	NumPy
	•	Matplotlib
	•	scikit-learn

**Model Yapısı**

Projemizde iki farklı model kullanılmıştır:

**1. Yapay Sinir Ağı (ANN**

Bu model, bir giriş katmanı, bir Flatten katmanı, 4 adet yoğun katman (1024, 512, 256 ve 128 nöron), 3 adet Dropout katmanı ve bir çıkış katmanından oluşmaktadır. Model, ‘adam’ optimizer ve ‘categorical_crossentropy’ kayıp fonksiyonu ile derlenmiştir.

**2. Evrişimli Sinir Ağı (CNN)**

CNN modeli, görüntülerin özelliklerini çıkarmak için evrişimli katmanlar ve ardından yoğun katmanlarla sınıflandırma yapmaktadır.

Eğitim Bilgileri

	•	Epoch Sayısı: 5- 10
	•	Kullanılan Donanım: GPU

Model Değerlendirme

Modellerin performansını değerlendirmek için aşağıdaki metrikler kullanılacaktır:

	•	Doğruluk (Accuracy)
	•	Kayıp Fonksiyonu Grafiği
	•	Confusion Matrix
	•	Classification Report




Kaynak
@inproceedings {ulucan2020large,
title={Balık Segmentasyonu ve Sınıflandırması İçin Büyük Ölçekli Bir Veri Seti},
author={Ulucan, Oguzhan ve Karakaya, Diclehan ve Turkan, Mehmet},
booktitle={2020 Akıllı Sistemler ve Uygulamalarında Yenilikler Konferansı (ASYU)},
pages={1--5},
year={2020},
organization={IEEE}
}

O.Ulucan, D.Karakaya ve M.Turkan.(2020) Balık segmentasyonu ve sınıflandırması için büyük ölçekli bir veri seti.
Conf. Innovations Intell. Syst. Appli. (ASYU)

Lisans

Bu proje Attribution 4.0 International (CC BY 4.0) lisansı altında lisanslanmıştır.
