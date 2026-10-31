# Первое бронирование после заданной даты

**Сложность:** средняя · **Язык:** SQL (SQLite) · **Темы:** [SQL: группировка](../sql-aggregate/), [SQL: JOIN](../sql-join/), [SQL: выборка и фильтры](../sql-filter/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-19?utm_source=github&utm_medium=tasks-repo)**

Для каждого участника, у которого есть бронирования 1 сентября 2012 года или позже, найдите самое раннее из этих бронирований. Выведите столбцы `surname`, `firstname`, `memid` и `starttime` (время этого бронирования), отсортировав по `memid`.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — List each member's first booking after September 1st 2012](https://pgexercises.com/questions/aggregates/nbooking.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
