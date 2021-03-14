# ESP32_monitor
![Schematic_ESP32_switcher_2021-03-14](https://user-images.githubusercontent.com/22659037/111063221-f81aa000-84df-11eb-97a7-e8cc6294aa0e.png)
# COMMAND LIST
- SET_SSID,xxx\r\n  || xxx is your name ssid max 20 char
- SET_PASS,xxx\r\n  || xxx is your password ssid max 20 char
- SET_TPORT,xxx\r\n || xxx is target-port can be 0 - 65534
- SET_TIP,xxx\r\n   || xxx is target-IP such 192.168.1.1
- TERMINAL,xxx\r\n  || xxx is string as you want to render to display terminal max cahr is 250
- CON_TCP,\r\n      || create socket and connect to ip/port target with tcp protocol  
- CON_UDP,\r\n      || create socket and connect to ip/port target with udp protocol 
- SEND_TCP,xxx\r\n  || xxx is string data that is sent via tcp protocol data max is 250 char
- SEND_UDP,xxx\r\n  || xxx is string data that is sent via udp protocol data max is 20 char
![test_com](https://user-images.githubusercontent.com/22659037/111063587-2bf6c500-84e2-11eb-8241-ab2ff1e4c739.png)
![test_com](https://user-images.githubusercontent.com/22659037/111063682-aa536700-84e2-11eb-9385-94c59d88ca76.png)
