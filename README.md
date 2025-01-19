Kırmızı Şarap Kalitesi Tahmini
Makine öğrenimi yöntemleri kullanarak kırmızı şarap kalitesinin tahmin edilmesine yönelik proje.

Proje Açıklaması
Bu proje, kırmızı şarapların fiziksel ve kimyasal özelliklerinden yola çıkarak kalite tahmini yapmayı amaçlamaktadır. Çalışma kapsamında, farklı makine öğrenimi algoritmaları test edilmiş ve model performansları detaylı analizlerle değerlendirilmiştir. Bu proje, şarap üretim süreçlerini optimize etmeye ve kalite kontrol mekanizmalarına katkı sağlamayı hedeflemektedir.

Veri Seti
Projede kullanılan veri seti, UCI Machine Learning Repository'den alınmış olup 1599 adet kırmızı şarap örneğini içermektedir. Her örnek, 11 kimyasal özellik ve bir kalite skoruyla etiketlenmiştir. Daha fazla bilgi için UCI Red Wine Quality Data Set bağlantısını ziyaret edebilirsiniz.

Kullanılan Algoritmalar ve Yöntemler
Destek Vektör Regresyonu (SVR): Doğrusal olmayan ilişkileri modellemek için kullanılmıştır.
Rastgele Orman Regresyonu (Random Forest): Özellikler arasındaki etkileşimleri başarılı bir şekilde yakalamıştır.
K-En Yakın Komşu (KNN): Basit ve etkili bir algoritma olarak uygulanmıştır.
Veriler, modelin performansını artırmak için standartlaştırılmış ve eğitim/test olarak ayrılmıştır.

Sonuçlar ve Öneriler
Model, şarap kalitesini tahmin etmede başarılı bir performans sergilemiştir.
Veri seti, bazı sınıflarda dengesiz dağılım göstermektedir. Daha dengeli ve geniş veri setleriyle modelin genelleme yeteneği artırılabilir.
Çeşitli hiperparametre optimizasyonları ile model doğruluğu daha da artırılabilir.

Nasıl Kullanılır?
Colab Not Defteri: Proje kodlarını çalıştırmak için Colab bağlantısı kullanılabilir.
Gereksinimler:
Python 3.x
Gerekli kütüphaneler: NumPy, Pandas, Scikit-learn, Matplotlib

