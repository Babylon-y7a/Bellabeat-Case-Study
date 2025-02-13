# 📊 Bellabeat Case Study - Data Analysis in R  

This project analyzes Bellabeat's fitness tracker data using R.  
It includes data cleaning, exploratory data analysis, and insights for business decisions.  

## 📌 Key Findings  
- **Steps and Calories:** Positive correlation between total steps and calories burned.  
- **Sleep and Activity:** Weak negative correlation between sleep duration and activity levels.  
- **Hourly Activity:** Peak activity is observed between **10:00-12:00 AM and 5:00-8:00 PM**.  
- **Morning vs Evening Calories:** No major difference between calorie burn in the morning and evening.  

## 📂 Files in the Repository  
- `FitBit_Fitness_Tracker_Data.ipynb` - Jupyter Notebook with all analysis  
- `README.md` - Project description  

## 🚀 Tools Used  
- **Programming Language:** R (ggplot2, dplyr, tidyr)  
- **Data Source:** Kaggle (Fitbit Fitness Tracker Data)  

Proje Özeti
Bu case study, Bellabeat şirketinin akıllı sağlık takip cihazlarıyla ilgili verileri analiz ederek kullanıcıların aktivite ve sağlık alışkanlıklarını anlamaya odaklanmaktadır.

📊 Ana Sorular:
✔ Kullanıcıların günlük aktivite seviyeleri nasıldır?
✔ Uyku süresi ile fiziksel aktivite arasında nasıl bir ilişki vardır?
✔ Kalp atış hızı zaman içinde nasıl değişir?
✔ Saatlik hareketlilik nasıl değişir?
✔ Kilo değişimi ile aktivite arasında ilişki var mı?
✔ Sabah ve akşam saatlerinde kalori yakımı nasıl değişiyor?

📂 Veri Seti & Kaynaklar
Bu analizde kullanılan veri, FitBit Fitness Tracker Data (Kaggle) veri setinden alınmıştır.

📍 Veri setindeki ana dosyalar:
✔ dailyActivity_merged.csv – Günlük aktivite verileri (Adım, Kalori, Hareket Süresi)
✔ sleepDay_merged.csv – Uyku verileri
✔ heartrate_seconds_merged.csv – Kalp atış verileri
✔ hourlySteps_merged.csv – Saatlik adım verileri
✔ weightLogInfo_merged.csv – Kullanıcıların kilo takibi

🔎 Analiz Süreci
1️⃣ ASK (Sorunu Belirleme)
Bellabeat ekibi, kullanıcı verilerinden faydalanarak pazarlama stratejilerini geliştirmek istiyor.
Bu yüzden analizimiz şu sorulara odaklandı:
📌 Kullanıcıların aktivite seviyeleri nasıl?
📌 Uyku süresi, hareketlilik ve kalori yakımıyla nasıl ilişkili?
📌 Kullanıcılar günün hangi saatlerinde daha aktif?

2️⃣ PREPARE (Veri Hazırlama)
✔ Eksik ve anormal veriler kontrol edildi.
✔ Tarih formatları düzenlendi.
✔ Kullanılmayan sütunlar çıkarıldı.

3️⃣ PROCESS (Veri Temizleme & İşleme)
✔ Tüm veri setleri birleştirildi ve analiz için uygun hale getirildi.
✔ ID'lerin eşleşip eşleşmediği kontrol edildi.
✔ Saat ve tarih sütunları ayrılarak detaylı inceleme yapıldı.

4️⃣ ANALYZE (Veri Analizi & Görselleştirme)
📊 Adım Sayısı vs Kalori Yakımı
✔ Günlük adım sayısı ile yakılan kalori arasında orta düzeyde pozitif korelasyon (0.59) bulundu.
✔ Daha fazla hareket eden kullanıcılar, daha fazla kalori yakıyor.

📊 Uyku Süresi & Günlük Aktivite
✔ Uyku süresi ile günlük adım sayısı arasında zayıf negatif korelasyon (-0.18) bulundu.
✔ Uyku süresi arttıkça aktivite azalıyor, ancak bu ilişki güçlü değil.

📊 Saatlik Hareketlilik
✔ Kullanıcıların en aktif olduğu saatler: 10:00 - 12:00 ve 17:00 - 20:00
✔ Gece saatlerinde hareketlilik neredeyse sıfır.

📊 Sabah & Akşam Kalori Yakımı
✔ Sabah ve akşam saatlerinde yakılan kalori miktarları neredeyse aynı.
✔ Detaylı analizde, akşam saatlerinde biraz daha fazla kalori yakıldığı görüldü.

📊 Kilo & Adım Sayısı İlişkisi
✔ Kilo ile toplam adım sayısı arasında belirgin bir ilişki bulunamadı.
✔ Kişisel farklılıklar bu ilişkiyi etkiliyor olabilir.

📢 Öneriler & İş Stratejileri
🔹 Kullanıcıların aktivite seviyelerine göre hedef belirlemesi teşvik edilebilir.
🔹 Sabah ve akşam saatlerinde farklı egzersiz önerileri sunulabilir.
🔹 Kullanıcılara kişiselleştirilmiş uyku ve hareket önerileri sunulabilir.
🔹 Bellabeat’in reklam ve bildirim stratejileri, kullanıcıların aktif olduğu saatlere göre optimize edilebilir.

💻 Kod ve Analizler
📍 Analizlerin tüm detaylarına Jupyter Notebook / R Markdown dosyamdan ulaşabilirsiniz.
📂 FitBit_Fitness_Tracker_Data.ipynb

📌 Sonuç
Bu analiz, Bellabeat’in müşteri kitlesinin davranışlarını anlamasına ve daha iyi pazarlama stratejileri geliştirmesine yardımcı olabilir.

📢 Bu çalışmayı genişletmek isterseniz, veri setini farklı açılardan analiz edebiliriz. 🚀

