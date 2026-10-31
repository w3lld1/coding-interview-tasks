# Скользящая средняя дневной выручки

**Сложность:** сложная · **Язык:** SQL (SQLite) · **Темы:** [SQL: оконные функции](../sql-window/), [Даты и время](../dates/), [SQL: группировка](../sql-aggregate/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-24?utm_source=github&utm_medium=tasks-repo)**

Для каждого дня августа 2012 года посчитайте среднюю дневную выручку за 15 дней: этот день и 14 предыдущих календарных дней. Выручка бронирования — `slots × guestcost` для гостя (`memid = 0`), иначе `slots × membercost`. День без бронирований входит в среднее с выручкой 0. Для первых дней августа окно захватывает дни июля. Выведите столбцы `date` (текст `YYYY-MM-DD`) и `revenue` (среднее, без округления), отсортировав по дате.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — Calculate a rolling average of total revenue](https://pgexercises.com/questions/aggregates/rollingavg.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
