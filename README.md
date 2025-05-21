## Giriş

Bu projede, haber metinlerinin sahte mi yoksa gerçek mi olduğunu belirlemek amacıyla FakeOrReal News Dataset kullanılmıştır.
Kullanılan algoritma:

-TF-IDF ile metin vektörleştirme

-Logistic Regression ile sınıflandırma

-GridSearchCV ile hiperparametre optimizasyonu

-Confusion Matrix, ROC-AUC, F1-Score gibi metriklerle model değerlendirmesi

## Metrikler

Projede gerçekleştirilen çalışma sonucunda elde edilen temel metrikler:

-Accuracy: 0.93
-Precision: 0.89
-Recall: 0.94
-F1-score: 0.93
-ROC-AUC: 0.98

Bu sonuçlar, Logistic Regression modelinin TF-IDF ile vektörleştirilmiş haber metinleri üzerinde yüksek başarıyla çalıştığını göstermektedir.ROC eğrisi neredeyse ideal bir sınıflandırıcıya işaret etmektedir.

## Ekler

Proje kapsamında ekstra bir bölüm olarak:

-random_news fonksiyonu ile gerçek dünyadan rastgele seçilen bir haber metni modele verilerek sınıf tahmini yapılmıştır.

-GridSearchCV ile modelin "C", "penalty", "class_weight" gibi parametreleri optimize edilmiştir.

-ROC eğrisi, confusion matrix, classification report gibi görsellerle desteklenmiş detaylı analizler yapılmıştır.

## Sonuç ve Gelecek Çalışmalar

Bu projede, klasik makine öğrenmesi yöntemleriyle haberlerin sahte olup olmadığını belirleyen başarılı bir sistem kurulmuştur.Gelecek aşamalarda:

-Derin öğrenme modelleri (RNN, BERT, LSTM gibi) uygulanabilir.

-Streamlit ile web tabanlı arayüz geliştirilebilir.

-Veri kümesi daha geniş, çok dilli ve gerçek zamanlı hale getirilebilir.

-Sosyal medya verileri entegre edilerek çoklu kaynaklardan haber doğrulama yapılabilir.

Bu proje, NLP ve metin sınıflandırma konularında kariyer hedefleri doğrultusunda geliştirilebilir ve genişletilebilir.

Linkler

https://www.kaggle.com/code/emreyoruk/fakeorreal
https://www.kaggle.com/datasets/vikasukani/news-data-set-fake-news-with-python
