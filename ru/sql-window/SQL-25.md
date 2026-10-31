# Календарь на месяц

**Сложность:** лёгкая · **Язык:** SQL (SQLite) · **Темы:** [SQL: оконные функции](../sql-window/), [Даты и время](../dates/), [Рекурсия и перебор](../recursion/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-25?utm_source=github&utm_medium=tasks-repo)**

Выведите один столбец `date` со всеми датами октября 2012 года — 31 строка текста вида `YYYY-MM-DD`. Таблицы с данными не используйте.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — Generate a list of all the dates in October 2012](https://pgexercises.com/questions/date/series.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
