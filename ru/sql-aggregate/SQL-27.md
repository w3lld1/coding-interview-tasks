# Процент использования объектов

**Сложность:** сложная · **Язык:** SQL (SQLite) · **Темы:** [SQL: группировка](../sql-aggregate/), [Даты и время](../dates/), [SQL: JOIN](../sql-join/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-27?utm_source=github&utm_medium=tasks-repo)**

Для каждой пары «объект — месяц», в которой были бронирования, посчитайте процент занятости и округлите его до одного знака после запятой. Клуб открыт ежедневно с 08:00 до 20:30, это 25 слотов в день. Процент = сумма `slots` за месяц / (25 × число дней в календарном месяце) × 100; дни без бронирований тоже учитываются. Выведите столбцы `name` (название объекта), `month` (первый день месяца, например `2012-09-01`) и `utilisation` (процент). Отсортируйте по `name`, затем по `month`.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — Work out the utilisation percentage for each facility by month](https://pgexercises.com/questions/date/utilisationpermonth.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
