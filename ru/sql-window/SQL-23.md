# Три группы объектов по выручке

**Сложность:** сложная · **Язык:** SQL (SQLite) · **Темы:** [SQL: оконные функции](../sql-window/), [SQL: группировка](../sql-aggregate/), [SQL: JOIN](../sql-join/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-23?utm_source=github&utm_medium=tasks-repo)**

Посчитайте выручку каждого объекта: `slots × guestcost` для гостя (`memid = 0`), иначе `slots × membercost`. Разделите объекты на три почти равные по числу строк группы функцией `NTILE(3)` по убыванию выручки. Группа 1 — `'high'`, группа 2 — `'average'`, группа 3 — `'low'`. Выведите столбцы `name` и `revenue`; в `revenue` запишите метку группы. Сначала идут объекты группы `high`, затем `average`, затем `low` (по номеру группы, а не по алфавиту); внутри группы — по `name`.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — Classify facilities by value](https://pgexercises.com/questions/aggregates/classify.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
