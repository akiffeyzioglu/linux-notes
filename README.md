## Linux Notlarım

Bu repository Linux kullanmayı öğrenirken aldığım notları içermektedir. İşletim sistemi Pardus 19.03 ve masaüstü GNOME kullanılmaktadır.

#
`lsb_release -a:` Kullanılan işletim sistemi sürümünü verir.

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

`sudo apt-get update/upgrade:` Güncelleme yapmak için kullanılır. 