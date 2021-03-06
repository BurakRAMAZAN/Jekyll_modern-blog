---
title:  "PHP mi ASP.NET mi ?"
subtitle: "Just develop it"
author: "Burak"
avatar: "img/authors/wferr.png"
image: "img/f.jpg"
date:   2015-12-25 12:12:12
---
Yıllardır web yazılımla uğraşan herkesin kendine sorduğu sorudur: Asp.Net mi yoksa Php mi kullanmalıyım ? Öncelikle şunu söylemeliyim ki bu yazının sonunda bir boks maçında olduğu gibi bir galip çıkmayacak. Bu yazıyı yazmamdaki neden önceden kendimin de yaşadığı bu kararsızlığı mantıksal sonuçlara dayandırarak karar vermenizi kolaylaştırmak. Ben de bilgisayar mühendisliğine ilk başladığım yıllarda bu ikileme çok düştüm. O zamanlar daha kolay öğrenebileceğimi ve de  freelance çalışmalar için daha uygun olduğunu düşündüğümden dolayı Php ile yazılım geliştirmeyi tercih etmiştim. 2 yıl sonra bir iş görüşmesine gitmiştim. Burada neden php dilini kullandığımı ve Asp.Net ‘e göre kaliteli yazılım geliştirmede ne gibi faydaları olduğunu sorduklarında verebilecek bir cevabımın olmadığını farkettim. Sadece kolay öğrenebileceğimi düşündüğüm için Php kullanıyordum ve bu güne kadar hiç böyle bir soruyu kendime sormamıştım. Eve döndüğümde araştırmaya koyuldum ve dillerin avantaj ve dezavantajlarını yazdım. Hangi avantajların benim için önemli, hangi dezavantajların daha gözardı edilebilir olduğuna karar vererek yazılım konusunda kendi adıma yeni bir sayfa açmıştım.

Gelelim karşılaştırmaya. Birçok sitede Bu karşılaştırmalar bir taraftar edasıyla yapılıyor maalesef. Asp.net kullanıcıları Php’yi eleştirip dururken Php kullanıcıları da Php’yi yerlere göklere sığdıramıyor. Ben bu konuda elimden geldiğince tarafsız olarak dillerin avantajlarından ve dezavantajlarından bahsetmeye çalışacağım.

Hadi başlayalım ;

### 1.Derleyici


Microsoft’un geliştirdiği bir IDE olan Visual Studio herhalde bu konuyu tartışanların tek ortak noktası. Asp.Net ‘i ön plana atan en önemli özelliği Visual Studio gibi mükemmel bir IDE’ ye sahip  olmasıdır. Php için de çeşitli geliştirme araçları olsa da Visual Studio alanının lideri ve tartışmaya yer bırakmayacak kadar iyi bir geliştirme aracıdır.

### 2. Performans ve Hız


Bu konuda bu daha iyi demek taraflı bir yorum olacaktır sanıyorum. Çünkü sitenizin performansı kullandığınız dilden ziyade birçok faktöre bağlıdır. Genellikle büyük web siteleri (Google, Facebook,Yahoo vb.) bu problemi açık kaynaklı ve her biri o dilin en iyi yaptığı işi yapması için seçilen birçok programlama dili kullanarak maksimum performans elde ediyor.

Performansı etkileyen önemli ölçütlerden birisi veritabanına bağlantı kurup burada sorguyu gerçekleştirerek sorguyu web sunucuya ordan da tarayıcıya aktarmaktır. Burada da programlama diliyle veritabanı arasındaki ilişki önem kazanmaktadır. Günümüzde Php ve MySql arasındaki iletişim Asp.Net ve MsSql arasındaki iletişime göre daha hızlıdır diyebiliriz. Yine de bu durum sitenizde gözle görülür bir fark yaratmayacaktır.

Diğer performans farklılıkları şu şekilde;

Php, çalışma  anında hem derlenip hem çalıştırılırken Asp.net kodları çalıştırılmadan önce dll’lere derlenerek çalışmayı hazır hale getirilip saklanmaktadır bu nedenle sunucu tarafında Asp.net daha hızlı çalışır diyebiliriz.
Kullanıcı taraflı çalışma ve sayfa yükleme hızları geliştiricinin  tecrübesi ve kullandığı teknolojilere göre büyük ölçüde değişebilmektedir.
 

### 3. Web Site Hazırlama


Php kullanarak sıfırdan bir web sitesi hazırlamak zahmetli bir iş olacaktır. Asp.net bu konuda mevcut kontrolleri kullanarak ortalama ihtiyaçlarınızı karşılayacaktır. Fakat projeleriniz büyüdükçe Asp.net ‘in  mevcut kontrolleri sizin için birçok sıkıntı da yaratabilir. Bu aşamada Php ‘nin çok sevilen bir yönü ortaya çıkmaktadır: Php tabanlı içerik yönetim sistemleri.

Nedir bu içerik yönetim sistemleri ?

WordPress, Joomla, Drupal, Oscommerce ve Magento gibi neredeyse her web yazılımı için geliştirilmiş açık kaynaklı bu sistemleri indirip ihtiyaçlarınıza göre kolayca kullanabilir ve geliştirebilirsiniz. Bu da Asp.net ‘te olmayan ve Php ‘nin tercih edilmesinde önemli rol oynayan maddelerden biridir.

### 4. Maliyetler


Geliştirme araçları, barındırma hizmetleri, çeşitli sertifikasyon ücretleri…

Maliyetler size şuan çokta önemli gözükmeyebilir fakat Firmaların ana amaçlarının karlılık olduğu düşünülürse yapılan işlere göre çok ciddi maliyetler ortaya çıkabilmektedir. Php, açık kaynaklı olması ve tercih edilirliğinden kaynaklı olarak hosting ücretlerinin daha uygun olması, ücretsiz ve cüzi fiyatlara IDE ‘lere sahip olması ile sertifikasyon ve lisans ücretleri gerektirmemesinden dolayı Asp.net ‘e göre oldukça ucuzdur. Özellikle firmalar için ciddi maliyet farklılıkları oluşturabildiğinden Php bu konuda tercih sebebidir.

### 5.Kullanım Oranı 


Elbette dünyada birçok Asp.net ya da Php kullanan web sitesi mevcut. Genel kullanıma bakıldığında Php, Asp.net ‘e göre daha fazla kullanılıyor. Bunda da maliyetlerin ve wordpress, joomla gibi içerik yönetim sistemlerinin büyük etkisi bulunuyor. Fakat işin ticari boyutuna bakıldığında firmalar genellikle Asp.net kullanmayı tercih ediyor. Özellikle ülkemizde genellikle banka ya da önde gelen e-ticaret sitelerinin Asp.net kullandığını görebiliriz.  Örneğin; Kariyer.Net ‘te şuan 325 Asp.net ilanı varken 149 Php iş ilanı bulunmaktadır.

Bu dilleri kullanan bazı popüler web siteleri;

Php:  Facebook, Apple, Wikipedia, Yahoo, Flickr, Vimeo

Asp.net: MySpace, Msn, Ebay, Live, BankofAmerica, Jd
