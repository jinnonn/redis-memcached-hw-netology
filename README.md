# Домашнее задание к занятию «Кеширование Redis/memcached»

### Задание 1. Кеширование 

Приведите примеры проблем, которые может решить кеширование. 

*Приведите ответ в свободной форме.*

### Решение 1.

- Оптимизация работы сервиса путем кеширования часто запрашиваемых данных, что позволит эти данные получать и использовать быстрее.
- Та же оптимизация но уже, например, при работе с тяжелыми запросами, которые из источника этих данных извлекаются непозволительно долго.
- Ограничение в вычислительных мощностях. Само по себе кеширование тоже требует некоторых ресурсов, однако на дистанции запросы к кешированным данным сэкономят часть ресурсов, нежели эти ресурсы использовались бы для повторного вычисления данных или их извлечение из источника.

В целом все проблемы, которое решает кеширование, сводятся к проблемам с быстродействием сервиса связанных с часто используемыми данными.

---

### Задание 2. Memcached

Установите и запустите memcached.

*Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.*

### Решение 2.

![image](https://github.com/jinnonn/redis-memcached-hw-netology/assets/146999555/73042262-1f27-41c7-8b56-4877cc85c4c0)


---

### Задание 3. Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5. 

*Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.*

### Решение 3

![image](https://github.com/jinnonn/redis-memcached-hw-netology/assets/146999555/35ca8753-2b1a-4006-b4c5-339d7a8de19b)

---

### Задание 4. Запись данных в Redis

Запишите в Redis несколько ключей с любыми именами и значениями. 

*Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.*

### Решение 4.

![image](https://github.com/jinnonn/redis-memcached-hw-netology/assets/146999555/371de027-7733-47e2-8f8f-81735480870d)

![image](https://github.com/jinnonn/redis-memcached-hw-netology/assets/146999555/82d8d4b0-f1a4-49a3-b10a-e7a3d1db6452)

