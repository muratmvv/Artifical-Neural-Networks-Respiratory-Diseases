# Artifical-Neural-Networks-Respiratory-Diseases

Solunum Ses Sınıflandırması CNN ve GRU Projesi
Proje Hakkında
Bu proje, Convolutional Neural Networks (CNN) ve Gated Recurrent Units (GRU) mimarilerini kullanarak solunum seslerini sınıflandırmayı amaçlamaktadır. Solunum seslerinin doğru şekilde analiz edilmesi, astım, bronşit veya zatürre gibi solunum yolu hastalıklarının erken teşhisinde kritik bir rol oynar. Projemiz, bu süreçte makine öğrenmesi ve derin öğrenme yöntemlerinden faydalanmaktadır.

Özellikler
Veri Toplama: Solunum seslerinin toplandığı açık kaynak veri setleri (örneğin, ICBHI 2017 Challenge veri seti) kullanıldı.
Özellik Çıkarımı: MFCC (Mel-Frequency Cepstral Coefficients) ve spektrogramlar kullanılarak ses sinyallerinden anlamlı özellikler çıkarıldı.
Model Mimarisi:
CNN: Spektrogramlardan uzaysal özellikleri öğrenmek için kullanıldı.
GRU: Zaman serisi verilerinin sıralı yapısını öğrenmek için tercih edildi.
Sınıflandırma: Normal solunum sesleri ile anormal solunum sesleri (örneğin, hırıltı, ronküs) arasında sınıflandırma yapıldı.
Model Performansı: Doğruluk, hassasiyet ve F1 skoru gibi metriklerle değerlendirildi.
Gelecekteki Çalışmalar
Daha büyük ve çeşitli veri setleriyle test edilmesi.
Gerçek zamanlı sınıflandırma için mobil ve gömülü sistemlere entegrasyon.



Respiratory Sound Classification using CNN and GRU
About the Project
This project aims to classify respiratory sounds using Convolutional Neural Networks (CNN) and Gated Recurrent Units (GRU). Accurate analysis of respiratory sounds plays a crucial role in the early diagnosis of respiratory diseases such as asthma, bronchitis, or pneumonia. The project leverages machine learning and deep learning techniques to achieve this goal.

Features
Data Collection: Open-source datasets of respiratory sounds (e.g., ICBHI 2017 Challenge) were utilized.
Feature Extraction: Meaningful features were extracted from sound signals using MFCC (Mel-Frequency Cepstral Coefficients) and spectrograms.
Model Architecture:
CNN: Used to learn spatial features from spectrograms.
GRU: Applied for capturing the sequential structure of time-series data.
Classification: Differentiated between normal and abnormal respiratory sounds (e.g., wheezing, crackles).
Model Performance: Evaluated using metrics like accuracy, precision, and F1 score.
Future Work
Testing with larger and more diverse datasets.
Integration into mobile and embedded systems for real-time classification.
