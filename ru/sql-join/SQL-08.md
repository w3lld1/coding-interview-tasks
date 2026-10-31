# Расписание теннисных кортов

**Сложность:** лёгкая · **Язык:** SQL (SQLite) · **Темы:** [SQL: JOIN](../sql-join/), [Даты и время](../dates/), [SQL: выборка и фильтры](../sql-filter/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-08?utm_source=github&utm_medium=tasks-repo)**

Выведите бронирования за 21 сентября 2012 года для объектов с названиями ровно `Tennis Court 1` и `Tennis Court 2` (объект `Table Tennis` не подходит). Столбцы: `start` (время начала `starttime`) и `name` (название объекта). Отсортируйте строки по времени начала.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — Work out the start times of bookings for tennis courts](https://pgexercises.com/questions/joins/simplejoin2.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
