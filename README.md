# Принципы создания Базы данных
Перед тем, как делать базу данных надо выделить следующе:

Понятие | Описание
------  | -----
Цель приложения | Всегда надо помнить - что и зачем мы делаем. Если мы описываем пользователя, то должны расписать его параметры (паспорт, дату рождения, связи с родственниками и т.д.). Если пользователь нам нужен только для авторизации, то достаточно определить login и password...
Основные сущности | (Entity) составляют предметную область.
Cвязи между сущностями | Один ко многим, Многие ко многим, один к одному и т.д.
Ограничения | (Constraint) Ограничения - это то, что делает набор таблиц базой данных. Кроме самих констрейнтов к ограничения относятся первичный и вторичный ключ, ограничения типа поля и т.д. 

## Таблица
Таблицы 

### Название таблицы
Имя таблицы длжно определять ее суть (*Как вы судно назовете, так оно и поплывет*). Кроме этого, название не должно быть длинным.

В люксе принято добавлять в начало таблицы префикс. Префикс определяет 

### Первичный ключь ID
Каждая таблица должна иметь primary key (PK, ID).

### Время жизни записи
2. 
