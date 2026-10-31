# Объекты с выручкой ниже порога

**Сложность:** средняя · **Язык:** SQL (SQLite) · **Темы:** [SQL: группировка](../sql-aggregate/), [SQL: JOIN](../sql-join/), [SQL: выборка и фильтры](../sql-filter/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-18?utm_source=github&utm_medium=tasks-repo)**

Посчитайте выручку каждого объекта так же, как в задаче о выручке: `slots × guestcost` для гостя (`memid = 0`), иначе `slots × membercost`. Оставьте объекты с выручкой меньше 50. Выведите столбцы `name` и `revenue`, отсортировав по выручке по возрастанию.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — Find facilities with a total revenue less than 1000](https://pgexercises.com/questions/aggregates/facrev2.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
