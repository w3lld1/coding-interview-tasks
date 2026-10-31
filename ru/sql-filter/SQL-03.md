# Категории стоимости обслуживания

**Сложность:** лёгкая · **Язык:** SQL (SQLite) · **Темы:** [SQL: выборка и фильтры](../sql-filter/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-03?utm_source=github&utm_medium=tasks-repo)**

Для каждого объекта из таблицы `facilities` выведите три столбца: `name`, `monthlymaintenance` и `cost`. В `cost` запишите `'expensive'`, если `monthlymaintenance` больше 100, иначе `'cheap'`. Порядок строк не важен.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — Classify results into buckets](https://pgexercises.com/questions/basic/classify.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
