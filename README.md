# DefectVision: NEU Metal Yüzey Hataları Sınıflandırıcı

Python 3.11 TensorFlow 2.15 Accuracy 94.63% License MIT

# Proje Özeti

Akbank Derin Öğrenme Bootcamp kapsamında geliştirilen bu proje, CNN mimarisi kullanarak endüstrideki metallerin yüzeylerinde oluşan hataları %94.63 doğruluk oranıyla sınıflandırmaktadır.

Proje Amacı

* Endüstriyel kalite kontrol için otomatik hata tespiti
* Derin öğrenme modellerinin endüstriyel uygulamaları
* CNN mimarilerinin performans değerlendirmesi

📈 Sonuçlar

* Test Accuracy	94.63%

* Training Accuracy	85.62%

* Validation Accuracy	90.56%

* Overfitting	Yok ✅

* # Sınıf Bazlı Performans
* Crazing	100.0% accuracy	90 samples
* Inclusion	100.0% accuracy	90 samples
* Patches	98.9%	accuracy 90 samples
* Pitted	98.9% accuracy	90 samples
* Rolled	100.0% accuracy	90 samples
* Scratches	100.0% accuracy	90 samples

* # Model Mimarisi

Model: "DefectVision_CNN"

├── Conv2D(32, (3,3)) + BatchNormalization + Dropout(0.3)

├── Conv2D(64, (3,3)) + BatchNormalization + Dropout(0.4)

├── Flatten()

├── Dense(128) + Dropout(0.5)

└── Dense(6, activation='softmax')

##  Veri Seti
Dataset: NEU Metal Surface Defects Data
Total Images: 1,800
Classes: 6
Image Size: 200x200 pixels


##  Veri Seti
Dataset: NEU Metal Surface Defects Data
Total Images: 1,800
Classes: 6
Image Size: 200x200 pixels
