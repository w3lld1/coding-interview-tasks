# Кто пользовался теннисными кортами

**Сложность:** средняя · **Язык:** SQL (SQLite) · **Темы:** [SQL: JOIN](../sql-join/), [SQL: выборка и фильтры](../sql-filter/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-11?utm_source=github&utm_medium=tasks-repo)**

Выведите, какие участники бронировали теннисные корты `Tennis Court 1` и `Tennis Court 2` (объект `Table Tennis` не учитывается). Столбцы: `member` — имя и фамилия через пробел (`firstname || ' ' || surname`), `facility` — название корта. Каждая пара участник–корт должна встретиться один раз. Гостевая запись участвует наравне с остальными. Отсортируйте по `member`, затем по `facility`.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — Produce a list of all members who have used a tennis court](https://pgexercises.com/questions/joins/threejoin.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
