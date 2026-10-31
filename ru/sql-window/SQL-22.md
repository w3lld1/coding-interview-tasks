# Три первых места по выручке

**Сложность:** сложная · **Язык:** SQL (SQLite) · **Темы:** [SQL: оконные функции](../sql-window/), [SQL: группировка](../sql-aggregate/), [SQL: JOIN](../sql-join/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-22?utm_source=github&utm_medium=tasks-repo)**

Посчитайте выручку каждого объекта: `slots × guestcost` для гостя (`memid = 0`), иначе `slots × membercost`. Присвойте объектам ранг `RANK` по убыванию выручки. Выведите столбцы `name` и `rank` для объектов с рангом 1, 2 или 3 (при равенстве выручки их может быть больше трёх). Отсортируйте по `rank`, затем по `name`.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — Find the top three revenue generating facilities](https://pgexercises.com/questions/aggregates/facrev3.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
