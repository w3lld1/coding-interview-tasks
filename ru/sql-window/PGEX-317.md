# Наименее загруженные объекты

**Сложность:** средняя · **Язык:** SQL (SQLite) · **Темы:** [SQL: оконные функции](../sql-window/), [SQL: группировка](../sql-aggregate/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/PGEX-317?utm_source=github&utm_medium=tasks-repo)**

Найдите объекты с наименьшей суммой забронированных слотов за всё время. Если наименьшую сумму делят несколько объектов, выведите все. Столбцы: `facid` и `total` (сумма `slots`). Порядок строк не важен.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises, aggregates/fachours4.html](https://pgexercises.com/questions/aggregates/fachours4.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare, вместо наибольшей суммы ищется наименьшая
