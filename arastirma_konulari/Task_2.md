## MAVEN

---

Maven genellikle java platformunda yer alan komutlarin derlenmesi sirasinda kullanilan otomasyon ve insa aracidir .
Java gelistiriken cesitli kutuphaneler kullanmamiz gerekmektedir .

Her kutuphane icin gecerli olan JAR dosyalarini indirmek gerekmektedir.Her yeni guncelleme aldigimizda bu dosyalarin tekrardan elden gecirilmesi gerekmektedir. Buda bize bir zorluk olusturmaktadir . Maven ile proje dosyasina eklenen pluginler sayesinde proje dosyalarinin tasinabilirligi ve guncellemesini saglamis oluruz .

## MAVEN YAPISI

---

- /src/main/java ---> Java komutlarinin yer aldigi dizin yolu
- /src/main/resource ---> Ayar dosyalarinin yer aldigi dizin yolu
- /src/main/webapp ---> Css , Javascript gibi web dosyalari bu dizin yolunda yer alir.
- /target ---> Derlenen komutlarin ciktisinin alidigi dizin yolu .

## XML YAPISI

---

.xml
[extensible Markup Language , kisacasi Genisletilebilir Isaretleme Dili]

Xml verileri hem insan hem de makineler tarafindan anlasilir sekilde depolamak icin ve farkli platformlar arasinda tasinabilirlik saglagan etiket tabanli bir dildir (hmtl gibi).

### XML kullanim yerleri :

- XML verileri saklamak için bir yapı oluşturulabilir.
- Verileri farklı platformlar arası taşımak için kullanılabilir.
- Web sayfaları arasında veri paylaşımı için kullanılabilir.
- RSS, Feed, Ajax ve Web servisleri oluşturulabilir.

### XML Kurallari:

- Etiketlerin kapatilmasi gerekir.

  `<etiket>Etiket içeriği</etiket> `

- Etiketlerin içeriği boşsa

      ```<etiket/> ```

  seklinde kapatilmalidir.

- XML dosyalarinin basinda XML tanimlayicisi olmasi gerekmektedir.

  `<?xml version="3.0" encoding="UTF-8"?> `

- XML etiketleri; Etiketlerin başında sayı, özel işaret ve anahtar kelimeler olamaz.
- Kullanimi birnevi html table ozellikleri gibidir.

```<?xml version="1.0"?>
<kisiler>
  <kisi sira="1" adi="FATIH" soyadi="AYDIN" />
  <kisi sira="2" adi="FATIH" soyadi="AYDIN" />
  <kisi sira="3" adi="FATIH" soyadi="AYDIN" />
  <kisi sira="4" adi="FATIH" soyadi="AYDIN" />
</kisiler>

```

## MAVEN AYAR DOSYASI

---

Project Object Model (POM.xml) proje talimatlarini iceren dosyadir.

Uc kisimdan olusur.

- Project Meta Datasi
  - Proje Adi
  - Proje Surumu
  - Proje Ciktisi ve turu(jar,web)
- Dependencies(Bagimliliklari)
  - Hibernate
  - Spring
  - iText
