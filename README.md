# 🚦 Traffic Sign Recognition with CNN

Bu proje, Convolutional Neural Network (CNN) kullanarak **trafik işaretlerini sınıflandırmayı** amaçlamaktadır.  
Model, **GTSRB (German Traffic Sign Recognition Benchmark)** veriseti üzerinde eğitilmiş ve test edilmiştir.  

---

## 📌 Proje Özeti
- CNN tabanlı derin öğrenme modeli ile trafik işaretleri tanındı.
- Eğitim verisi: 34,799 görüntü  
- Doğrulama verisi: 4,410 görüntü  
- Test verisi: 12,630 görüntü  
- Model doğruluğu: **%95+**  

---

## ⚙️ Kullanılan Teknolojiler
- **Python**
- **TensorFlow / Keras**
- **NumPy, Pandas**
- **Matplotlib, Seaborn**
- **Scikit-learn**

---

## 📊 Sonuçlar
- Eğitim doğruluğu: ~%98  
- Test doğruluğu: ~%95  
- Confusion Matrix ve Classification Report ile detaylı analiz yapıldı.  

📈 Eğitim ve doğrulama grafikleri modelin dengeli çalıştığını göstermektedir.  

---

## 📂 Dosya Yapısı
- `traffic_sign_model.h5` → Kaydedilmiş model  
- `notebook.ipynb` → Kaggle üzerinde çalıştırılan notebook  
- `README.md` → Proje açıklaması  

---

## ▶️ Nasıl Çalıştırılır?
1. Gerekli kütüphaneleri yükle:
   ```bash
   pip install tensorflow numpy pandas matplotlib seaborn scikit-learn
   ```
2. Notebook’u çalıştır veya kaydedilmiş modeli yükle:
   ```python
   from tensorflow.keras.models import load_model
   model = load_model("traffic_sign_model.h5")
   ```
3. Test verisiyle doğruluğu kontrol et.  

---

## 👩‍💻 Yazar
**Arzu Çakır**  

---
