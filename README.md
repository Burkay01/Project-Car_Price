EN
Car Price Prediction Project
This project aims to predict the selling price of used cars based on various features such as age, mileage, fuel type, and transmission. A Linear Regression model was developed using a dataset of 4,340 vehicles (CARS.csv).

Project Objective
The goal is to analyze the key factors influencing used car market values and build a machine learning model that provides accurate price estimations.

Dataset Overview
The dataset contains the following features used for analysis and modeling:

name: Make and model of the car.

year: Manufacturing year.

selling_price: Selling price (Target Variable).

km_driven: Total distance driven in kilometers.

fuel: Fuel type (Diesel, Petrol, CNG, LPG, Electric).

seller_type: Type of seller (Individual, Dealer, Trustmark Dealer).

transmission: Gearbox type (Manual, Automatic).

owner: Number of previous owners.

Tech Stack
Data Analysis: pandas, numpy

Visualization: seaborn, matplotlib

Machine Learning: sklearn (Scikit-learn)

Workflow
Exploratory Data Analysis (EDA): Performed statistical analysis and visualized correlations using heatmaps.

Data Visualization: Analyzed price trends over years and price distributions across different categories (fuel, transmission, etc.).

Data Preprocessing: Handled categorical variables using encoding techniques to make them compatible with the model.

Modeling: Split the data into 80% Training and 20% Test sets. Trained a Linear Regression algorithm.

Evaluation: Validated the model performance using standard regression metrics.

Key Insights
There is a strong negative correlation between car age and selling price (Price drops as age increases).

Diesel cars tend to have a higher average selling price compared to petrol cars.

Automatic transmission vehicles command a significant price premium over manual ones.

----------------------------------------------------------------------------------------------------------------------------------

TR

Projenin Amacı
Araçların yaşı, kilometresi, yakıt türü ve vites tipi gibi değişkenlerin satış fiyatı (selling_price) üzerindeki etkisini analiz etmek ve Linear Regression algoritması ile fiyat tahmini yapan bir model oluşturmaktır.

Veri Seti Özellikleri
Veri setinde yer alan ve modelde kullanılan temel özellikler:

name: Aracın marka ve modeli.

year: Aracın üretim yılı.

selling_price: Satış fiyatı (Hedef Değişken).

km_driven: Aracın toplam kilometresi.

fuel: Yakıt türü (Diesel, Petrol, CNG, LPG, Electric).

seller_type: Satıcı tipi (Individual, Dealer, Trustmark Dealer).

transmission: Vites tipi (Manual, Automatic).

owner: Aracın kaçıncı sahibi olduğu.

Kullanılan Kütüphaneler
Veri Analizi: pandas, numpy

Görselleştirme: seaborn, matplotlib

Makine Öğrenmesi: sklearn (Scikit-learn)

Proje Adımları
Exploratory Data Analysis (EDA): Veri setinin genel yapısı incelendi, korelasyon matrisi (heatmap) ile değişkenler arası ilişkiler görselleştirildi.

Veri Görselleştirme: * Yıllara göre fiyat değişimi.

Yakıt türü ve vites tipinin fiyat üzerindeki etkisi (Box plot ve Scatter plot).

Veri Ön İşleme: Kategorik değişkenler (yakıt, vites, satıcı tipi vb.) modelin işleyebilmesi için sayısal değerlere dönüştürüldü.

Modelleme: Veri seti %80 Eğitim ve %20 Test olarak ayrıldı. Linear Regression modeli kullanılarak eğitim gerçekleştirildi.

Değerlendirme: Modelin tahmin başarısı test verileri üzerinde ölçüldü.

Öne Çıkan Bulgular
Araç yaşı ve satış fiyatı arasında güçlü bir negatif korelasyon vardır (Araç eskidikçe fiyat düşer).

Dizel araçların satış fiyatları ortalamada benzinli araçlara göre daha yüksektir.

Otomatik vitesli araçlar, manuel viteslilere göre belirgin bir fiyat üstünlüğüne sahiptir.
