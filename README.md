﻿# Домашнее задание к занятию 2 "Кластеризация и балансировка нагрузки" Горегляд Николай

### Задание 1

`Запустите два simple python сервера на своей виртуальной машине на разных портах`

`Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке`

`Настройте балансировку Round-robin на 4 уровне.`

`На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.`

1. `Task_1`
   ![screenshot](https://github.com/nick-mp/HAProxy_hw/blob/main/1_task.png)

  [link_to_script](https://github.com/nick-mp/HAProxy_hw/blob/main/haproxy.cfg)
   
---

### Задание 2

`Запустите три simple python сервера на своей виртуальной машине на разных портах`

`Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4`

`HAproxy должен балансировать только тот http-трафик, который адресован домену example.local`

`На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.`




1. `Task_2`
   ![screenshot](https://github.com/nick-mp/HAProxy_hw/blob/main/2_task.png)

2. `Task_2-1`
   ![screenshot](https://github.com/nick-mp/HAProxy_hw/blob/main/2-1%20task.png)

[link_to_script](https://github.com/nick-mp/HAProxy_hw/blob/main/haproxy_task_2.cfg)
