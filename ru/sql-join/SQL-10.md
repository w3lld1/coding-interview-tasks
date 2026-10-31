# Участники и пригласившие их люди

**Сложность:** средняя · **Язык:** SQL (SQLite) · **Темы:** [SQL: JOIN](../sql-join/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-10?utm_source=github&utm_medium=tasks-repo)**

Для каждого участника выведите его имя и фамилию, а также имя и фамилию участника, который его пригласил (`recommendedby`). Столбцы: `memfname`, `memsname` (имя и фамилия участника), `recfname`, `recsname` (имя и фамилия пригласившего). Участников без пригласившего тоже выведите, с `NULL` в последних двух столбцах. Отсортируйте по фамилии, затем по имени участника.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — Produce a list of all members, along with their recommender](https://pgexercises.com/questions/joins/self2.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
