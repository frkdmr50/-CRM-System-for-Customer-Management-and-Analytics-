# -CRM-System-for-Customer-Management-and-Analytics-


🔎 Analiz Adımları
1. Veri Ön İşleme
Eksik ve hatalı verilerin temizlenmesi
Tarih formatlarının düzenlenmesi
İptal edilen siparişlerin ayıklanması
2. RFM Analizi
Recency (Güncellik): Müşterinin en son alışveriş yaptığı tarih
Frequency (Sıklık): Alışveriş sayısı
Monetary (Harcama): Toplam harcama miktarı
Her müşteri için RFM skorları hesaplanmıştır.
3. Müşteri Segmentasyonu (Clustering)
RFM skorları StandardScaler ile ölçeklendirildi.
K-Means Clustering yöntemi kullanıldı.
Belirlenen segmentler:
🟢 Sadık Müşteriler
🔵 Potansiyel Müşteriler
🟡 Risk Altındaki Müşteriler
🔴 Kaybedilmiş Müşteriler
4. Satın Alma Eğilimi Tahmini
Makine Öğrenmesi Modelleri:
Lojistik Regresyon
Karar Ağaçları
Değerlendirme Metrikleri:
Accuracy
F1-Score
Classification Report
📈 Sonuçlar
RFM analizi ile müşteriler segmentlere ayrılmıştır.
Kümeleme sonuçları görselleştirilerek hangi müşteri grubunun daha değerli olduğu belirlenmiştir.
Satın alma tahmin modelleri arasında en yüksek başarıyı Decision Tree göstermiştir.
