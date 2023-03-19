University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Network programming](https://itmo-ict-faculty.github.io/ip-telephony)  
Year: 2022/2023  
Group: K34202  
Author: Filippov Artem Alekseevich  
Lab: Lab2  
Date of create: 19.03.2023  
Date of finished: ...

Цель: Изучить построение сети IP-телефонии с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960.

Ход работы:

1. Собрана схема соединения, указанная на рисунке 1.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/0.png)  
2. В конфигурационном режиме изменено название маршрутизатора на CMERouter.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/1.png)  
3. Отключен синтаксис ввода слов от DNS серверов.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/2.png)  
4. Заданы пароли для защиты маршрутизатора как в удаленном режиме, так и в режиме консоли.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/3.png)  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/3.1.png)  
5. Настроен интерфейс fa0/0 на маршрутизаторе Cisco 2811 (CMERouter).  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/4.png)  
6. Настроен DHCP сервер для передачи голоса и данных на маршрутизаторе Cisco 2811.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/5.png)  
7. Настроить услуги телефонии Cisco CallManager Express на маршрутизаторе 2811.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/6.png)  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/7.png)  
8. Созданы VLAN порты на коммутаторе Cisco Catalyst 3560 для взаимодействия коммутатора с маршрутизатором и подключены IP телефоны.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/8.png)  
9. Осуществленна настройки IP-телефоноы и их соединение с коммутатором Cisco Catalyst 3560. После чего осуществленны тестовые звонки.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/9.png)  
10. Собрана схема соединения, указанная на рисунке 2.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/10.1.png)  
11. Созданы VLAN порты на коммутаторе для взаимодействия коммутатора с маршрутизатором и подключены IP телефоны.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/10.png) 
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/12.png)   
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/13.png)  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/14.png)  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/15.png)  
12. Задан маршрут по умолчанию командой ip default-gateway.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/11.1.png)  
13. Настроен порт как канал типа trunk.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/11.png)  
14. Настроен DHCP сервера для передачи голоса и данных на маршрутизаторе Cisco 2811.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/16.png)  
15. Настроены услуги телефонии Cisco CallManager Express на маршрутизаторе.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/18.png)  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/19.png)  
16. Осуществленна настройка IP-телефонов и конечных устройств, а также их соединение с коммутатором. После чего осуществленна проверка звонков между телефонами и пингов между кончеыми узлами.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/17.png)  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/20.png)  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab2/images/21.png)

Вывод:  
В ходе выполнения лабораторной работы было изучено построение сети IP-телефонии с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960, при помощью инструментов Cisco Packet Tracer.
