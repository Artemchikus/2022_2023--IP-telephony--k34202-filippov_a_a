University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Network programming](https://itmo-ict-faculty.github.io/ip-telephony)  
Year: 2022/2023  
Group: K34202  
Author: Filippov Artem Alekseevich  
Lab: Lab4  
Date of create: 28.03.2023  
Date of finished: ...

Цель: Изучить построение сети IP-телефонии между удаленными филиалами с помощью маршрутизаторов Cisco 2811 и коммутаторов Cisco 2950Т.

Ход работы:

1. Собрана схема соединения, указанная на рисунке 1.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab4/images/0.png)
2. Настроен интерфейс fa0/0 на маршрутизаторах Cisco 2811.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab4/images/2.png)
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab4/images/3.png)
3. Настроен интерфейс s0/3/0 на маршрутизаторах Cisco 2811.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab4/images/1.png)
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab4/images/4.png)
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab4/images/5.png)
4. Настроен маршрутизатор Cisco 2811, коммутатор Cisco 3950Т, IP-телефоны аналогично лабораторной работе №2.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab4/images/6.png)  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab4/images/7.png)
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab4/images/8.png)
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab4/images/10.png)
5. Настроены DHCP сервера на маршрутизаторах для передачи голоса и данных между ними.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab4/images/11.png)
6. Настроена динамическая маршрутизация RIP между маршрутизаторами для передачи информации друг другу.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab4/images/13.png)
7. Настроены услуги телефонии Cisco CallManager Express на маршрутизаторе 2811.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab4/images/14.png)
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab4/images/15.png)
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab4/images/16.png)
8. Проверены вызовы между удаленными IP-телефонами и пинги между удаленными хостами.  
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab4/images/17.png)
   ![Image text](https://github.com/Artemchikus/2022_2023--IP-telephony--k34202-filippov_a_a/raw/main/lab4/images/18.png)

Вывод:  
В ходе выполнения лабораторной работы было изучено построение сети IP-телефонии между удаленными филиалами с помощью маршрутизаторов Cisco 2811 и коммутаторов Cisco 2950Т, при помощью инструментов Cisco Packet Tracer.
