# Пригласивший участник без JOIN

**Сложность:** средняя · **Язык:** SQL (SQLite) · **Темы:** [SQL: JOIN](../sql-join/), [SQL: выборка и фильтры](../sql-filter/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/SQL-13?utm_source=github&utm_medium=tasks-repo)**

Для каждого участника выведите его полное имя и полное имя участника, который его пригласил. Столбцы: `member` и `recommender`; полное имя — имя и фамилия через пробел. Если пригласившего нет, в `recommender` должен быть `NULL`. Не используйте `JOIN`. Одинаковые строки выведите один раз. Отсортируйте по `member`.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises — Produce a list of all members, along with their recommender, using no joins.](https://pgexercises.com/questions/joins/sub.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare
