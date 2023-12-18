# BMB311 İşletim Sistemleri 2023-2024 Güz Dönemi Uygulama Notları, Projeleri ve Ödevleri

Bu repo'da uygulama derslerine ait materyallere (ders notlari, odev bilgileri, proje bilgileri, duyurular vb.) ulasabilirsiniz.

### Iletisim

Ars. Gor. Güvenç Usanmaz

Oda: B207

Bolum: Bilgisayar Muhendisligi

Email: gusanmaz <att< nku nokta edu nokta tr


### Onerilen Kaynaklar

#### Isletim Sistemleri

* [Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/) ***Teorik Kaynak***
* [Advanced Linux Programming](https://mentorembedded.github.io/advancedlinuxprogramming/alp-folder/) ***Pratik Kaynak***
* [Operating Systems: Crash Course Computer Science #18](https://www.youtube.com/watch?v=26QPDBe-NB8) ***~10 dakikada isletim sistemleri***
* [Turkce Linux Dersleri](https://linux-dersleri.github.io/)
* [Belgeler.org (Muhtemelen Guncel Degil)](http://www.belgeler.org/)
* [Prof. Kemal Bıçakçı İşletim Sistemleri Ders Videoları](https://www.youtube.com/watch?v=sqtkwd09KXs&list=PLmPsb7nQhv7NLRWdIiDVNBDCMOtuUn6WZ) - Ilgili videolarda kaynak kitap olarak **Operating Systems: Three Easy Pieces** kullanilmaktadir.

#### Komut Satiri ve Kabuk Programlama

* [Linux Tutorial](https://ryanstutorials.net/linuxtutorial/)
* [Linux/Mac Tutorials - Corey Schafer](https://www.youtube.com/playlist?list=PL-osiE80TeTvGhHkpvfmKWOiIPF8UVy6c)
* [Bash Scripting](https://ryanstutorials.net/bash-scripting-tutorial/)
* [UNIX: Making Computers Easier To Use -- AT&T Archives film from 1982, Bell Laboratories](https://www.youtube.com/watch?v=XvDZLjaCJuw&t)

#### C Programlama

* [C Programming Language, 2nd Edition](https://www.amazon.com/Programming-Language-2nd-Brian-Kernighan/dp/0131103628/ref=sr_1_1?crid=YQFLRR2SUKAG&keywords=c+programming&qid=1665091837&qu=eyJxc2MiOiI1LjIxIiwicXNhIjoiNC42OCIsInFzcCI6IjQuNjMifQ%3D%3D&s=books&sprefix=c+programming%2Cstripbooks-intl-ship%2C275&sr=1-1)

* C dilinde kendini eksik goren ogrencilerimizin https://exercism.org/tracks/c sayfasindaki alistirmalari kodlamalari ve dogru kodladiklari alistirmalari baskalarinin nasil kodladigini incelemeleri tavsiye edilir.

### Onerilen Linux Dagitimlari

* [Distrowatch](https://distrowatch.com/) Bu sitede çok sayıda Linux dağıtımı hakkında bilgi bulunmaktadır. Size en uygun dağıtımı tespit etmek için bu siteyi inceleyebilirsiniz.
* Ubuntu
* KDE Neon
* Pop!_OS
* OpenSuse
* Manjora

#### Linux Kurulumu
* Dual-boot
* Single-boot
* Sanal makine (Virtual Box, WMvare)
* Windows Subsystem for Linux (WSL)
* Virtual Private Server (VPS)
* B205 (?)
* Cygwin (?)
* [Repl.it](replit.com)

### AWS'de Linux Istance'i Olusturma

[https://github.com/Mona-Roza/Notes/tree/main/About%20Server%20%26%20About%20Linux](https://github.com/Mona-Roza/Notes/tree/main/About%20Server%20%26%20About%20Linux)

### Oracle VM VirtualBox Üzerine Debian Linux Kurulumu

[https://medium.com/@zeynepssasmaz953/oracle-vm-virtualbox-u%CC%88zerine-debian-linux-kurulumu-2c87dbe64aa9](https://medium.com/@zeynepssasmaz953/oracle-vm-virtualbox-u%CC%88zerine-debian-linux-kurulumu-2c87dbe64aa9)

#### Kurulumda Dikkat Edilecekler
* Onemli Verilerin Yedeklenmesi
* BIOS Boot Oncelikleri
* Disk Bicimlendirme (Gparted vb.)
* Once Windows, sonra Linux Kurulumu (?)
* USB ISO Creator (Etcher, UnetBootin)
* Legacy boot vs. UEFI
* Secure boot

#### Beklentiler
* Github hesabi acmak
* Bilgisayara Linux dagitimi kurmak
* Github Discussion sayfasinda aktif olmak
* Bu sayfayi duzenli araliklarla kontrol etmek
* Bu sayfada ilan edilecek proje ve odevlerde istenilenleri yapmak
* Universite email hesabinizi duzenli araliklarla kontrol etmek.

### Projeler

#### 1. Proje

**Ön Hazırlık**
* Github hesabı açınız.
* Bilgisayarınıza bir Linux dağıtımı kurunuz.
* Kurmuş olduğunuz Linux dağıtımını incelip, bu dağıtımın nasıl kullanılabileceği konusunda deneyim edinmeye çalışınız.

**Proje Açıklaması**

* Bu projede [https://ryanstutorials.net/linuxtutorial/](https://ryanstutorials.net/linuxtutorial/) adresindeki 13 farklı bölümden oluşan tutorial'ı okuyup, burada anlatılan bilgileri anlamanız gerekmektedir.
* Bu tutorial'daki konuların uygulama dersinde de anlatılacaktır.
* Bu proje kapsamında en fazla 8 kişilik gruplar halinde bu tutorialda anlatılan konuların tamamını anlatan birer video çekmeniz gerekmektedir.
* Çekeceğiniz videoya format olarak bu videoya benzeyebilir: https://www.youtube.com/watch?v=ZtqBQ68cfJc
* Yukarıdaki örnek videoda kod yazılan zamanlarda terminal ekranının videoya yansıtıldığına dikkat ediniz.
* Videolarda konuştuğunuz zamanlar ufak bir alanda kendi görüntünüze de yer vermeniz güzel olacaktır. Örnek: [https://www.youtube.com/watch?v=gd7BXuUQ91w](https://www.youtube.com/watch?v=gd7BXuUQ91w)
* Hem Linux komut satırını anlamada, hem de nasıl bir formatta video hazırlamanızın daha iyi olabileceği konusunda fikir edinmek için yukarıda örnek olarak verilen 2 Youtube videosuna benzer videoları seyredebilirsiniz. 
* Bütün grup üyelerinin videoda bir konu anlatması gerekmektedir. Örneğin grubunuz 6 kişilik bir grupsa 5 kişi 2 konu, 1 kişi de 3 konu anlatabilir. Grup uyelerinizin ogrenim turu ayni olmak zorunda degil. 1. ogretim ve 2. ogretim karisik grup olusturabilirsiniz.
* Her grup üyesinin projeye mümkün olduğunda eşit ölçüde katkı vermesi beklenmektedir. Projeye katkıyı sadece videoda konu anlatımı olarak düşünmeyiniz. Video post production, tutorialdaki konuların araştırılması, Türkçeye çevrilmesi gibi işler de proje çalışması olarak değerlendirilmelidir.
* Projeniz linki verilen tutorialın birebir videolaştırılmış hali olmasın. Tutorialdan öğrendiğiniz bilgileri tutorialdaki örnek kodlardan farklı kodlar yazarak da gösterebilirsiniz. İlginizi çeken komutları tutorialda anlatılandan daha kapsamlı anlatabilirsiniz.
* Projeniz Youtube'da bulabileceğiniz onlarca Linux komut satırı videosunun birebir kopyası da olmamalıdır.
* Her grup kendi videosunu çekmelidir. Başka bir grubun çektiği videoyu izleyip o videoyu birebir ya da büyük ölçüde taklit edecek videolar hazırlamayınız! Bu tür çalışmalar kopya olarak değerlendirilecektir.

**Ödev Gönderimi**

* Videonuz Youtube'a yükleyiniz. Videonuzun Youtube'da aramayla bulunabilir olmasını istemiyorsanız videonuzu sadece link ile erişilebilecek şekilde Youtube'a yükleyebilirsiniz.
* Ödevi yüklemeniz için bu davet linki üzerinden bir repo oluşturunuz: [https://classroom.github.com/a/0LNO9aUH](https://classroom.github.com/a/0LNO9aUH)
* Davet linki ile repo oluşturulduktan sonra bu repoda `bash.txt` isimli bir dosya oluşturunuz.
* `bash.txt` dosyasının içine sırayla her bir bilgi farklı satırda olacak şekilde önce video linkini sonra da grup üyelerinin öğrenci numaralarını yazınız.
* Örnek `bash.txt` içeriği:

 ```
  https://www.youtube.com/watch?v=gd7BXuUQ91w
  1234567890
  1234567891
  1234567892
  1234567893
  1234567894
  1234567895
```

* `bash.txt` dosyasını oluşturup içini doğru bir şekilde doldurduktan sonra reponuzun son halini kaydetmek (diğer bir deyişle ödevi göndermek) için repoyu **commit**`leyiniz.
* Grup üyelerinin her birinin bu işlemleri kendi Github hesapları üzerinden yapmasın gerekmektedir. Örneğin 4 kişilik bir grupsanız her bir grup üyesi aynı bash.txt dosyasını kendi repolarına ekleyip, repolarını commit etmeleri gerekmektedir.
* Youtube'a yüklediğiniz videonun açıklama kısmına da öğrenci numaralarınız ve isim - soyisim bilgilirini ekleyiniz.
* Ödev son gönderim tarihi 26 Kasım 2023 23:59'dur. Bu tarihten sonra gönderilen ödevler değerlendirmeye alınmayacaktır.
* Ödev gönderiminde yukarıdaki adımları doğru uygulamanız çok önemlidir. Bu adımlarda yapacağınız bir hata ödevinizin değerlendirilmemesine ya da ödev puanınızın düşürülmesine sebep olabilir.

#### 2. Proje

**Ön Hazırlık**
* Operating Systems: Three Easy Pieces kitabının 5 (Process API), 26 (Concurency and Threads) ve 27 (Thread API) numaralı chapter'larını okuyunuz. 27. bölümü şu an için 27.3 Locks başlığına kadar okumanız yeterlidir.
* Okumuş olduğunuz kitap bölümlerinde verilen örnek kodları bilgisayarınızda çalıştırınız.

**Proje Açıklaması**

* Bu projede kitapta sizden okunmasını istediğiniz bölümleri anlatan bir video hazırlamanız istenmektedir.
* Videonuzdaki uygulama derslerindeki benzer şekilde özellikle kitaptaki kod örnekleri (p1.c, p2.c, p3.c, p4.c, t0.c, t1.c, thread_create.c, thread_create_simple_args.c, thread_create_with_return_args.c) üzerinde durmanız beklenmektedir.
* Videonuzda bu kodları kendi bilgisayarında çalıştırmanız, üretilen çıktıları değerlendirmeniz, ilgili kodu satır satır detaylı olarak açıklamanız beklenmektedir.
* Videoda bu kodları kendi bilgisayarında çalıştırabildiğinizi gösteremezseniz, ödevden 0 veya oldukça düşük bir not alabilirsiniz!
* Bu proje kapsamında en fazla 8 kişilik gruplar halinde bu tutorialda anlatılan konuların tamamını anlatan birer video çekmeniz gerekmektedir.
* Videolarda konuştuğunuz zamanlar ufak bir alanda kendi görüntünüze de yer vermeniz güzel olacaktır. Örnek: [https://www.youtube.com/watch?v=gd7BXuUQ91w](https://www.youtube.com/watch?v=gd7BXuUQ91w)
* Bütün grup üyelerinin videoda bir konu anlatması gerekmektedir. Grup uyelerinizin öğrenim türü aynı olmak zorunda degil. 1. ögretim ve 2. öğretim karışık grup oluşturabilirsiniz.
* Her grup üyesinin projeye mümkün olduğunda eşit ölçüde katkı vermesi beklenmektedir.
* Her grup kendi videosunu çekmelidir. Başka bir grubun çektiği videoyu izleyip o videoyu birebir ya da büyük ölçüde taklit edecek videolar hazırlamayınız! Bu tür çalışmalar kopya olarak değerlendirilecektir.

**Ödev Gönderimi**

* Videonuz Youtube'a yükleyiniz. Videonuzun Youtube'da aramayla bulunabilir olmasını istemiyorsanız videonuzu sadece link ile erişilebilecek şekilde Youtube'a yükleyebilirsiniz.
* Ödevi yüklemeniz için bu davet linki üzerinden bir repo oluşturunuz: https://classroom.github.com/a/b0QLNtAS
* Davet linki ile repo oluşturulduktan sonra bu repoda `threads.txt` isimli bir dosya oluşturunuz.
* `threads.txt` dosyasının içine sırayla her bir bilgi farklı satırda olacak şekilde önce video linkini sonra da grup üyelerinin öğrenci numaralarını yazınız.
* Örnek `threads.txt` içeriği:

 ```
  https://www.youtube.com/watch?v=gd7BXuUQ91w
  1234567890
  1234567891
  1234567892
  1234567893
  1234567894
  1234567895
```

* `bash.txt` dosyasını oluşturup içini doğru bir şekilde doldurduktan sonra reponuzun son halini kaydetmek (diğer bir deyişle ödevi göndermek) için repoyu **commit**`leyiniz.
* Grup üyelerinin her birinin bu işlemleri kendi Github hesapları üzerinden yapmasın gerekmektedir. Örneğin 4 kişilik bir grupsanız her bir grup üyesi aynı bash.txt dosyasını kendi repolarına ekleyip, repolarını commit etmeleri gerekmektedir.
* Youtube'a yüklediğiniz videonun açıklama kısmına da öğrenci numaralarınız ve isim - soyisim bilgilerini ekleyiniz.
* Ödev son gönderim tarihi 3 Ocak 2024 23:59'dur. Bu tarihten sonra gönderilen ödevler değerlendirmeye alınmayacaktır.
* Ödev gönderiminde yukarıdaki adımları doğru uygulamanız çok önemlidir. Bu adımlarda yapacağınız bir hata ödevinizin değerlendirilmemesine ya da ödev puanınızın düşürülmesine sebep olabilir.
  
  
  
  


