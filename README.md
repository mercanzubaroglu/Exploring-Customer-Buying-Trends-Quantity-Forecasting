# MachineLearningGlobalAIHub
**Proje Sonuçları ve Performans Karşılaştırması**
Bu projede, e-ticaret veri seti kullanılarak Random Forest Regressor algoritması uygulanmıştır. Apriori algoritması, veri setinin büyük boyutu nedeniyle uygulanamamıştır; bu nedenle yalnızca Random Forest algoritmasının performansına odaklanılmıştır.

Veri Seti
**E-ticaret Veri Seti:**

**Açıklama:** Kullanılan veri seti, e-ticaret platformlarından elde edilen satış ve müşteri bilgilerini içermektedir. Bu veri seti, müşteri alışveriş davranışlarını, ürün satışlarını ve ülkelere göre satış dağılımını içeren çeşitli özellikler barındırmaktadır. Büyük boyutu ve karmaşıklığı, veri analizi ve modelleme sürecinde önemli bir rol oynamıştır.
Kullanılan Öğrenme Algoritması
**Random Forest Regressor**
*Açıklama:* Random Forest, birçok karar ağacının birleşiminden oluşan bir topluluk yöntemidir. Karmaşık veri ilişkilerini modellemede etkili olup, geniş veri setlerinde yüksek performans gösterebilir. Veri setindeki karmaşık ilişkileri ve etkileşimleri modelleme yeteneği sayesinde etkili sonuçlar elde edilmiştir.
**Performans:**
Mean Absolute Error (MAE): [MAE değeri]
R² Score: [R² değeri]

**Diğer Yöntemler**
Projede Apriori algoritması veri setinin büyük boyutu nedeniyle uygulanamamıştır. Bu nedenle, diğer gözetimli öğrenme yöntemleri de değerlendirilmiştir. Denenen gözetimli öğrenme yöntemleri yaklaşık olarak benzer sonuçlar vermiştir, bu da veri setimizin özelliklerine göre bu yöntemlerin genel olarak aynı performansı sergilediğini göstermektedir.

Veri Setinin Uygunluğu
**Random Forest Regressor:**

**Uygunluk Nedeni:** E-ticaret veri setinin geniş ve karmaşık yapısı, Random Forest algoritmasının karmaşık ilişkileri etkili bir şekilde modellemesine olanak tanımıştır. Özellikle büyük veri setlerinde Random Forest'ın güçlü performansı gözlemlenmiştir.
Apriori Algoritması:

**Uygulanamama Nedeni:** E-ticaret veri setinin büyük boyutu, Apriori algoritmasının eğitim sürecinde bellek ve işlem süresi sorunlarına neden olmuştur. Bu nedenle, Apriori algoritması veri setimiz üzerinde başarılı bir şekilde çalıştırılamamıştır.
**Sonuç**
Sonuç olarak, e-ticaret veri seti üzerinde Random Forest Regressor algoritması etkili bir şekilde kullanılmıştır ve performans değerlendirmeleri yapılmıştır. Apriori algoritması, veri setinin büyüklüğü nedeniyle uygulanamamış ve diğer gözetimli öğrenme yöntemlerinin performansı benzer sonuçlar göstermiştir. Bu proje, e-ticaret veri setleri ile algoritma seçiminin önemini ve performans değerlendirmelerinin nasıl yapıldığını vurgulamaktadır.
