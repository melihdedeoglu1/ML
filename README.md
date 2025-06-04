# FakeandRealNews-ML

Makine öğrenmesi ile gerçek ve sahte haberleri sınıflandırma denemesi. Temel veri analizi, model eğitimi ve değerlendirme adımlarını içerir.


# Gerçek ve Sahte Haber Sınıflandırması (Makine Öğrenmesi Denemesi)

Bu repoda, [bu Kaggle veri seti](https://www.kaggle.com/datasets/razanaqvi14/real-and-fake-news) kullanılarak gerçek ve sahte haberleri sınıflandırmak amacıyla yapılan temel bir makine öğrenmesi çalışması yer almaktadır. Proje; veri analizi, özellik mühendisliği (feature engineering), model eğitimi ve model başarımının değerlendirilmesi gibi temel ML adımlarını öğrenmek amacıyla hazırlanmıştır.

## 🔍 Kullanılan Veri Seti

- Kaggle: [Real and Fake News Dataset](https://www.kaggle.com/datasets/razanaqvi14/real-and-fake-news)
- İçerik: Gerçek ve sahte olarak etiketlenmiş haber başlıkları ve içerikleri

## 🛠️ Uygulanan Adımlar

1. **Veri Yükleme:**  
   Veri seti Kaggle'dan indirilip, Jupyter Notebook ortamında yüklendi.

2. **Özellik Mühendisliği (Feature Engineering):**  
   - Metin temizleme ve önişleme  
   - Gerekli sütunların seçilmesi ve/veya dönüştürülmesi  
   - Metin verisinin sayısal verilere dönüştürülmesi (vektörleştirme)

3. **Model Hazırlığı:**  
   - Verinin eğitim ve test olarak ayrılması  
   - İlk olarak KNN (K-En Yakın Komşu) modeliyle temel bir deneme  
   - Ardından Random Forest modeli ile daha gelişmiş bir yaklaşım

4. **Feature Importance (Özellik Önem Dereceleri):**  
   - KNN ile elde edilen önemli özelliklerin görselleştirilmesi ve yorumlanması
   - Random Forest ile elde edilen önemli özelliklerin görselleştirilmesi ve yorumlanması 

5. **Hiperparametre Optimizasyonu:**  
   - KNN modeli için GridSearchCV kullanıldı  
   - Random Forest modeli için RandomizedSearchCV kullanıldı  

6. **Model Eğitimi ve Değerlendirme:**  
   - Modellerin doğruluk (accuracy) ve diğer metriklerle karşılaştırılması  
   - Sonuçların özetlenmesi
  
   

## 📈 Elde Edilen Sonuçlar
 
> - KNN doğruluk: 0.9375278396436526 
> - Random Forest doğruluk: 0.9199331848552339  

## 📝 Notlar

- Bu proje tamamen öğrenme ve deneme amaçlıdır.
- Veri seti açık kaynaklıdır ve kamuya açıktır.
- Farklı model ve özellik mühendisliği denemeleri yapılabilir.

## 🙏 Teşekkürler

- [Kaggle - Real and Fake News Dataset](https://www.kaggle.com/datasets/razanaqvi14/real-and-fake-news)
- Makine öğrenmesi topluluğu ve açık kaynak geliştiricilerine teşekkürler!

---

