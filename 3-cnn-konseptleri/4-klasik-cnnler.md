# 👵 Klasik Evrişimli Sinir Ağları

| Ağ | İlk Kullanım |
| :--- | :--- |
| LeNet-5 | Elle yazılmış basamak sınıflandırması |
| AlexNet | ImageNet Dataset |
| VGG-16 | ImageNet Dataset |

## 🔢 LeNet-5

LeNet-5 çok basit bir ağdır - Modern standartlara göre -. Sadece 7 katmanı vardır

* bunların arasında 3 konvolüsyon katmanı vardır _\(C1, C3 and C5\)_
* 2 sub-sampling \(sıkıştırma\) katmanları _\(S2 and S4\)_
* 1 tam bağlanmış katman _\(F6\)_
* Çıkış katmanı

### 👀 Ağın Görselleştirilmesi

![](../.gitbook/assets/LeNet5Arch.png)

### 🙌 Ağın Özeti

![](../.gitbook/assets/LeNetSummay.jpg)

## 🛸 AlexNet

* LeNet-5' çok benziyor
* Katman başına daha fazla filtresi vardır
* _tanh_ yerine _ReLU_ kullanıyor
* Momentumlu Gradyan İnişi
* Düzenlileştirme yerine sönümleme _\(dropout\)_ kullanıyor

### 👀 Ağın Görselleştirilmesi

![](../.gitbook/assets/alexnetarch.png)

### 🔎 Daha Ayrınıtılı

![](../.gitbook/assets/AlexNet.gif)

### 🙌 Ağın Özeti

![](../.gitbook/assets/AlexNetSummary.jpg)

## 🌱 VGG-16

### 👀 Ağın Görselleştirilmesi

![](../.gitbook/assets/VGGArch.jpg)

### 🙌 Ağın Özeti

![](../.gitbook/assets/vgg16summary.jpg)

### 🔎 Daha Ayrıntılı

![](../.gitbook/assets/VGG.gif)

### 😐 Olumsuz Yanları

* Eğitilmesi aşırı yavaş \(138 milyon parametresi var 🙄\)

## 👩‍🔧 İmplementasyon

* [AlexNet'in İmplementasyon](https://github.com/pytorch/vision/blob/master/torchvision/models/alexnet.py%20%20%20)

## 🌞 Yazının Aslı

* [Burada 🐾](https://dl.asmaamir.com/3-cnnconcepts/4-classiccnns)

## 🧐 Daha Fazla Oku

* [Detailed LeNet-5](https://engmrk.com/lenet-5-a-classic-cnn-architecture/)
* [Detailed AlexNet](https://engmrk.com/alexnet-implementation-using-keras/)
* [Detailed VGG-16](https://engmrk.com/vgg16-implementation-using-keras/)
* [Summary of classic networks](https://medium.com/analytics-vidhya/cnns-architectures-lenet-alexnet-vgg-googlenet-resnet-and-more-666091488df5)

