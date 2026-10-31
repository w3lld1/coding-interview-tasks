# Бронирования по месяцам

**Сложность:** лёгкая · **Язык:** SQL (SQLite) · **Темы:** [SQL: группировка](../sql-aggregate/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/PGEX-409?utm_source=github&utm_medium=tasks-repo)**

Посчитайте число бронирований в каждом месяце. Месяц выведите как дату его первого дня (`2012-07-01`) в столбце `month`, число бронирований — в столбце `count`. Отсортируйте по `month`.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises, date/bookingspermonth.html](https://pgexercises.com/questions/date/bookingspermonth.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
