# 🏡 California Housing Price Prediction  

Bu proje, **Kaggle California Housing** veri setini kullanarak ev fiyatlarını tahmin etmeyi amaçlamaktadır. Apache Spark ve PySpark ML kütüphaneleri ile veri analizi ve makine öğrenimi modeli oluşturulmuştur.  

## 📂 Kullanılan Teknolojiler  
- **Apache Spark (PySpark)**
- **Pandas**
- **Matplotlib & Seaborn**  

## 🔍 Modelleme Süreci  
- **Veri Temizleme & Özellik Mühendisliği**  
- **Linear Regression & GBTRegressor ile Model Eğitimi**  
- **Model Değerlendirme (RMSE, R²)**  

### 📊 Model Sonuçları  
| Model                 | Eğitim RMSE | Test RMSE | Eğitim R² | Test R² |
|-----------------------|-------------|-----------|-----------|---------|
| **Linear Regression** | 69538.44    | 69685.93  | 0.6378    | 0.6323  |
| **GBTRegressor**      | 54504.84    | 58985.82  | 0.7775    | 0.7365  |

1️⃣ Gerekli kütüphaneleri yükleyin:  
```bash
pip install pyspark pandas matplotlib seaborn

2️⃣ Jupyter Notebook'u açın ve main.ipynb dosyasını çalıştırın.
