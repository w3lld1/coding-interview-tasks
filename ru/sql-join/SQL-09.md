# Участники, пригласившие других

**Сложность:** средняя · **Язык:** SQL (SQLite) · **Темы:** [SQL: JOIN](../sql-join/), [SQL: выборка и фильтры](../sql-filter/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-09?utm_source=github&utm_medium=tasks-repo)**

Найдите участников, которые пригласили хотя бы одного другого участника: на их `memid` ссылается поле `recommendedby` в таблице `members`. Выведите столбцы `firstname` и `surname`, каждого человека один раз. Отсортируйте по фамилии, затем по имени.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — Produce a list of all members who have recommended another member](https://pgexercises.com/questions/joins/self.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
