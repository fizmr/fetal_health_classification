# [👶 Fetal Health Classification (Cenin Sağlığı Sınıflandırması)](https://github.com/fizmr/fetal_health_classification/blob/main/fetal_heal_csv.ipynb)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-Model_Training-orange)
![Pandas](https://img.shields.io/badge/Data-Analysis-green)

[🇺🇸 English](#english) | [🇹🇷 Türkçe](#türkçe)

---

<a name="english"></a>
## 🇺🇸 Project Overview
This project aims to classify the health status of a fetus based on Cardiotocograms (CTGs) data using Machine Learning algorithms.

### 📊 Exploratory Data Analysis (EDA)
Before training the models, I analyzed the dataset to understand correlations and class distributions.

**1. Correlation Heatmap:**
*(Shows how features relate to each other and the target variable)*

![Heatmap](images/heatmap.png)

**2. Target Class Distribution:**
*(Shows the imbalance between Normal, Suspect, and Pathological classes)*

![Class Distribution](images/sutun.png)

### 🧠 Models & Performance
I trained three different models. Here are the results:

#### 1. Logistic Regression
* **Accuracy:** %88.50
* A strong baseline model for this dataset.
* ![Logistic Regressşon Graph](images/LR.png)

#### 2. K-Nearest Neighbors (KNN)
* **Accuracy:** %87.09
* Below is the performance visualization for KNN:
* ![KNN Graph](images/KNN.png)

#### 3. Decision Tree (Best Model 🏆)
* **Accuracy:** **%90.14**
* The Decision Tree performed the best by capturing non-linear relationships.
  ![Decision Tree Graph](images/DT.png)

---

<a name="türkçe"></a>
## 🇹🇷 Proje Özeti
Bu proje, Kardiyotokografi (CTG) verilerini kullanarak anne karnındaki bebeğin sağlık durumunu makine öğrenmesi algoritmalarıyla tahmin etmeyi amaçlar.

### 📊 Keşifçi Veri Analizi (EDA)
Modelleri eğitmeden önce veri setindeki ilişkileri ve dağılımları inceledim.

**1. Korelasyon Haritası (Heatmap):**
*(Özelliklerin birbirleriyle ve hedef değişkenle ilişkisini gösterir)*
![Heatmap](images/heatmap.png)

**2. Sınıf Dağılım Grafiği:**
*(Normal, Şüpheli ve Patolojik sınıflar arasındaki dengesizliği gösterir)*
![Class Distribution](images/sutun.png)

### 🧠 Modeller ve Performans
Üç farklı model eğitildi. Sonuçlar şu şekildedir:

#### 1. Lojistik Regresyon
* **Doğruluk:** %88.50
* Veri seti için güçlü bir temel (baseline) oluşturdu.
![Logistic Regressşon Graph](images/LR.png)

#### 2. K-En Yakın Komşu (KNN)
* **Doğruluk:** %87.09
* KNN modeline ait performans grafiği aşağıdadır:
![KNN Graph](images/KNN.png)

#### 3. Karar Ağacı (En İyi Model 🏆)
* **Doğruluk:** **%90.14**
* Karmaşık ilişkileri yakalayarak en yüksek başarıyı bu model gösterdi.
![Decision Tree Graph](images/DT.png)

---

### 🔗 Connect with Me
<a href="https://www.linkedin.com/in/furkan-izmir-017249331/" target="_blank">
<img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn">
</a>

*(Click the badge above to visit my profile)*
