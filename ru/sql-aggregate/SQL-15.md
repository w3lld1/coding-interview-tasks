# Загрузка объектов за сентябрь

**Сложность:** лёгкая · **Язык:** SQL (SQLite) · **Темы:** [SQL: группировка](../sql-aggregate/), [Даты и время](../dates/), [SQL: выборка и фильтры](../sql-filter/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-15?utm_source=github&utm_medium=tasks-repo)**

Посчитайте, сколько слотов забронировали на каждом объекте в сентябре 2012 года. Выведите столбцы `facid` и `total_slots` (сумма `slots`) и отсортируйте по `total_slots`.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — List the total slots booked per facility in a given month](https://pgexercises.com/questions/aggregates/fachoursbymonth.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
