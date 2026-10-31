# Выручка каждого объекта

**Сложность:** средняя · **Язык:** SQL (SQLite) · **Темы:** [SQL: группировка](../sql-aggregate/), [SQL: JOIN](../sql-join/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-17?utm_source=github&utm_medium=tasks-repo)**

Посчитайте выручку каждого объекта по всем бронированиям. Стоимость бронирования — `slots × guestcost` для гостя (`memid = 0`) и `slots × membercost` для остальных. Выведите столбцы `name` (название объекта) и `revenue` (выручка), отсортировав по выручке по возрастанию.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — Find the total revenue of each facility](https://pgexercises.com/questions/aggregates/facrev.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
