#  Medium Websitesinin Mimarisinin Clonlanması 

## Siteyi buradan görüntüleyebilirsiniz => [Click Me](https://medium-clone-deploy.surge.sh)

***

## Kullanılanlar Yapılar ve Eklentiler
- Html
- Css
- Bootstrap
- Fontawesome
- Surge.sh


***
***


## Bootstrap ve Diğer Eklentilerin Yüklenmesi
- İlk olarak bootstrap dökümanlardan versiyon 4.5 seçilir ve dowmload kısmından Compiled CSS and JS dosyası localimizze indirilir.
- Sitede kullanılan iconlar için  Fontawesome eklentisini kullanacağız [fontawesome](https://fontawesome.com/) sitesinden 
   
***

### Artık Aşama ikide bu kalsörleri rar dan çıkartıyoruz. 

* fontawesome-free-5.15.4-web dosya adını fontawesome olarak değiştiriyoruz ve proje klasörümüzün içine (index dosyasının bulundugu dizin) koyuyoruz.
* bootstrap-4.5.3-dist klasörünün içindeki css ve js klasörlerini içinden alıp proje klasörümüzün içine yapıştırıyoruz.

*** 

Eklentiler hazır şimdi index sayfasını oluşturup programlamaya geçebiliriz...

* Daha önceden bootstrapt starter template ti kopyalayarak html kısmını oluşturuyorduk bu sefer bunu kullanmayacağız kendimiz elle oluşturacağız.
* Bunun için bootstrapt dökümandan İnroduction kısmına gidiyoruz.
* JS lerimizde nelerimizin olması gerekiyormuş ona bakıyoruz. CSS altında JS ve Onun altında Bundle kısmı var. Burada İlgli uzantılar var. Burada jquery-3.5.1.slim.min.js ve bootstrap.bundle.min.js dosyalarının olması gerektiğini gösteren iki satırlık script ayarlarımız var

    ```` html
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>

    ````

* jquery i gidip sitesinden indiriyoruz [indirme linki](https://code.jquery.com/jquery-3.5.1.slim.min.js)

linki kopyalayıp tarayıcımızın arama kısmına yapıştırıyoruz. bütün jquery kodlarının boşluksuz olarak yer aldığı sayfa açılacak. bu sayfayı olduğu gibi sağ klick farklı kaydet diyoruz. js uzantılı olarak proje klasörümüzün içindeki /js klasörümüzün içine kaydediyoruz.

* Artık elle oluşturma işlemine başlayabiliriz. 

    * Artık index.html dosyamızı açıyoruz; html etiketimizi oluştruyoruz. 
    Fakat istersek buradaki meta tag etiketinin yerine

    ```` html
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    ````

    bootsrapt starter template içindeki güncel meta taglarınıa alıp projemize yapıştıralım.

     ```` html
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    ````

    * Link:css diyerek css dosyamızı ekliyoruz   /css/bootstrap.min.css dosyamızı seçiyoruz.
    * Aynı şekilde /fontawesome/css/all.min.css linkimizide ekliyoruz
    * Son olarak js dosyalrını script:src etiketi içinde body nin içine kodların en sonuna gelecek şekilde ekliyoruz. 
    * Artık tüm ayarlamalarımızı yaptık, Medium clonu için medium web sitesini açıyoruz ve gerekli kodlamaları yapmaya başlayabiliriz.

***
***

## Kaynaklar
* https://medium.com/
* https://getbootstrap.com
* https://code.jquery.com/jquery-3.5.1.slim.min.js
* https://fontawesome.com

***

### İletişim
* [Ümit GENİŞ](https://github.com/umitgenis/) | [e-mail adress for click](umitgenis@gmail.com)            
