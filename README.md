#  Naive Bayes ile Iris Çiçeği Sınıflandırması

Bu proje, klasik **Iris veri seti** üzerinde **Gaussian Naive Bayes sınıflandırıcısı** kullanılarak çiçek türlerini (*Setosa*, *Versicolor* ve *Virginica*) tahmin etmeyi amaçlamaktadır.  
Amaç, olasılıksal modellerin küçük ve düzenli veri setlerinde ne kadar etkili çalışabildiğini göstermektir.

---

## Kullanılan Teknolojiler
- Python 🐍  
- scikit-learn  
- NumPy  
- Matplotlib  
- Seaborn  

---

##  Proje Adımları

1. **Veri Yükleme ve İnceleme**  
   - `load_iris()` fonksiyonu ile veri seti yüklendi.  
   - Temel istatistiksel bilgiler incelendi (özellikler, hedef değişken).  

2. **Veri Bölme**  
   - Veriler %75 eğitim, %25 test olarak `train_test_split()` ile ayrıldı.  

3. **Model Eğitimi**  
   - `GaussianNB()` sınıfı ile model oluşturuldu.  
   - Model `fit()` metodu ile eğitildi.  

4. **Tahmin ve Değerlendirme**  
   - Test verileri üzerinde tahminler yapıldı (`predict()`).  
   - Aşağıdaki metriklerle performans ölçüldü:  
     - Accuracy (Doğruluk)  
     - Precision (Kesinlik)  
     - Recall (Duyarlılık)  
     - F1-score  
 


