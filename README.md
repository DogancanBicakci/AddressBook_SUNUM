# AddressBook_SUNUM

Merhaba, Address Book projesi İstanbul - Beşiktaş Wissen Akademi'de Kursiyerlik yaptığım süreçte yazdık.Bu projede Trendyol,Getir gibi uygulamalardaki adres ekleme bölümünden esinlendik. Amacımız adres kaydı yapmaktır. Ayrıca gerçek hayata yaklaşmak ve istihdam sürecindeki hazır bulunuşluğu maksimum seviyeye getirebilmektir.

Burada projenin ekran resimlerini ve kaynak kodlardan bazı kod parçalarını aşağıda görebilirsiniz.

PROJE HAKKINDA TEKNİK BİLGİLER:

-->Proje Visual Studio .Net 6 ASP.NET MVC CORE ile yazıldı.
-->Proje Entity Framework Core Code-First yaklaşımıyla yazılmıştır.
-->Projede AspnetCore Identity kullanarak üyelik sistemini yazdık.
-->Projeyi 5 katman (EL,DAL,BLL,UI, AddressBookNeighborhoodsLoad) olarak yazdık. -AddressBookNeighborhoodsLoad katmanı Console uygulaması olup Mahalle datasını eklemektedir. (70bin data bulunuyor) Projede İlleri ve İlçeleri Excel dosyasını back-endde okuyarak veritabanına proje ilk ayağa kalktığında ekledik.
-->Projede Adres listesi ve Adres Ekle - Adres Sil ekranları bulunuyor. Adres Ekle sayfasındaki işlemleri AJAX ile yapmaktayız. Örneğin; ili seçtiğinde ilçeler sayfa yenilenmeden gelir. İlçeyi seçtiğinde mahalleler sayfa yenilenmeden gelir. Mahalleyi seçince o mahallenin posta kodunu APi'den çektik. https://api.ubilisim.com/postakodu/il/34 Proje gelişmeye açık olup zaman buldukça yeni sayfalar ya da yeni özellikler eklenecektir. 

Ekran resimleri ve kaynak kodlardan bir parça aşağıda görebilirsiniz .

![image](https://user-images.githubusercontent.com/120460194/223098381-c3239433-3f51-431a-b0b0-c8b04d72deb1.png)
![image](https://user-images.githubusercontent.com/120460194/223098238-0c5afeef-b722-444a-9338-0d3df0d71b31.png)
![image](https://user-images.githubusercontent.com/120460194/223099031-cc9c33c3-514e-4842-a9e6-217a8cbfedf9.png)
<img width="254" alt="219574439-6f3c596d-6916-4fda-8b35-e23da3ddbc48" src="https://user-images.githubusercontent.com/120460194/223099070-a302aefc-c542-49b1-821d-e5df106d0757.png">
![image](https://user-images.githubusercontent.com/120460194/223099405-c1e2b6e8-d0b1-4a80-908c-96490b954770.png)
![image](https://user-images.githubusercontent.com/120460194/223099574-c739160f-a631-4e40-89b0-2caef115b81d.png)
