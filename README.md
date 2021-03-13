## GNU/Linux Notlarım

Bu repository GNU/Linux kullanmayı öğrenirken aldığım notları içermektedir. İşletim sistemi Pardus 19.04 ve masaüstü GNOME kullanılmaktadır. 

Güncelleme: İşletim sistemi Mint 20.1 "Ulyssa" - Cinnamon ile değiştirilmiştir.  

# İçerik Tablosu

* [Faydalı Bilgiler](#Faydalı-Bilgiler)

* [tar Arşivi Kurulum Adımları](#tar-Arşivi-Kurulum-Adımları)

* [Medium Yazılarım](#Medium-Yazılarım)

* [Faydalı Siteler](#Faydalı-Siteler)

* [Komutlar](#Komutlar)
   
    * [Dizin İşlemleri](#Dizin-İşlemleri)

    * [Disk ve Bellek İşlemleri](#Disk-ve-Bellek-İşlemleri)

    * [Paket Yönetimi İşlemleri](#Paket-Yönetimi-İşlemleri)

    * [Bilgi Alma İşlemleri](#Bilgi-Alma-İşlemleri)

    * [Servis İşlemleri](#Servis-İşlemleri)

    * [Kullanıcı İşlemleri](#Kullanıcı-İşlemleri)

## Faydalı Bilgiler

* | işareti AltGr + - (orta çizgi) ile yapılır. İlk komutun çıktısını ikinci komutun girdisi olarak çalıştırır.

* && - İlk yazılan komut çalıştırılır. Hata vermezse 2. komut çalıştırılır. Hata verirse 2. komut çalıştırılmaz. 

* || - İlk yazılan komut çalıştırılır. Hata vermezse 2. komut çalıştırılmaz. Hata verirse 2. komut çalıştırılır.  

* ; bir komut içerisinde birden çok komut yazmamızı sağlar. 

* & işareti komutun devamına eklenirse işlem çalıştırılır, arka planda devam eder ve tek satırda çıktı verir. Örnek olarak; `sudo apt-get update &: [1] 9312` 

* Sistem dilinin İngilizce yapılması çoğu hatanın önüne geçmektedir. 

## tar Arşivi Kurulum Adımları

* İndirilen dosya untar yapılmalıdır. `sudo tar xzvf "file-name"`. Eğer komut ile yapılmayacaksa sağ tık ile buraya çıkar denilebilir.

* İndirilen dizine terminalde geçiş yapıldıktan sonra `./configure` yazılır ve işlemin bitmesi beklenir. (Bu komutta hata alıyorsanız muhtemelen C Compiler kurulu değildir. Kurmak için: "sudo apt install build-essential" ardından "sudo apt-get install manpages-dev". Kurulumlar tamamlandıktan sonra işlemlere devam edebilirsiniz.)

* `make` komutu çalıştırılır.

* `sudo make install` çalıştırılır.

* Kurulum adımları tamamlandıktan sonra uygulamanın version kontrolü gerçekleştirilir. 

## Medium Yazılarım

* [Basit Terminal İşlemleri #1](https://medium.com/software-development-turkey/basit-terminal-i%CC%87%C5%9Flemleri-1-b959a88074c9 "Basit Terminal İşlemleri")

* [Linux Dosya Sistemi Hiyerarşisi](https://medium.com/@akiffeyzioglu/linux-dosya-sistemi-hiyera%C5%9Fisi-115bd9bb607d "Linux Dosya Sistemi Hiyerarşisi")

## Faydalı Siteler

* [Man7](https://man7.org/ "Man7") 

* [Linux Command](https://linuxcommand.org/index.php "Linux Command")

* [Explain Shell](https://explainshell.com/ "Explain Shell")

* [Linux Teknik Bilgi Arşivleri](https://www.linuxteknik.com/ "Linux Teknik Bilgi Arşivleri")

* [nixCraft](https://www.cyberciti.biz "nixCraft")

* [OpenServer Docs](https://osr507doc.xinuos.com/en/Navpages/index.html "OpenServer Docs")

* [Linux](https://linux.com "Linux")

* [Linux Command Library](https://linuxcommandlibrary.com/ "Linux Command Library")

* [Linux Dersleri](https://linux-dersleri.github.io/ "Linux Dersleri") 

* [Linuxize](https://linuxize.com/ "Linuxize")

* [Tecmint](https://tecmint.com)

* [How To Geek](https://www.howtogeek.com/ "How To Geek")

* [OS Technix](https://ostechnix.com/ "OS TechNix")

* [The Geek Stuff](https://www.thegeekstuff.com/ "The Geek Stuff")

* [Computer Networking Notes](https://www.computernetworkingnotes.com/ "Computer Networking Notes")

* [Computer Hope](https://www.computerhope.com/ "Computer Hope")

* [Linode Docs](https://www.linode.com/docs "Linode Docs")

* [msHOWTO](https://www.mshowto.org/ "msHOWTO")

* [Linux Journey](https://linuxjourney.com/ "Linux Journey")

* [OverTheWire](https://overthewire.org/wargames/bandit/bandit0.html "OverTheWire")

* [Linux Survival](https://linuxsurvival.com/ "Linux Survival")

* [Açık Kaynak Fikirler](https://acikkaynakfikirler.com/egitimler/ "Açık Kaynak Fikirler")

* [Linux Topic](https://www.linuxtopic.com/ "Linux Topic")

* [Linux Hint](https://linuxhint.com/ "Linux Hint")

* [2 Day Geek](https://2daygeek.com/ "2 Day Geek")

* [The Geek Diary](https://www.thegeekdiary.com/ "The Geek Diary")

# Komutlar

## Dizin ve Dosya İşlemleri

`ls -la:` Çalıştırılan dizinde bulunan tüm gizli ve normal dizinleri kullanıcı grupları ve izinleri birlikte ekrana yazdırır.

`touch file-name:` Dosya oluşturmak için kullanılır. 

`cd directiroy-name:` Dizin değiştirmek için kullanılır. 

`mkdir directory-name:` Klasör oluşturmak için kulllanılır. 

`dd:` Dosyaları dönüştürmek ve görüntülemek için kullanılır.

`sudo rm -rf file:` Herhangi bir dosyayı silmek için kullanılır.

`cat filename:` İsmi verilen dosyanın içeriğini yazdırır. 

`cat filename | wc -l:` İsmi verilen dosyanın içindeki satır sayısını verir. 

`cat filename | wc -c`: İsmi verilen dosyanın içindeki karakter sayısını verir. 

`cat filename | wc -w`: İsmi verilen dosyanın içindeki kelime sayısını verir. 

`head -n 10 filename:` İsmi verilen dosyanın ilk 10 satırını görüntüler. 

`head -c 10 filename:` İsmi verilen dosyanın başından 10 byte okur. 

`tail -n 10 filename:` İsmi verilen dosyanın son 10 satırını görüntüler. 

`tail -c 10 filename:` İsmi verilen dosyanın sonundan 10 byte okur.

## Disk ve Bellek İşlemleri

`df -h *:` Disk ve bölümlerini gösterir. Bu şekilde de kullanılır. "df -h". 

`free -mh:` Sistemde bulunan belleğin kullanım oranını görüntüler. 

`lsblk:` Sistemdeki diskleri listeler. 

## Paket Yönetimi İşlemleri 

`apt install -f:` Kurulacak olan paketin bağımlılık paketlerini kurar.

`sudo dpkg -i example.deb:` Pardus debian tabanlı olduğu için debian uzantılı kurulum dosyaları bu komut ile kurulur.

`sudo apt-get autoremove:` Uygulamalar kaldırıldıktan sonra sistemde yapılandırma dosyaları kalmış olabilir. Bu komut ile kullanılmayan dosyalar kaldırılır.

`sudo apt-get remove program_name:` Uygulama kaldırmak için kullanılır. 

`apt list:` Yüklü paketleri listeler. Kernel hariç. 

`sudo apt-get update/upgrade:` Güncelleme yapmak için kullanılır. 

`sudo nano/etc/apt/source.list:` "sudo apt-get update" komutunda güncellenecek paket listesini verir.

## Bilgi Alma İşlemleri

`htop:` İşlemci kullanım oranlarını, ram kullanımı, arka planda çalışan servisleri ve tükettikleri kaynakları yüzdelik dilimler ile görmenizi sağlar. Komutu yazınca hata alıyorsanız paket kurulu değildir. "sudo apt install htop" ile paketi kurmanız gereklidir.

`cat /sys/class/thermal/thermal_zone0/temp:` İşlemcinin anlık ısı değerlerini verir. 

`ps:` Sistemde çalışan işlemleri listeler.

`man "command-name":` Herhangi bir komutun nasıl kullandıldığını direkt terminal üzerinden bu komut ile bakabiliyoruz. 

`neofetch:` İşletim sistemi bilgilerini verir.

`httpstat:` Sitenin performans durumunu görüntüler. 

`printenv:` Ortam değişkenlerini gösterir.

`lsb_release -a:` Kullanılan işletim sistemi sürümünü verir.

`echo $TERM:` "TERM" ortam değişkenini gösterir.

`echo deneme="test":` Ortam değişkeni oluşturur.

`lshw:` Donanımları listeler. 

`echo $?:` Son terminal oturumunda en son çalıştırılan komutun sonucunu döndürür. Çıktı "0" ise işlem başarılı demektir.

`cat /proc/cpuinfo:` İşlemcinin tüm bilgilerini yazdır  ır. 

`blkid:` Hangi UUID(Universally Unique Identifier) değerinin hangi disk bölümüne ait olduğunu gösterir.  

## Servis İşlemleri

`sudo service service_name start:` Herhangi bir servisi başlatmak için kullanılır. 

`sudo service service_name stop:` Herhangi bir servisi durdurmak için kullanılır.

`sudo service service_name status:` Herhangi bir servisin durumunu görmek için kullanılır.

`sudo mysql -u root -p:` MySQL'e geçiş yapar.

## Kullanıcı İşlemleri

`sudo su:` Root kullanıcısına geçiş yapar. 

`!100:` history ile ulaştılan komut geçmişinde 100. sırada bulunan komutu tekrar çalıştırır. Uzun ve sürekli tekrar edilen komutlar için kullanılabilir. 

`history:` Terminal geçmişini verir. 

`history -c:` Tüm terminal komut geçmişini siler.

[`cat /dev/null > ~/.bash_history && history -c && exit:`](https://belge.pardus.org.tr/pages/viewpage.action?pageId=10028408 "Uçbirim Geçmişini Silmek") "history -c" komutunu kullandığınız zaman terminal geçmişini siler fakat terminali kapatıp açtığınızda geçmiş geri gelir. Bu komut ile tüm geçmiş silinir. 

`passwd:` Giriş yapılan kullanıcın root parolasını değiştirir. 