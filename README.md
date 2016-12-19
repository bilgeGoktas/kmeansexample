# kmeansexample

K-Ortalama Algoritması (K-Means Algorithm)

Kümeleme, iş zekası, görüntü tanıma, web arama, biyoloji ve güvenlik alanlarında yaygın olarak kullanılır. Görüntü tanımada el yazısı karakterlerini bulmak için veri kümelere ayrılır. Kümeleme yöntemleri, bölümleme, hiyerarşik, yoğunluk tabanlı ve ızgara tabanlı olmak üzere dört şekilde uygulanır. Bölümleme metodu, k-means ve k-medoids yöntemlerinden oluşmaktadır.

K-Ortalama Algoritması özellik çıkarımı yapılmış bir grup verinin birden fazla küme özelliğine göre hangi kümeye ait olduğunun bulunmasını amaçlamaktadır. En sık kullanılan kümeleme algoritmasıdır. Uygulaması kolaydır. Küme merkezi tabanlı bir tekniktir. Bölümleme N elemanı k kümeye ayırır. Oluşan kümelere A denirse, A 1’den A k’ya k adet küme oluşur ve her küme N’nin altkümesi A i ⊂ N iken kümeler arası benzerlik yoktur. Küme içindeki değerler ise birbirlerine çok benzemelidir.

Algoritmanın aşamaları:

1.	k küme merkezleri belirlenir.

2.	Elemanların k merkezlerine olan uzaklıkları hesaplanır ve k merkezlerine en yakın noktalar bir kümeyi oluşturur. 

3.	Küme merkezlerinin ortalaması belirlenir ve merkezler tekrar belirlenir.

4.	Eğer merkez değişmişse noktaların merkeze olan uzaklıklarına göre hangi merkeze ait oldukları bulunur ve bu işlem küme merkezleri stabil hale gelene kadar devam eder.

K-Ortalama Algoritmasının avantajları küme sayısı azsa büyük veri setlerinde hiyerarşik kümelemeye göre daha hızlı olması ve veri seti küresel ise hiyerarşik kümelemeye göre daha sıkı kümeler oluşturmasıdır. Dezavantajları ise üretilen kümeler arasında kıyas yapmak zor olur. Sabitlenmiş küme sayısı, küme sayısının tahminini zorlaştırır. Küresel olmayan veri setlerinde iyi çalışmaz. Farklı başlangıç bölümlemeleri ile farklı sonuç kümeleri elde edilir.
