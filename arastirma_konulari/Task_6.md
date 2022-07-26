# HTTP NEDIR ?

Http (Hypertext Transfer Protocol) kelimesinin kisaltilmis halidir.

Bir programa dili degildir. Bir kural silsilesidir. Su sekilde dusunulebilir;
mesela siz birisiyle tanismak istediginiz yapacaniz haraket ve soyleviniz ne olurdu?

Tanimadigimiz bir insanla tanisirken , tanimadigimiz insana merheba ben <isminiz> olarak hitap edersiniz ve elinizi sikmasi icin uzatirsiniz.

Karsidaki kisi size ayni sekilde , merhaba ben de <ismi> diyerek havadaki elinizi sikar.

Burada merhaba dememizin sebebi biz insanlar olarak tanistigimizda ilk olarak merhaba kelimesini kullanmamiz gerektigini biliyoruz. Yani bir kural silsilesinin bir baslangicini olusturmusuz insanlar olarak.

Http ye donecek olursak . Client olarak biz daha dogrusu web tarayicisi diyelim , sunucuya merhaba ile baslayan bir mektup gondermis olduk ve bunun altinda sunucuya istedigimiz olan web sitesinin adresini soyledik.
Bu web sitesinin adresini soylerken de belirli bir yazim kullandik .

```
GET / HTTP/1.1
Host : www.tubitak.gov.tr
                    .
                    .
                    .
```

Yukaridaki bloga bakacak olursak GET "istedigimiz seyin getirilmesi icin , kullandigimiz getirme komutu "

HTTP ise ; nasil ki insanlarla tanisirken kullandigimiz merhaba kurali gibi .

1.1 Guvenlik uzerine yapilan yama sonrasi verilen guncellenmis surumu belirtmektedir.

Buradaki host ise bizim baska birisine mektup yazdigimizda , yazdigimiz iceriktir.

Server bu icerige gore gerekli olan yaniti verir ve bizim istedigimiz sayfaya ulasmamizi saglar.

Daha detayli anlatima asagidaki link uzerinden ulasabilirsiniz.↓

[CS50 HTTP COURSE](https://www.youtube.com/watch?v=PUPDGbnpSjw)
