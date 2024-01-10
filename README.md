# Proje Başlığı

## Ders Bilgileri

- **Dersin Kodu:** [YAZ20411](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)
- **Dersin Adı:** [DERİN ÖĞRENME](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)
- **Dersin Öğretim Elemanı:** Öğr. Gör. Dr. Fatih BAL [Github](https://github.com/balfatih) | [Web Sayfası](https://balfatih.github.io/)

---

## Grup Bilgileri

| Öğrenci No | Adı Soyadı       | Bölüm                | Proje Grup No | Github Profili                             |
|------------|------------------|----------------------|---------------|--------------------------------------------|
| 1200505056 | Yeşim Demir      | Yazılım Mühendisliği | PROJE_4       | [Github](https://github.com/yesimdemir)    |
| 1200505026 | Musa Berk İşkal  | Yazılım Mühendisliği | PROJE_4       | [Github](https://github.com/mberkiskal)   |
| 1200505002 | Muhsin Öztüfekçi | Yazılım Mühendisliği | PROJE_4       | [Github](https://github.com/MuhsinOztufekci)|

---

## Proje Açıklaması

Bu proje, özel bir sınıflandırma görevini gerçekleştirmek için Convolutional Neural Network (CNN), Transfer Learning ve Yapay Sinir Ağı modellerini içermektedir. Projenin amacı, belirli bir veri kümesindeki nesneleri doğru bir şekilde sınıflandırmaktır.

### CNN Modeli Tasarımı

- Tasarlanan CNN modeli eğitilmiş ve performans metrikleri aşağıda listelenmiştir:
  - Eğitim, test ve doğruluk oranları
  - Test verisi için:
    - Accuracy
    - Precision
    - Recall
    - F1 Skoru
    - Karmaşıklık Matrisi
    - Classification Report

### Transfer Learning

- Transfer Learning algoritmaları kullanılarak sınıflandırma yapılmıştır.
- Eğitim, test ve doğruluk oranları aşağıda verilmiştir:
  - Test verisi için:
    - Accuracy
    - Precision
    - Recall
    - F1 Skoru
    - Karmaşıklık Matrisi
    - Classification Report

### Yapay Sinir Ağı Tasarımı

- Kendi özel Yapay Sinir Ağı tasarlanmış ve eğitilmiştir.
- Test verisi için:
  - Accuracy
  - Precision
  - Recall
  - F1 Skoru
  - Karmaşıklık Matrisi
  - Classification Report

### Kullanılan Teknolojiler

- Python
- TensorFlow
- Keras

---

## Kurulum

### 1. Projeyi Klonlayın

```bash
git clone https://github.com/mberkiskal/Pneumonia(CNN-ANN-Transfer_Learning).git
cd Pneumonia(CNN-ANN-Transfer_Learning)
```


### 2. Sanal Ortamı Oluşturun

```bash
python -m venv venv
source venv/bin/activate   # Windows'ta: venv\Scripts\activate
```

### 3. Gerekli Bağımlılıkları Yükleyin

```bash
pip install -r requirements.txt
```

### 4. Veri Setini İndirin

```bash
wget https://drive.google.com/file/d/1QlnV6PUZ3ic8M1_22cC5bAjJocYZKn1P/view
unzip Pneumonia.zip
```

### 5. CNN - Transfer Learning Modelini Eğitin

```bash
cd CNN__Transfer_Learning__Test_0_20.ipynb
python train.py
```

### 6. Yapay Sinir Ağı Modelini Eğitin

```bash
cd Artificial_Neural_Network_0_35.ipynb
python train.py
```

### 7. Modelleri Değerlendirin

```bash
cd evaluation
python evaluate.py
```

### 8. Projeyi Sonlandırın

Sanal ortamı sonlandırmak için:

```bash
deactivate   # Sanal ortamı kullandıysanız
```

## Kullanım

Kurulum başlığı altındaki adımlar takip edilir. Ayrıca aşağıdaki adımlar kontrol edilir.

- **Konfigürasyon Dosyaları:** Projenin çeşitli özelliklerini yapılandırmak için config veya benzeri bir klasör içerisindeki dosyaları inceleyin.
- **Veri Seti Düzeni:** Proje, özel bir veri seti üzerinde çalışıyorsa, veri seti düzenini ve dosya yollarını projenizin ihtiyaçlarına göre özelleştirin.
- **Model Hyperparameters:** CNN veya Transfer Learning modellerinin hyperparameter'larını değiştirmek için `train.py` dosyalarındaki ilgili bölümleri inceleyin.

## Katkılar

- [https://github.com/balfatih](https://github.com/balfatih)
- [https://www.tensorflow.org/tutorials/images/transfer_learning?hl=tr](https://www.tensorflow.org/tutorials/images/transfer_learning?hl=tr)
- [https://medium.com/@batincangurbuz/konvol%C3%BCsyonel-sinir-a%C4%9Flar%C4%B1-evri%C5%9Fimli-sinir-a%C4%9Flar%C4%B1-olarak-da-bilinir-convolutional-neural-4ecd2c5ad842](https://medium.com/@batincangurbuz/konvol%C3%BCsyonel-sinir-a%C4%9Flar%C4%B1-evri%C5%9Fimli-sinir-a%C4%9Flar%C4%B1-olarak-da-bilinir-convolutional-neural-4ecd2c5ad842)
- [https://medium.com/@draj0718/convolutional-neural-networks-cnn-architectures-explained-716fb197b243](https://medium.com/@draj0718/convolutional-neural-networks-cnn-architectures-explained-716fb197b243)
- [https://www.tensorflow.org/tutorials/images/cnn?hl=tr](https://www.tensorflow.org/tutorials/images/cnn?hl=tr)
- [https://www.geeksforgeeks.org/introduction-to-ann-set-4-network-architectures/](https://www.geeksforgeeks.org/introduction-to-ann-set-4-network-architectures/)

## İletişim

- m.berkiskal@gmail.com
- yesimdmr000@gmail.com 
- muhsinoztufek@gmail.com 
```

