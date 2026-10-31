# Последние десять завершений бронирований

**Сложность:** средняя · **Язык:** SQL (SQLite) · **Темы:** [SQL: выборка и фильтры](../sql-filter/), [Даты и время](../dates/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-26?utm_source=github&utm_medium=tasks-repo)**

Время окончания бронирования — `starttime` плюс `slots × 30` минут, в том же текстовом формате `YYYY-MM-DD HH:MM:SS`. Выведите столбцы `starttime` и `endtime` для десяти бронирований с самым поздним окончанием. Отсортируйте по `endtime` по убыванию, а при равенстве — по `starttime` по убыванию.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — Work out the end time of bookings](https://pgexercises.com/questions/date/endtimes.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
