# CIFAR-10 Görüntü Sınıflandırma Projesi

## Proje Amacı

Bu proje, CIFAR-10 veri setini kullanarak görüntü sınıflandırma işlemi gerçekleştirmeyi amaçlamaktadır. Projede, görüntü verileri üzerinde kapsamlı bir analiz yapılmış, uygun makine öğrenimi modelleri seçilmiş ve bu modeller kullanılarak veri setindeki görseller doğru bir şekilde sınıflandırılmıştır.

## Kullanılan Veri Setleri

**CIFAR-10 Veri Seti:**
CIFAR-10 veri seti, 10 farklı sınıfa ait toplamda 60,000 renkli görüntü içermektedir. Sınıflar arasında uçak, araba, kuş, kedi, geyik, köpek, kurbağa, at, gemi ve kamyon bulunmaktadır. Görüntüler 32x32 piksel boyutlarında ve RGB formatında kaydedilmiştir.

## Proje ve Araştırma Basamakları

1. **Veri Setinin Seçilmesi:** CIFAR-10 veri seti seçilmiş ve kullanılmıştır.
   
2. **Veri Seti Üzerinde Ön İşleme Yapılması:** Verilerin temizlenmesi, normalizasyon ve diğer ön işleme adımları gerçekleştirilmiştir.

3. **Kullanılan Modeller:**

   - **CNN (Evrişimli Sinir Ağı) Modeli:** Görüntü verilerinden özellik çıkarmak için evrişim ve havuzlama katmanları kullanarak eğitilmiştir.
   
   - **Random Forest Modeli:** CIFAR-10 veri setindeki özellikleri ve sınıfları öğrenmek için bir ensemble yöntemi olarak kullanılmıştır.

4. **Model Eğitimi ve Performans Değerlendirmesi:**

   - **CNN Modeli Performansı:**
     - Doğruluk Oranı: %64.54
     - F1 Skoru: 0.6416
     - ROC AUC Skoru: 0.944
     
   - **Random Forest Modeli Performansı:**
     - Doğruluk Oranı: %46.54
     - F1 Skoru: 0.4621
     - ROC AUC Skoru: 0.853

## Temel Bulgular

Proje kapsamında yapılan çalışmalar sonucunda elde edilen performans metrikleri göstermiştir ki, CNN modeli Random Forest modeline kıyasla daha yüksek doğruluk oranı ve daha iyi F1 skoru sağlamıştır. Bu sonuçlar, evrişimli sinir ağlarının (CNN) görüntü sınıflandırma problemlerinde etkili bir şekilde kullanılabilirliğini ve performansını vurgulamaktadır.

## İletişim

Daha fazla bilgi veya projeyle ilgili sorularınız için benimle iletişime geçebilirsiniz:

[Emirhan Tozlu](https://www.linkedin.com/in/emirhan-tozlu-576093253/)
