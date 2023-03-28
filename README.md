# airbnb-price-analysis
Elde ettiğimiz veri setini kullanarak İstanbul'daki Airbnb evlerinin fiyatları hakkında bazı analizler yaptık. İlk olarak, geopandas kütüphanesi kullanarak evlerin verilerini içeren veri setini yükledik. Daha sonra, İstanbul'un semtlerini gösteren bir GeoJSON dosyasını yükleyerek adı altında bir değişkene atadık. Veri setindeki bazı eksik değerleri içeren satırları çıkardık. Ardından, veri setindeki evlerin konumlarını haritada işaretledik ve semtlerle birleştirdik. Her semtteki evlerin fiyat ortalamalarına göre sıralanmış bir veri seti oluşturduk ve bunu semtlerin sınırlarını içeren dosya ile birleştirdik. Son olarak, semtlerin sınırlarını ve evlerin fiyat ortalamalarını içeren bir dosya oluşturduk. Bu sayede, İstanbul'daki farklı semtler arasındaki fiyat farklılıklarını görselleştirebildik.

verileri aldığımız site
http://insideairbnb.com/get-the-data/
