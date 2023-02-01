# Python_net_scanner
Bu kod, kullanıcının belirttiği IP adresine ait ağdaki cihazları tarar. 
Kullanıcı, "-i" veya "--ipaddress" argümanı ile belirttiği IP adresini girebilir. 
Optparse kütüphanesi, argümanların doğru şekilde kullanılıp kullanılmadığını kontrol eder ve kullanıcıya doğru kullanımı nasıl yapabileceği hakkında bilgi verir.

Scapy kütüphanesi, ARP isteği göndererek ağdaki cihazları tarama işlemini gerçekleştirir. 
Tarama sonrası, cevaplanan veya cevaplanmayan paketleri bir liste olarak döndürür ve sonuçları özet şekilde görüntüler.
