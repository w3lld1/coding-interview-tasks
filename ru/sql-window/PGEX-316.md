# Нумерация участников по дате вступления

**Сложность:** лёгкая · **Язык:** SQL (SQLite) · **Темы:** [SQL: оконные функции](../sql-window/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/PGEX-316?utm_source=github&utm_medium=tasks-repo)**

Пронумеруйте участников клуба (включая гостя) по порядку вступления: первый вступивший получает 1. Выведите столбцы `row_number`, `firstname`, `surname`, отсортировав по `joindate`.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises, aggregates/nummembers.html](https://pgexercises.com/questions/aggregates/nummembers.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
