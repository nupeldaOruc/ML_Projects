# Veri Bilimi ve Makine Öğrenmesi Projeleri

Bu repository, veri bilimi ve makine öğrenmesi alanında geliştirilmiş çeşitli projeleri içermektedir. Her bir proje, farklı veri analizi ve makine öğrenmesi tekniklerini kullanarak gerçek dünya problemlerine çözümler sunmaktadır.

## 📚 Projeler

### 1. Mental Sağlık Analizi
**Dosya:** `mental-healts.ipynb`

Bu proje, mental sağlık verilerinin analizini ve görselleştirilmesini içermektedir. Proje kapsamında:
- Veri temizleme ve ön işleme
- İstatistiksel analizler
- Veri görselleştirme
- Korelasyon analizleri
- Trend analizleri

### 2. ABD'deki ML İşlerinin Kümeleme Analizi
**Dosya:** `Clustering_ML_Jobs_in_the_US_withTF_IDF_and_KMeans.ipynb`

Bu proje, ABD'deki makine öğrenmesi iş ilanlarının analizini ve kümeleme işlemlerini içermektedir. Kullanılan teknikler:
- TF-IDF (Term Frequency-Inverse Document Frequency)
- K-Means Kümeleme
- Metin madenciliği
- İş ilanlarının kategorize edilmesi
- Görselleştirme ve analiz

### 3. Uygulama Oturumu
**Dosya:** `Practice Session.ipynb`

# Pima Indians Diabetes Analizi

Bu proje, Pima Indians Diabetes veri seti üzerinde temel veri analizi, görselleştirme ve korelasyon incelemeleri içermektedir.

## 🔍 Amaç

- Veriyi tanımak
- Eksik ve anlamlı olmayan sütunları tespit etmek
- Görsel analizlerle dağılımları ve ilişkileri incelemek

## 📁 Kullanılan Kütüphaneler

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

## 📊 Uygulanan Adımlar

1. **Veri Yükleme:** `pima-indians-diabetes-database.csv`
2. **Dağılım Grafikleri:** Her sütunun dağılımını incelemek için `plotPerColumnDistribution()`
3. **Korelasyon Matrisi:** Değişkenler arası ilişkiyi görmek için `plotCorrelationMatrix()`
4. **Scatter Matrix:** Sayısal değişkenler arası dağılım grafikleri

## 🛠️ Fonksiyonlar

- `plotPerColumnDistribution(df, n, perRow)`
- `plotCorrelationMatrix(df, width)`
- `plotScatterMatrix(df, size, textSize)`

## 📌 Notlar

- Eksik değerler otomatik olarak tespit edilip analiz dışında bırakılır.
- Sadece sayısal veriler görselleştirmeye dahil edilir.

## 📚 Veri Seti

Veri seti: [Kaggle - Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

---

Bu proje temel veri analizi ve görselleştirme uygulamaları içeren bir başlangıç çalışmasıdır.


Bu dosya, çeşitli veri bilimi ve makine öğrenmesi kavramlarının uygulamalı olarak gösterildiği bir çalışma oturumunu içermektedir.

## 🛠️ Kullanılan Teknolojiler

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- NLTK (Doğal Dil İşleme için)

## 📋 Gereksinimler

Projeleri çalıştırmak için aşağıdaki Python kütüphanelerinin yüklü olması gerekmektedir:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn nltk jupyter
```

## 🚀 Başlangıç

1. Repository'yi klonlayın:
```bash
git clone [repository-url]
```

2. Gerekli kütüphaneleri yükleyin
3. Jupyter Notebook'ları açın ve çalıştırın

## 📊 Proje Yapısı

```
.
├── mental-healts.ipynb
├── Clustering_ML_Jobs_in_the_US_withTF_IDF_and_KMeans.ipynb
└── Practice Session.ipynb
   Pima Indians Diabetes Analizi
```



