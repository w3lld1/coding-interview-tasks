# Имена в формате «Фамилия, Имя»

**Сложность:** лёгкая · **Язык:** SQL (SQLite) · **Темы:** [SQL: выборка и фильтры](../sql-filter/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/PGEX-501?utm_source=github&utm_medium=tasks-repo)**

Выведите имена всех участников клуба в одном столбце `name` в формате `Фамилия, Имя` (запятая и пробел между частями). Порядок строк не важен.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises, string/concat.html](https://pgexercises.com/questions/string/concat.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
