# Xiaomi miIO

Модуль предназначен для интеграции **MajorDoMo** с Wi-Fi устройствами из экосистемы **Xiaomi Mihome**, взаимодействующих по протоколу **miIO**.

**miIO** - проприетарный сетевой протокол Xiaomi с шифрованием, по которому взаимодействуют wifi-устройства из экосистемы Xiaomi и приложение Mihome на смартфоне. В качестве транспорта используется UDP и порт 54321. Содержимое пакетов шифруется. Ключи шифрования формируются на основе уникальных токенов. Для контроля корректности принимаемых пакетов используется контрольная сумма на основе алгоритма MD5.

Использование этого протокола позволяет управлять теми устройствами, которые не имеют открытого API (режима разработчика). Например, пылесосы, лампы, светильники, увлажнители и очистители воздуха, розетки и многие другие. Также позволяет расширить имеющиеся возможности открытого API у xiaomi-шлюза, в частности переводить его в режим сопряжения, привязывать и отвязывать zigbee-устройства, управлять радио и др.

В основе модуля лежит библиотека **[php-miio](https://github.com/skysilver-lab/php-miio)**.

Обсуждение модуля на **[Форуме](https://mjdm.ru/forum/viewtopic.php?f=5&t=4863)**.

Модуль в **[Connect](https://connect.smartliving.ru/tasks/51.html)**.

![miio](https://kb.mjdm.ru/wp-content/uploads/2018/07/module_miio.gif)

### Поддерживаемые устройства

1. Шлюз ZigBee ***Mi Smart Home Gateway 2***
2. Шлюз ZigBee ***Aqara AC Companion Gateway***
3. Розетка ***Mi Smart Socket Plug 2***
4. Розетка ***Mi Smart Socket Plug with USB***
5. Розетка ***Mi Smart Socket Plug with 2 USB***
6. Пылесос ***Mi Vacuum Cleaner***
7. Пылесос ***Mi Roborock S50/S51***
8. Пылесос ***Mi Robot Vacuum-Mop P***
9. Пылесос ***Xiaomi Robot Vacuum S10+***
10. Настольная лампа ***Philips EyeCare Smart Desk Lamp 2***
11. Лампочка белая Е27 ***Philips Light Bulb***
12. Лампочка белая Е27 ***Yeelight White Bulb***
13. Лампочка цветная Е27 ***Yeelight Color Bulb***
14. Лампочки ***Philips Rui Chi Candle Light Bulb***
15. Настольная лампа ***Mi LED Desk Lamp***
16. Потолочный светильник ***Yeelight Ceiling Light***
17. Потолочный светильник ***Yeelight Square Ceiling Light***
18. Потолочный светильник ***Yeelight Jiaoyue 650 Ceiling Light***
19. Потолочный светильник ***Yeelight Bright Moon LED Intelligent Ceiling***
20. Потолочный светильник ***Philips EyeCare Smart Ceiling Lamp***
21. Светодиодная лента ***Yeelight LED Lightstrip***
22. Удлинитель (5 розеток) ***Mi (Chingmi) Smart Power Strip 5 Plugs***
23. Удлинитель (6 розеток) ***Mi Smart Power Strip 6 Plugs***
24. Увлажнитель воздуха ***Mi Air Humidifier***
25. Увлажнитель воздуха ***Mi Air Humidifier 2***
26. Увлажнитель воздуха ***Mi Air Humidifier MJJSQ***
27. Очиститель воздуха ***Mi Air Purifier v3***
28. Очиститель воздуха ***Mi Air Purifier 2S***
29. Очиститель воздуха ***Mi Air Purifier 3/3H***
30. Термопот ***Mi Heating Water Dispenser MINI (R1/R2)***
31. Термопот ***Mi Heating Water Dispenser 4A (R3)***
32. IR-контроллер ***Mi IR Remote 360***
33. WiFi-колонка ***Mi Internet Speaker***
34. Ночник ***Yeelight Bedside Lamp***
35. Светильник (спот) ***Philips Zhirui Downlight***
36. Напольный вентилятор ***Mi Smart Fan SA1***
37. Анализатор качества воздуха ***Mi ClearGrass Air Monitor S1***
38. Анализатор качества воздуха ***Mi ClearGrass Air Monitor B1***
39. Ультрафиолетовая лампа ***Mi Five Disinfection Lamp***
40. Трехканальный выключатель ***Mi PTX ThreeKey Switch***
41. Аквариум ***Mi Smart Fish Tank***

### Документация по модулю
* [Общие сведения](https://kb.mjdm.ru/xiaomimiio_help/)
* [Установка, обновление, удаление модуля](https://kb.mjdm.ru/xiaomimiio-ustanovka-obnovlenie/)
* [Интерфейс модуля](https://kb.mjdm.ru/xiaomimiio-gui/)
* [Настройка модуля](https://kb.mjdm.ru/xiaomimiio-settings/)
* [Протокол miIO](https://kb.mjdm.ru/xiaomimiio-protocol/)
* [Токены устройств](https://kb.mjdm.ru/xiaomimiio-tokens/)
* [Управление техникой по ИК-каналу](https://kb.mjdm.ru/xiaomi-miio-ir-control/)
* [Управление роботом-пылесосом](https://kb.mjdm.ru/miio-vacuums-control/)
