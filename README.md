# Appbee-statik-ip-atama
Appbee Yetenek Merkezi bünyesinde tamamlanan, Cisco Router üzerinde GigabitEthernet0/0 arayüzüne statik IP atama ve portu aktifleştirme görevidir.


##GÖREV: Router'ın GigabitEthernet0/0 arayüzüne 192.168.10.1 IP adresini ve 255.255.255.0 subnet maskını ata, ardından portu aktif et (no shutdown). 
##Çözüm Konfigürasyonu
```text
enable
configure terminal
interface GigabitEthernet0/0
ip address 192.168.10.1 255.255.255.0
no shutdown
