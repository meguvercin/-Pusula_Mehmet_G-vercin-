# Pusula_Mehmet_Güvercin
Data Science Intern Case Study


# Pusula Drug Side Effects Analysis Project

## Proje Tanımı
Bu proje, ilaç yan etkileri ile ilgili bir veri seti üzerinde kapsamlı bir analiz yapmayı ve veriyi daha ileri tahmine dayalı modelleme için hazırlamayı amaçlamaktadır. Aşağıdaki aşamalar sırasıyla uygulanmıştır:
1. **Exploratory Data Analysis (EDA)**: Veriyi keşfetmek ve veri yapısını anlamak için veri görselleştirme teknikleri kullanıldı.
2. **Veri Ön İşleme (Data Preprocessing)**: Eksik verilerin doldurulması, kategorik verilerin sayısal verilere dönüştürülmesi ve sayısal verilerin ölçeklendirilmesi gibi işlemler gerçekleştirildi.

## Kurulum ve Gereksinimler
Proje, Python programlama dili ile yazılmıştır ve aşağıdaki kütüphaneler kullanılmaktadır:

- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

Gerekli kütüphaneleri kurmak için aşağıdaki komutu çalıştırabilirsiniz:

```bash
pip install -r requirements.txt
```

Kullanım Talimatları
Proje kodunu çalıştırmak için şu adımları izleyin:

Proje dosyalarını indirin ve uygun bir dizine yerleştirin.
Terminal veya komut satırında proje dizinine gidin.
Veriyi işlemek için Jupyter Notebook veya herhangi bir Python IDE'sinde drug_analysis.ipynb dosyasını çalıştırın.
Proje Aşamaları
1. Exploratory Data Analysis (EDA)
Veri yapısı incelendi: Verinin genel yapısı Pandas kullanılarak incelendi.
Eksik veri tespiti: Eksik veriler ısı haritası (heatmap) ile görselleştirildi.
Veri görselleştirme: Yan etkiler ve ilaçlar arasındaki ilişkiler çeşitli grafiklerle analiz edildi.
2. Veri Ön İşleme
Eksik veri doldurma: Eksik veriler SimpleImputer ile dolduruldu.
Kategorik verilerin sayısallaştırılması: Kategorik veriler OneHotEncoder ile sayısal değerlere dönüştürüldü.
Sayısal verilerin ölçeklendirilmesi: Sayısal veriler StandardScaler ile normalize edildi.
Pipeline Kullanımı: Veri işleme adımları pipeline kullanılarak modüler ve tekrar kullanılabilir bir yapı oluşturuldu.
3. Sonuçlar
Veri başarılı bir şekilde işlenmiş ve modellemeye hazır hale getirilmiştir. Elde edilen veri ile çeşitli tahmine dayalı modeller eğitilebilecek yapıdadır.

İletişim Bilgileri
İsim: Mehmet Emin Güvercin
E-posta: m.guvercin34@gmail.com
