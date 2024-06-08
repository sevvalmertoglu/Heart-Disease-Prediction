# Kalp Hastalığı Veri Analizi Flask Uygulaması

Bu, kalp hastalığı veri setini analiz etmek için kullanılan bir Flask uygulamasıdır. Uygulama, kullanıcıların bir CSV dosyası yüklemesine, çeşitli veri analizi işlemlerini gerçekleştirmesine ve sonuçları görüntülemesine olanak tanır.

## Özellikler

- **Veri Seti Genel Bilgileri**: Veri setinin adı, örnek sayısı ve özellik sayısını görüntüler.
- **Kategorik ve Sayısal Değişkenlerin Belirlenmesi**: Kategorik ve sayısal değişkenleri belirler ve listeler.
- **Kategorik Değişken Analizi**: Kategorik değişkenler için frekans sayımlarını sağlar.
- **Sayısal Değişken Analizi**: Sayısal değişkenler için tanımlayıcı istatistikleri sağlar.
- **Hedef Değişken Analizi**: Hedef değişkeni (hem kategorik hem de sayısal) analiz eder.
- **Eksik Değer İşlemleri**: Eksik değerleri belirler ve görüntüler.
- **Kodlama**: Label Encoding, One-hot Encoding uygular.
- **Özellik Ölçeklendirme**: Özellikleri RobustScaler kullanarak ölçeklendirir.
- **Korelasyon Analizi**: Numerik verileri kullanarak Korelasyon analiz yapılır. 
- **Aykırı Değer Analizi**: IQR yöntemi ile aykırı değerleri tespit eder.
- **Makine Öğrenimi**: Random Forest yöntemi ile eğitildi, sınıflandırılma parametreleri ve confusion matrixine bakıldı.

## Kurulum

1. Depoyu klonlayın:
     
*  git clone https://github.com/betulaltunl/Heart-Disease-Prediction.git
2. Proje dizinine gidin:
 
   
* cd heart-disease-flask-app

3. Sanal ortamı etkinleştirin:
   
  On Windows:

* .\env\Scripts\activate
   
 On macOS and Linux:
  
* source env/bin/activate
  
   
4. Install the required dependencies:
   
* pip install -r requirements.txt

## Kullanım

1- Kalp hastalığı veri setini aşağıdaki linkden indirip bir CSV dosyası olarak kaydedin:

[Heart Disease Veri Seti](https://www.kaggle.com/datasets/thedevastator/predicting-heart-disease-risk-using-clinical-var)

2- Flask uygulamasını çalıştırın:

* flask run

3- Web tarayıcınızda görüntüleyin 

4- Sağlanan formu kullanarak CSV veri dosyanızı yükleyin ve hedef değişkeni belirtin.

## Proje Yapısı

![image](https://github.com/betulaltunl/Heart-Disease-Prediction/assets/101793578/00be0b24-1e1d-4742-b1f5-96ff976b820c)


- app.py: Ana Flask uygulama dosyası.

- templates/: HTML şablonlarını içeren dizin.

- index.html: Kullanıcıların veri setini yüklediği ana sayfa.

- result.html: Analiz sonuçlarının görüntülendiği sayfa.

- requirements.txt: Proje için gerekli Python paketlerinin listesi.

- README.md: Bu readme dosyası.

## Kalp Hastalığı Veri Analizi Python Kodu Linki
[Veri Analizi Python Kodu](https://www.kaggle.com/code/sevvalmertoglu/veri-analizi/notebook)

## Proje Sunumu Linki
[Sunum Linki](https://drive.google.com/file/d/1ghoJ9hUbEVPgi8Z2UD4rg-L24BR-ZGmn/view?usp=sharing)

## Proje Görselleri
<img width="600" alt="Ekran Resmi 2024-06-08 11 37 11" src="https://github.com/sevvalmertoglu/Heart-Disease-Prediction/assets/79595517/54adeaac-4cca-4649-81d8-4999ebaaf166">
<img width="600" alt="Ekran Resmi 2024-06-08 11 37 36" src="https://github.com/sevvalmertoglu/Heart-Disease-Prediction/assets/79595517/8f777b96-bb4d-4d51-b088-8b4c8da26caf">
<img width="600" alt="Ekran Resmi 2024-06-08 11 37 47" src="https://github.com/sevvalmertoglu/Heart-Disease-Prediction/assets/79595517/84ca5f40-589b-4f06-948c-2591af0ea823">


