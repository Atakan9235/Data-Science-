# Data-Science-
Bist100 verileri ve hacmi,dolar kuru,gram altın fiyatları haftalık verileri csv dosyaları halinde indirilmiş tek bir veri seti halinde işlenerek pandas dataframe haline dönüştürülmüştür.Bist100 hacim verisi hariç diğer para birimleri ve endeks değerleri TL para birimi cinsine dönüştürülmüştür.Uygun Lstm miamri ve parametre sayısı belirlenmeden önce tek bir epoch verisi için  en iyi uygun Optimizer ve Loss fonksiyonları bir döngü içinde bütün kombinasyonları hesaplanmıştır.En uygun optimizer RMSprop Loss fonksiyonu ise Huber olarak bulunmuştur.Yazılan kod optimizerandloss.jpg dosyası halinde paylaşılmıştır.Elde edilen dataframe LSTM yapay sinir ağları ile modellenmiş ve bist harici ekonomik göstergelerin fiyatlarına göre bir fiyat tahmini oluşturulmaya çalışılmıştır.Son halini alan veri paketi proje.csv adıyla paylaşılmıştır.Günümüz makro ekonomik koşullarının daha çok parametreden etkilendiği aşikardır.Ancak bu projedeki temel amaç belirlenen ana göstergelerin fiyatlarının bist fiyatlamasına olan etkisini incelemek ve  daha ileri yapılabilecek algoritmalar  için katkı verecek bir kaynak oluşturmaktır.  
