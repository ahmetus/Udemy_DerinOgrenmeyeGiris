📌[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ayyucekizrak/Udemy_DerinOgrenmeyeGiris/blob/master/Optimizasyon_Algoritmalarinin_Karsilastirilmasi/Optimizasyon_Yöntemlerinin_Karşılaştırması.ipynb) **Google Colab Not Defteri**

📌[![Open In Jupyter](https://github.com/jupyter/notebook/blob/master/docs/resources/icon_32x32.svg)](https://nbviewer.jupyter.org/github/ayyucekizrak/Udemy_DerinOgrenmeyeGiris/blob/master/Optimizasyon_Algoritmalarinin_Karsilastirilmasi/Optimizasyon_Yöntemlerinin_Karşılaştırması.ipynb) **Jupyter Not Defteri** 
---
# Aşırı Uydurma ve Erken Durdurma

Overfitting and Early Stopping

---
### Basit Bir Öğrenme Modelinde Aşırı Uydurma (Overfitting) Probleminin Çözümü: Erken Durdurma (Early Stopping)
---
Bunun için iki sınıflı rastgele değerlere sahip bir veri seti için basit bir çok katmanlı sinir ağı (Multi Layer Perceoptron) oluşturulmuştur. 
* Aktivasyon fonksiyonu olarak **ReLU** ve çıkış katmanında **Sigmoid** kullanılmıştır. Aktivasypn fonksiyonlarıyla ilgili daha kapsamlı bilgi için [**buraya**](https://github.com/ayyucekizrak/Udemy_DerinOgrenmeyeGiris/tree/master/Aktivasyon_Fonksiyonlarinin_Karsilastirilmasi) tıklayınız!
* Hatayı minimize etmek için **Adam** optimizasyon algoritması kullanılmıştır. Optimizasyon algoritmaları hakkında daha kapsamlı bilgi için [**buraya**](https://github.com/ayyucekizrak/Udemy_DerinOgrenmeyeGiris/tree/master/Optimizasyon_Algoritmalarinin_Karsilastirilmasi) tıklayınız!
* Tüm eğitim işlemi sonunda en iyi sonucun elde edildiği **epoch**'ta kaydedilen model ağırlıkları en iyi model ağırlıkları olarak **ModelCheckPoints** ile kaydedilmiştir.
Hadi birlikte işlemleri nasıl yapmamız gerektiğine adım adım bakalım.
---
<img align="left" src="https://github.com/ayyucekizrak/Udemy_DerinOgrenmeyeGiris/blob/master/Asiri_Uydurma_(Overfitting)_ve_Erken_Durdurma_(Early_Stopping)/dance-2.gif">

---

[Aynı çalışmanın MNIST veri seti örneğinde basit bir evrişimli sinir ağı modeli için hazırlanmış versiyonuna buradan ulaşabilirsiniz!](https://github.com/ayyucekizrak/Udemy_DerinOgrenmeyeGiris/blob/master/Asiri_Uydurma_(Overfitting)_ve_Erken_Durdurma_(Early_Stopping)/AsiriUydurma_Overfitting_v2.ipynb)