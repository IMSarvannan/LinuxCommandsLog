#LINUX COMMNAND TO CONNECT TO WIFI FROM TERMINAL
```
ims@ims-System-Product-Name:~$ nmcli device list
Error: argument 'list' not understood. Try passing --help instead.
ims@ims-System-Product-Name:~$ nmcli device wifi list
IN-USE  BSSID              SSID              MODE   CHAN  RATE        SIGNAL  BARS  SECURITY  
        06:D4:DD:19:1F:F1  Infinix           Infra  1     117 Mbit/s  94      ▂▄▆█  WPA2      
        14:A7:2B:0D:DF:48  IMS HOME          Infra  8     270 Mbit/s  79      ▂▄▆_  WPA1 WPA2 
        60:E3:27:C6:5D:14  IMS HOME          Infra  8     270 Mbit/s  70      ▂▄▆_  WPA1 WPA2 
        76:29:AF:A0:23:EE  DIRECT-NA-BRAVIA  Infra  11    65 Mbit/s   67      ▂▄▆_  WPA2      
ims@ims-System-Product-Name:~$ ^C
ims@ims-System-Product-Name:~$ nmcli device wifi Infinix password *********
Error: argument 'Infinix' not understood. Try passing --help instead.
ims@ims-System-Product-Name:~$ nmcli device wifi connect Infinix password ims733412h
Device 'wlx90f652057095' successfully activated with '939d8e61-24ab-4478-b1df-d5a9be08bd21'.

```
