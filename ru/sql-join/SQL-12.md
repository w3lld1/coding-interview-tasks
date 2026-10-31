# Дорогие бронирования с разными тарифами

**Сложность:** средняя · **Язык:** SQL (SQLite) · **Темы:** [SQL: JOIN](../sql-join/), [SQL: выборка и фильтры](../sql-filter/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-12?utm_source=github&utm_medium=tasks-repo)**

Найдите бронирования за 14 сентября 2012 года, стоимость которых больше 30. Стоимость бронирования — `slots`, умноженное на `guestcost`, если `memid = 0` (гость), иначе на `membercost`. Выведите столбцы `member` (имя и фамилия через пробел), `facility` (название объекта) и `cost` (стоимость). Отсортируйте по стоимости по убыванию. Не используйте подзапросы.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — Produce a list of costly bookings](https://pgexercises.com/questions/joins/threejoin2.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
