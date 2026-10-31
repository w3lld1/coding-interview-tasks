# Самый загруженный объект

**Сложность:** лёгкая · **Язык:** SQL (SQLite) · **Темы:** [SQL: группировка](../sql-aggregate/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/PGEX-311?utm_source=github&utm_medium=tasks-repo)**

Найдите объект, на котором забронировано больше всего слотов за всё время. Выведите столбцы `facid` и `total_slots` (сумма `slots`) — одну строку.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises, aggregates/fachours2.html](https://pgexercises.com/questions/aggregates/fachours2.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
