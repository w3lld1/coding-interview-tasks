# Цепочка приглашений

**Сложность:** сложная · **Язык:** SQL (SQLite) · **Темы:** [SQL: оконные функции](../sql-window/), [SQL: JOIN](../sql-join/), [Деревья и графы](../trees-graphs/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-30?utm_source=github&utm_medium=tasks-repo)**

Найдите всех участников, которых прямо или через других пригласил участник с `memid = 1`: его приглашённых, затем приглашённых ими и так далее. Выведите столбцы `memid`, `firstname`, `surname`, отсортировав по `memid`. Самого участника 1 в результат не включайте.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — Find the downward recommendation chain for member ID 1](https://pgexercises.com/questions/recursive/getdownward.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
