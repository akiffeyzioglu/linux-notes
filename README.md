## Linux Notlarım

Bu repository Linux kullanmayı öğrenirken aldığım notları içermektedir. İşletim sistemi Pardus 19.03 ve masaüstü GNOME kullanılmaktadır.

* | işareti AltGr + - (orta çizgi) ile yapılır. 
## Medium Yazılarım

* [Basit Terminal İşlemleri #1](https://medium.com/software-development-turkey/basit-terminal-i%CC%87%C5%9Flemleri-1-b959a88074c9 "Basit Terminal İşlemleri")

#
`lsb_release -a:` Kullanılan işletim sistemi sürümünü verir.

`lsblk:` Sistemdeki diskleri listeler. 

`sudo mysql -u root -p:` MySQL'e geçiş yapar.

`sudo dpkg -i example.deb:` Pardus debian tabanlı olduğu için debian uzantılı kurulum dosyaları bu komut ile kurulur.

`sudo apt-get autoremove:` Uygulamalar kaldırıldıktan sonra sistemde yapılandırma dosyaları kalmış olabilir. Bu komut ile kullanılmayan dosyalar kaldırılır.

`sudo apt-get remove program_name:` Uygulama kaldırmak için kullanılır. 

`sudo service service_name start:` Herhangi bir servisi başlatmak için kullanılır. 

`sudo service service_name stop:` Herhangi bir servisi durdurmak için kullanılır.

`sudo service service_name status:` Herhangi bir servisin durumunu görmek içn kullanılır.

`sudo nano/etc/apt/source.list:` "sudo apt-get update" komutunda güncellenecek paket listesi verir.

`history:` Terminal geçmişini verir. 

`history -c:` Tüm terminal komut geçmişini siler.

[`cat /dev/null > ~/.bash_history && history -c && exit:`](https://belge.pardus.org.tr/pages/viewpage.action?pageId=10028408 "Uçbirim Geçmişini Silmek") "history -c" komutunu kullandığınız zaman terminal geçmişini siler fakat terminali kapatıp açtığınızda geçmiş geri gelir. Bu komut ile tüm geçmiş silinir. 

`sudo apt-get update/upgrade:` Güncelleme yapmak için kullanılır. 

`sudo rm -rf file:` Herhangi bir dosyayı silmek için kullanılır.

`touch file-name:` Dosya oluşturmak için kullanılır. 

`cd directiroy-name:` Dizin değiştirmek için kullanılır. 

`mkdir directory-name:` Klasör oluşturmak için kulllanılır. 

`neofetch:` İşletim sistemi bilgilerini verir.

`apt-list:` Yüklü paketleri listeler. Kernel hariç. 

`free -mh:` Sistemde bulunan belleğin kullanım oranını görüntüler. 

`printenv:` Ortam değişkenlerini gösterir.

`echo $TERM:` "TERM" ortam değişkenini gösterir.

`echo deneme="test":` Ortam değişkeni oluşturur.

`df -h *:` Disk ve bölümlerini gösterir. Bu şekilde de kullanılır. "df -h". 

`dd:` Dosyaları dönüştürmek ve görüntülemek için kullanılır.

`httpstat:` Sitenin performans durmunu görüntüler. 
