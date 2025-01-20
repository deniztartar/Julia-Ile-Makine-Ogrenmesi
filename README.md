# Julia-Ile-Makine-Ogrenmesi
Sağlık alanında veri bilimi ve makine öğrenmesi alanındaki çalışmalarımı içeren bir Julia projesi.Bu proje, Julia dilinde yazılmış kodlar içeren bir HTML dosyasını barındırır.
Bu çalışma, kalp hastalığını etkileyen faktörlerin analiz edilmesi ve bireylerin kalp hastalığı riskini tahmin eden modellerin geliştirilmesini amaçlamaktadır. Araştırmada kullanılan Heart Disease veri seti, yaş, cinsiyet, kolesterol seviyesi, dinlenme kan basıncı ve maksimum kalp atış hızı gibi 14 farklı tıbbi ve demografik özelliği içermektedir. Çalışma kapsamında doğrusal regresyon, lojistik regresyon, karar ağaçları, rastgele orman, k-en yakın komşuluk ve kümeleme algoritmaları uygulanmış; modellerin performansı doğruluk, kesinlik, hatırlama ve F1 skoru gibi ölçütlerle karşılaştırılmıştır. Analiz sonucunda, kalp hastalığını etkileyen kritik faktörleri belirlemekte ve risk tahmini için etkili modeller sunmaktadır.
Veri seti, istatistiksel modelleme ve makine öğrenmesi yöntemlerinin uygulanması için sıkça kullanılan bir kaynaktır. Kalp hastalığının erken teşhisine yönelik çalışmalarda kullanılır. Bu çalışmamızda kalp hastalığını tahmin etmek için hangi faktörlerin önemli olduğunun belirlemeye ve bu tahminlerin hangi makine öğrenmesi algoritmaları ile daha yüksek doğrulukta tahminler yapılabileceğini incelemeye odaklıdır.
Veri Seti Kaynağı: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset/data
1. VERİ SETİ DEĞİŞKENLERİ
Yaş
Cinsiyet: 1;Erkek 0;Kadın
Göğüs ağrısı tipi (4 değer
Dinlenme kan basıncı: mm Hg cinsinden
Serum kolesterol (mg/dl): miligram/desilitre cinsinden
Açlık kan şekeri > 120 mg/dl: Açlık kan şekeri seviyesi 120 mg/dl'nin üzerinde mi? (1: Evet, 0: Hayır).
Dinlenme elektrokardiyografik sonuçları (değerler 0,1,2): Dinlenme sırasında alınan EKG sonuçları:
• 0: Normal
• 1: ST-T dalga anormallikleri (örn. T dalgası inversiyonu veya ST yükselmesi/depresyonu)
• 2: Sol ventriküler hipertrofi (Minnesota kodu kriterlerine göre).
Maksimum kalp atış hızı: Egzersiz sırasında ulaşılan maksimum kalp atış hızı.
Egzersizle indüklenen anjina: Egzersiz sırasında göğüs ağrısı veya rahatsızlık oluşup oluşmadığı (1: Evet, 0: Hayır).
Oldpeak: Egzersizle tetiklenen ST depresyonu (dinlenme durumuna göre).
Egzersiz sırasında ST segmentinin eğimi: Egzersiz sırasında ST segmentinin eğimini gösterir:
• 0: Düz
• 1: Yukarı eğimli
• 2: Aşağı eğimli.
Floroskopi ile renklendirilmiş büyük damar sayısı (0-3): Floroskopi sonucunda renklendirilmiş büyük damarların sayısı (0'dan 3'e kadar).
Thal (Talasemi durumu):
• 0: Normal
• 1: Sabit defekt
• 2: Reversibl defekt (geri dönüşümlü defekt).
2. MODELLERİN TANIMLANMASI
2.1 Veri tanımlaması ve Tanımlayıcı İstatistiklerinin İncelenmesi
2.2 Doğrusal Regresyon
2.3 Çoklu Doğrusal Regresyon
2.4 Lojistik Regresyon – Sınıflandırma
2.5 Karar Ağaçları & Rastgele Orman Algoritması
2.6 k-En Yakın Komşu Algoritması
2.7 Kümeleme Algoritması
2.8 k-Medoids Kümeleme
