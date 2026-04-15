# Отладка сети

## Документирование 

Пиши документацию
Указывай в ней все, что важно для понимания твоей сети. Все писать не оч удобно, т.к занимает много усилий

![alt text](image.png)
Что нужно указывать в документации

![alt text](image-1.png)

пример документации топологии сети
![alt text](image-2.png)

ещё один пример, с указанием физического, канального и сетевого уровня сети 

![alt text](image-3.png)

## Базовые показатели производительности

Требуется вычислить основные параметры сети при нормальной средней нагрузке, чтобы затем иметь возможность сравнивать их с текущими значениями и определять различные сбои, задержки, либо что сеть работает в штатном режиме

Данные собираются на критически важных устройствах, сетевом оборудовании

![alt text](image-4.png)

Команды для сбора данных

![alt text](image-5.png)

Показатели можно собирать с помощью snmp, ip sla, зеркалирования порта свитча на анализирующее устройство, сбор логов

## Процедура поиска и устранения неполадок

Проблемы и их решения лучше документировать 

Сбор симптов осуществляется за счет получения сообщений об ошибках, ip sla, snmp

![alt text](image-6.png)

![alt text](image-7.png)

![alt text](image-8.png)

![alt text](image-9.png)

Отладка сети основана на уровнях моделях OSI

![alt text](image-10.png)

![alt text](image-11.png)

![alt text](image-12.png)

![alt text](image-13.png)

![alt text](image-14.png)

![alt text](image-15.png)

![alt text](image-16.png)

## Отладка проблем на разных уровнях OSI

## Физический уровень

![alt text](image-17.png)


## Канальный уровень

![alt text](image-18.png)

## Сетевой уровень

![alt text](image-19.png)

## Транспортный уровень 

![alt text](image-20.png)

![alt text](image-21.png)

## Прикладной уровень

Проверяй работу конкретного протокола

![alt text](image-22.png)

## Пример

Проверь провода, работоспособность устройств
Проверь настройку свитчей s1 s2
Посмотри таблицу маршрутизации, правильную адресацию
Посмотри транспортный уровень (acl)

![alt text](image-23.png)

![alt text](image-24.png)

![alt text](image-25.png)

![alt text](image-26.png)

![alt text](image-27.png)

![alt text](image-28.png)

![alt text](image-29.png)

![alt text](image-30.png)

![alt text](image-31.png)

![alt text](image-33.png)

![alt text](image-32.png)
![alt text](image-34.png)

![alt text](image-35.png)

![alt text](image-36.png)

![alt text](image-37.png)

![alt text](image-38.png)

![alt text](image-39.png)

![alt text](image-40.png)

![alt text](image-41.png)

![alt text](image-42.png)

![alt text](image-43.png)

![alt text](image-44.png)

![alt text](image-45.png)

![alt text](image-46.png)

![alt text](image-47.png)

![alt text](image-48.png)

![alt text](image-49.png)

![alt text](image-50.png)

![alt text](image-51.png)

![alt text](image-52.png)

![alt text](image-53.png)

![alt text](image-54.png)

19/20