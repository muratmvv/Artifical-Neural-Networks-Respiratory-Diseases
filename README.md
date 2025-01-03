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
