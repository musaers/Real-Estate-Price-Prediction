# Real-Estate-Price-Prediction
Predicting and visualization of  house prices based on certain parameters

# Emlak Fiyat Tahmini Projesi

Bu proje, çoklu doğrusal regresyon (multiple linear regression) kullanarak emlak fiyatlarını tahmin eden ve sonuçları kapsamlı görselleştirmelerle sunan bir uygulamadır.

## Proje Özeti

Emlak fiyatlarını etkileyen faktörleri analiz ederek, potansiyel bir evin fiyatını tahmin etmeye yönelik bir makine öğrenimi modeli geliştirilmiştir. Proje, veri analizi, model eğitimi ve interaktif görselleştirmeler dahil olmak üzere kapsamlı bir çözüm sunmaktadır.

## Özellikler

- **Otomatik Veri Ön İşleme**:
  - Kategorik değişkenlerin otomatik tespiti ve dönüştürülmesi
  - Yes/No değerlerinin sayısallaştırılması
  - Eksik değerlerin kontrolü ve işlenmesi

- **Çoklu Doğrusal Regresyon Modeli**:
  - Emlak özellikleri ile fiyat arasındaki ilişkinin modellenmesi
  - Önemli özelliklerin belirlenmesi ve model performansının ölçülmesi

- **Kapsamlı Görselleştirmeler**:
  - Korelasyon matrislerinin ısı haritaları
  - Gerçek vs. tahmin edilen değerlerin karşılaştırması
  - 3B görselleştirmeler
  - Artık değerlerin analizi
  - Özellik önem derecelerinin görselleştirilmesi

- **İnteraktif Web Arayüzü**:
  - Flask tabanlı kullanıcı arayüzü
  - Yeni evler için anlık fiyat tahmini
  - Kullanıcı dostu form girişi

## Teknolojiler

- Python 3.x
- Pandas, NumPy (veri manipülasyonu)
- Scikit-learn (makine öğrenimi)
- Matplotlib, Seaborn (temel görselleştirme)
- Plotly (interaktif görselleştirme)
- Flask (web arayüzü)
- Bootstrap (UI tasarımı)

## Kurulum

### Gereksinimler

```bash
# Gereksinimleri yükle
pip install pandas numpy scikit-learn matplotlib seaborn plotly flask
```

### Projeyi Çalıştırma

1. Veri setini analiz etmek ve modeli eğitmek için:

```bash
python multilinear_regression.py
```





## Model Performansı

- R² skoru: 0.9257456555111836


 Fiyata En Çok Etki Eden Faktörler:
- Floor_Area: 108.4% etki (180.0 × 187628.0797)
- Land_Area: 20.2% etki (450.0 × 14014.0726)
- Num_rooms: 0.6% etki (4.0 × 48283.0410)
- Num_bathrooms: -0.4% etki (2.0 × -56770.5051)
- Crimerate in area: -28.9% etki (3.5 × -2575759.3158)

## Geliştirme İmkanları

- Derin öğrenme modelleri kullanarak tahmin performansını artırma
- Coğrafi bilgi sistemleri (GIS) entegrasyonu ile konum bazlı analiz
- Zaman serisi analizi ile fiyat trendlerini tahminleme
- Mobil uygulama geliştirme
- Model açıklanabilirliğini (explainability) geliştirme


