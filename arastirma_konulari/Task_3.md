# MVC (Model-View-Controller) nedir?

- Yazilim mimari desenidir.
- Mobil , web , masaustu uygulamalarin gelistirme surecinde kullanilmaktadir.

### MODEL

---

<strong>Model :</strong> Model, proje içerisinde kullanılacak olan nesnelerin oluşturulduğu kısımdır. Günlük hayattaki somut nesnelerin, bilgisayar ortamında modellenmesi anlamına gelir. Örneğin bir kütüphane otomasyonu yapmak istediğimizde kitap bilgilerinin tutulacağı bir modele ihtiyaç duyulacaktır. Bu modelde kitabın seri numarası, adı, yazarı, yayınevi gibi bilgileri yer alacaktır.

### VIEW

---

<strong>View :</strong> Proje tamamlandığında kullanıcının gördüğü arayüzdür. Bu bir web sayfası, masaüstü uygulaması arayüzü veya mobil bir tasarım olabilir. Projenin yapısına göre bu tasarım farklı şekillerde oluşturulabilir.

### CONTROLLER

---

<strong>Controller :</strong>Projedeki tüm işlemlerin (veritabanı işlemleri, hesaplamalar, veri aktarımı v.b) yapıldığı kontrol bölümüdür. Controller ayrıca model ve view arasındaki veri akışını da kontrol eder.

## MVC Nasil Calisir ?

Bir MVC projesinde kullanıcı, tarayıcı üzerinden (View) sayfaya istek yaptığında bu istek Controller’a iletilir. Controller isteği gerçekleştirmek üzere model ve bağlantılı bileşenleri ile gerekli sınıf ve metotları çağırır. Elde ettiği sonuçları View’e göndererek sayfanın görüntülenmesini sağlar.
