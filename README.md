# ecommerce-rfm-segmentation
# E-Ticaret Müşteri Segmentasyonu (K-Means ve RFM)

Bu projede, e-ticaret verileri üzerinden Python, Pandas ve Makine Öğrenmesi (K-Means) kullanılarak profesyonel müşteri segmentasyonu (RFM analizi) gerçekleştirilmiştir.

## Proje Adımları
- **Veri Ön İşleme:** Eksik değerlerin, iptal edilen işlemlerin ve anormalliklerin temizlenmesi.
- **RFM Metrikleri:** Recency (Yenilik), Frequency (Sıklık) ve Monetary (Parasal Değer) hesaplamaları.
- **İstatistiksel Dönüşüm:** Sağa çarpık dağılımları normalleştirmek için `np.log1p` logaritmik dönüşüm ve `StandardScaler` ile ölçeklendirme.
- **K-Means Kümeleme:** Unsupervised (Denetimsiz) öğrenme ile müşterilerin optimum kümelere ayrılması.
- **Görselleştirme:** Seaborn ile küme dağılım grafiklerinin çizdirilmesi.

## Kullanılan Kütüphaneler
- Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
