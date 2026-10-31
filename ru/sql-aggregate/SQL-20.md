# Месячные итоги и общий итог

**Сложность:** сложная · **Язык:** SQL (SQLite) · **Темы:** [SQL: группировка](../sql-aggregate/), [Даты и время](../dates/), [SQL: выборка и фильтры](../sql-filter/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-20?utm_source=github&utm_medium=tasks-repo)**

Посчитайте сумму `slots` за 2012 год по каждому объекту и месяцу. Выведите столбцы `facid`, `month` (номер месяца числом от 1 до 12) и `slots` (сумма). Добавьте строки итогов:

- для каждого объекта — сумма за все месяцы, `month` равен `NULL`;
- общий итог по всем объектам — `facid` и `month` равны `NULL`.

Отсортируйте по `facid`, затем по `month`: итог объекта идёт после его месяцев, а общий итог — последней строкой.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — List the total slots booked per facility per month, part 2](https://pgexercises.com/questions/aggregates/fachoursbymonth3.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
