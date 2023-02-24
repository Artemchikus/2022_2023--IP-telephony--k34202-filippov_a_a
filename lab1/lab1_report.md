University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Network programming](https://itmo-ict-faculty.github.io/ip-telephony)  
Year: 2022/2023  
Group: K34202  
Author: Filippov Artem Alekseevich  
Lab: Lab1  
Date of create: 24.02.2023  
Date of finished: ...  

Цель:  Изучить рабочую среду Cisco Packet Tracer, ознакомить- ся с интерфейсами основных устройств, типами кабелей, научиться собирать топологию. Изучить построение сети IP-телефонии с помощью маршрутизатора, коммутатора и IP телефонов Cisco 7960 в среде Packet tracer.  

Ход работы:  

1.	Собрана схема соединения, указанная на рисунке 1.  
![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab1/images/00.png)  
2.	Настроены коммутаторы и компьютеры для полноценной работы сети.    
![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab1/images/0.png)  
![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab1/images/01.png)  
3. Посредством пинга протестирована возможность любого компьютеря одной сети передачи пакетов любому компьютеру другой сети.  
![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab1/images/02.png)  
![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab1/images/03.png)  
4.	Собрана схема соединения, указанная на рисунке 2.  
![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab1/images/10.png)  
5.	Осуществлено подключение IP телефонов к сети.  
![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab1/images/12.png)  
6.	Настроен интерфейс fa0/0 на маршрутизаторе Cisco 2811 (CMERouter).  
![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab1/images/1.png)  
7.	Настроен DHCP сервер для передачи голоса на маршрутизаторе Cisco 2811.  
![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab1/images/2.png)  
8. Настроить услуги телефонии Cisco CallManager Express на маршрутизаторе 2811.  
![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab1/images/3.png)  
9. Созданы VLAN порты на коммутаторе для взаимодействия коммутатора с маршрутизатором.  
![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab1/images/4.png) 
10. Настроены номера для IP телефонов.  
![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab1/images/5.png) 
![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab1/images/7.png)  
11. Осуществлен тестовый звонок с одного IP телефона на другой.  
![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab1/images/6.png)  

Вывод:  
В ходе выполнения лабораторной работы были реализованы две схемы, а именно схема с несколькими коммутаторами, но без маршрутизаторов и схема реализации VOIP с маршрутизатором, при помощью инструментов Cisco Packet Tracer.