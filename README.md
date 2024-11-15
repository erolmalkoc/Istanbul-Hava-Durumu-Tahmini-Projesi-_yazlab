# İstanbul Hava Durumu Tahmini Projesi
## 1.Özet
Bu projede, İstanbul'un hava durumu tahminlerini yapmak amacıyla yapay zeka kullanılarak bir model geliştirilmiştir. Meteostat veritabanından otomatik olarak veri çekilmesi için Selenium aracı kullanılmış ve veriler Python ile işlenmiştir. Zaman serisi analizi yapılarak, sıcaklık, nem ve rüzgar gibi faktörlerin gelecekteki değerleri tahmin edilmiştir. Bu çalışma, hava durumu tahminlerinin daha doğru ve verimli hale getirilmesi için gelecekteki projelere temel oluşturmayı hedeflemektedir.


## 2. Geliştirme Ortamı
Bu projede kullanılan araçlar ve kütüphaneler aşağıda listelenmiştir:

Selenium: Dinamik web sayfalarından veri çekmek için kullanıldı. Python ile entegre edilerek, Meteostat veritabanından hava durumu verileri otomatik olarak alındı.

Python: Veri işleme ve modelleme işlemleri için kullanıldı. Aşağıdaki kütüphanelerle veri analizi ve modelleme gerçekleştirildi

Pandas: Verilerin işlenmesi, temizlenmesi ve analiz edilmesi için kullanıldı.

NumPy: Veri analizi ve hesaplama için kullanıldı.

Matplotlib & Seaborn: Verilerin görselleştirilmesi ve analiz sonuçlarının grafiklerle sunulması için kullanıldı.

Zaman Serisi Analizi: Veriler zaman dilimlerine göre incelendi, trend ve mevsimsellik analizleri yapıldı, tahminler için model oluşturuldu.

Excel: Verilerin saklanması, görselleştirilmesi ve detaylı analizlerin yapılması için kullanıldı.
Kullanılan Kütüphaneler:
Selenium WebDriver
Pandas
NumPy
Matplotlib
Seaborn
OpenWeather API (veri toplama için)
Statsmodels (zaman serisi analizi için)

## 3. Veri İşleme ve Grafik Çıkarımı
Proje kapsamında, çekilen hava durumu verileri üzerinde zaman serisi analizi yapılmış ve bu verilerden trend, mevsimsellik gibi bileşenler ayrıştırılmıştır. Elde edilen veriler görselleştirilerek kullanıcıya sunulmuştur. Çıkarılan grafikler aşağıdaki gibi özetlenmiştir:

Zaman Serisi Grafik: Verilerin zaman içinde nasıl değiştiği gösterildi.
Trend Grafik: Verinin genel eğilimi ve uzun vadeli hareketi ortaya kondu.
Mevsimsellik Grafik: Verinin belirli dönemlerdeki (örneğin yaz, kış) değişimlerine odaklanıldı.
Tahmin Grafiği: Gelecekteki hava durumu değerlerinin tahmin edildiği grafikler oluşturuldu.
Bu grafikler, verinin geçmişteki davranışlarını anlamamıza ve gelecekteki tahminleri yapmamıza olanak tanımaktadır.

## 4. Geliştirilen Zaman serisi Grafik

![zamanserisigrafik](https://github.com/user-attachments/assets/03bb45a7-e29e-4561-b5d4-2044ddb5ac71)
İstanbul için bu grafiklerde görülen döngüsel yapı, şehrin dört mevsimi belirgin olarak yaşadığını ve sıcaklıkların mevsimlere göre düzenli bir şekilde değiştiğini gösteriyor.
Özellikle yaz aylarında sıcaklıklar yüksek, kış aylarında ise oldukça düşük seyretmekte.
Bu grafikteki düzenli döngü, İstanbul’un ikliminin yıllar arasında çok büyük bir değişiklik göstermediğini ve sıcaklıkların yıllık bazda tutarlı bir şekilde tekrar ettiğini işaret ediyor.



## 5.Kaynakça
https://www.selenium.dev/documentation/ 

https://medium.com/kodluyoruz/selenium-webdriver-ile-test-senaryosu-107ad1f99229

https://muhammedtalhacevik.medium.com/temel-selenium-komutlar%C4%B1-ve-i%CC%87%C5%9Flevleri-web-otomasyonunun-temelleri-a6be9066f64d

https://www.w3schools.com/python/pandas/default.asp

https://www-browserstack-com.translate.goog/guide/python-selenium-to-run-web-automation-test?_x_tr_sl=en&_x_tr_tl=tr&_x_tr_hl=tr&_x_tr_pto=wa

https://meteostat.net/en/

https://selenium-python.readthedocs.io/waits.html 

https://mvnrepository.com/

https://www.w3schools.com/python/numpy/numpy_intro.asp

https://dev.to/aciklab/rest-api-e26 

https://towardsdatascience.com/how-to-use-selenium-to-web-scrape-with-example-80f9b23a843a?gi=50b438f27bbc 
