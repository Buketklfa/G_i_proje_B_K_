# G_i_proje_B_K_
# Hayvan Türlerini Sınıflandırma Projesi

Bu proje, çeşitli hayvan türlerini sınıflandırmak için bir Convolutional Neural Network (CNN) modeli oluşturmayı amaçlamaktadır. Proje, Aygaz Görüntü İşleme Bootcamp kapsamında gerçekleştirilmiştir.

Kaggle [https://www.kaggle.com/code/buketkalfa/g-i-proje-bk]

## Proje Adımları

### 1. Veri Setini Kullanma
- Veri seti, Kaggle üzerinde bulunan "Animals with Attributes 2" veri setidir.
- JPEGImages klasöründe 50 farklı hayvan sınıfı bulunmaktadır.
- Projede yalnızca 10 sınıf kullanılacaktır: collie, dolphin, elephant, fox, moose, rabbit, sheep, squirrel, giant panda ve polar bear.

### 2. Veri Setini Hazırlama
- Her sınıftan yalnızca ilk 650 resim kullanılmıştır.
- Tüm resimler 128x128 boyutuna getirilmiş ve normalize edilmiştir.
- Veriler eğitim (%70) ve test (%30) olarak ikiye ayrılmıştır.

### 3. CNN Modelinin Tasarlanması
- 10 hayvan sınıfını ayırt edecek bir CNN modeli tasarlanmıştır.
- Modelde kullanılan katmanlar: Convolution, Activation, Pooling, Fully Connected, Dropout.
- Kullanılan kayıp fonksiyonu: categorical_crossentropy.

### 4. Modelin Test Edilmesi
- Model, test verisiyle test edilmiştir.
- Modelin başarısı (accuracy) değerlendirilmiştir.

### 5. Resimlerin Farklı Işıklar ile Manipüle Edilmesi
- Test resimleri farklı ışık koşulları ile manipüle edilmiştir.

### 6. Modelin Manipüle Edilmiş Test Seti ile Denenmesi
- Model, manipüle edilmiş test seti ile test edilmiştir.
- Başarı oranı kaydedilmiştir.

### 7. Manipüle Edilmiş Test Setine Renk Sabitliği Algoritması Uygulanması
- Manipüle edilmiş test setine renk sabitliği algoritması uygulanmıştır.

### 8. Modelin Renk Sabitliği Uygulanmış Test Seti ile Denenmesi
- Model, renk sabitliği uygulanmış test seti ile test edilmiştir.
- Başarı oranı kaydedilmiştir.

### 9. Farklı Test Setlerinin Başarılarını Karşılaştırma ve Raporlama
- Üç farklı test setinin başarıları karşılaştırılarak raporlanmıştır.
- Çözüm önerileri sunulmuştur.

## Kullanılan Kütüphaneler
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

## Nasıl Çalıştırılır
1. Proje dosyalarını indirin ve gerekli kütüphaneleri yükleyin.
2. Veri setini indirin ve belirtilen klasör yapısına yerleştirin.
3. Notebook dosyasını çalıştırarak adımları takip edin.

## Sonuçlar
- Modelin eğitim ve test sonuçları değerlendirilmiştir.
- Manipüle edilmiş ve renk sabitliği uygulanmış test setleri ile modelin performansı karşılaştırılmıştır.

## Katkıda Bulunanlar
- Diclehan ve Oğuzhan Ulucan

## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır.
